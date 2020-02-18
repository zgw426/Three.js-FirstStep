### ウソ穴-動作検証結果

- ウソ穴の種類

|ウソ穴|タグ|テクスチャ|
|---|---|---|
|aftest01.html|img|画像(tex001.png)|
|aftest02.html|video|動画(test.mp4)|
|aftest03.html|video|ストリーミング(HLS)|

- 検証結果

|ウソ穴|win-FF|Win-Chrome|Win-IE|Win-Edge|iOS13-Safari|Android9-Chrome|
|---|:---:|:---:|:---:|:---:|:---:|:---:|
|aftest01|〇|〇|NG(*2)|〇|〇|〇|
|aftest02|〇|NG(*1)|NG(*2)|〇|NG(*1)|NG(*1)|
|aftest03|〇|〇|NG(*2)|〇|NG(*1)|〇|

(*1) 静止画になる
(*2) エラー

```
Webcam Error
Name:
Message: WebRTC issue-! navigator.mediaDevices not present in your browser
```
