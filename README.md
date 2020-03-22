# FinalFantasy 14 Eorzea Clock ACT Overlay

素晴らしい冒険の世界を与えてくれたSquare Enixに感謝します。
そしてACTやプラグイン、その他のツールを開発されている方達に感謝いたします。
Thanks to Square Enix for giving us a wonderful adventure world.
And thanks to those who develop ACT, plugins and other tools.
---
エオルゼアの秒数まで表示する時計です。
A clock that displays up to Eorzea seconds.

これは、Advanced Combat Tracker用オーバーレイです。
画面にローカル時間とエオルゼア時間を表示します。
ngld/OverlayPlugin https://github.com/ngld/OverlayPlugin で動作を確認しました。
"MiniParseOverlay" で追加してください。
表示するURLは、https://aromatibus.github.io/EorzeaClock/ です。
PCに詳しい方は "index.html" をPCに保存して改造できます。
楽しんでいただければ幸いです。

This is an overlay for Advanced Combat Tracker.
Displays the local time and Eorzea time on the screen.
ngld/OverlayPlugin https://github.com/ngld/OverlayPlugin has confirmed the operation.
Please add with "MiniParseOverlay".
The URL to be displayed is "https://aromatibus.github.io/EorzeaClock/".
If you are familiar with PC, you can save "index.html" on PC and modify it.
I hope you enjoy it.

![表示例1 (LTET-White)](https://user-images.githubusercontent.com/54123288/74087730-75503600-4ad2-11ea-9f67-bc2332726bd2.png)
![表示例2 (LTET-NeonBlue)](https://user-images.githubusercontent.com/54123288/74087731-75e8cc80-4ad2-11ea-86c1-0785a92ec943.png)
![表示例3 (LTET-NeonRed)](https://user-images.githubusercontent.com/54123288/74087732-76816300-4ad2-11ea-9dc8-0449bd92aebe.png)
![表示例4 (LTET-Black)](https://user-images.githubusercontent.com/54123288/74087734-7719f980-4ad2-11ea-9810-0814f1ecbe5f.png)
![表示例5 (STET)](https://user-images.githubusercontent.com/54123288/74087735-7719f980-4ad2-11ea-9c48-367ffc593cd8.png)
![表示例6 (LTSTET)](https://user-images.githubusercontent.com/54123288/74087736-77b29000-4ad2-11ea-8da5-6ea538bf00df.png)
![表示例7 (YYYYMMDD-LTET)](https://user-images.githubusercontent.com/54123288/74087737-77b29000-4ad2-11ea-8b31-86927c3df99f.png)
![表示例8 (Zoom)](https://user-images.githubusercontent.com/54123288/74087738-784b2680-4ad2-11ea-8e56-649f71b0556e.png)

表示された時計をクリックすると表示形式を変更します。ダブルクリックすると拡大します。一定まで大きくなると最小になります。
Click the displayed clock to change the display format. Double click to enlarge. It reaches a minimum when it reaches a certain level.

NICTのサーバーからJST(日本標準時)を取得しUTC(協定世界時)=ST(サーバー時間)を計算しています。
JST (Japan Standard Time) is obtained from the NICT server and UTC (Coordinated Universal Time) = ST (server time) is calculated.
NICT SERVER Guidelines >> http://http://www.nict.go.jp/JST/http.html

ローカル時間、エオルゼア時間はPCの時間を基準にしています。

2020/03/22  
正確な世界のローカル時間の計算やその他、途中までいろいろと実装しましたが必要なことではないと思い一旦、開発終了といたします。  
We performed a variety of other calculations, such as accurate calculations of local time around the world, but stopped thinking we didn't think it was necessary.
