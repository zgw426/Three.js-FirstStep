## ウソ穴動作検証結果

|カメラ|配信サーバ|ARサーバ|結果→|Win+Chrome|Win+FireFox|iOS+Safari|iOS+Chrome|
|-------------|--------------------|-----|-----|----------|-----------|----------|------|
|ラズパイカメラ|GStreamer on ラズパイ|Nodejs+自己証明書 on ラズパイ||OK|OK|NG(静止画)|NG(AR動かず)|
|ラズパイカメラ|時雨堂 momo-ayamame|Nodejs+自己証明書 on Win||NG(真っ黒)|OK|NG(静止画)||
|スマホカメラ|時雨堂 sora|Nodejs+自己証明書 on Win||NG(真っ黒)|OK|NG(静止画)||

