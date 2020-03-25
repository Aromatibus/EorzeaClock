# FinalFantasy 14 Eorzea Clock ACT Overlay

## 素晴らしい冒険の世界を与えてくれたSquare Enixに感謝します。</BR>そしてACTやプラグイン、その他のツールを開発されている方達に感謝いたします。

## Thanks to Square Enix for giving us a wonderful world of adventure.</BR>And thanks to the people who develop ACT, plugins and other tools.
---
[Onlinegaming.life](https://onlinegaming.life/) 様で紹介されていました。  
とっても詳しく使い方を紹介してくださっています。ありがとうございます。&#x1f60a;

[ACTでEorzeaClockを導入する方法](https://onlinegaming.life/ff14/eorzeaclock/) (JP) How to introduce EorzeaClock in ACT.

---

エオルゼアの秒数まで表示する時計です。  
これは、Advanced Combat Tracker用オーバーレイです。  
画面にローカル時間、サーバー時間、エオルゼア時間を表示します。  
[ngld/OverlayPlugin](https://github.com/ngld/OverlayPlugin)で動作を確認しました。
"*`MiniParseOverlay`*" で追加してください。  
表示するURLは、"**`https://aromatibus.github.io/EorzeaClock/`**"です。  
PCに詳しい方は "*`index.html`*" をPCに保存して改造できます。  
楽しんでいただければ幸いです。

It is a clock that displays even the seconds of Eorzea.  
This is an overlay for the Advanced Combat Tracker.  
Local time, server time, and Eorzea time are displayed on the screen.  
I checked the behavior with [ngld/OverlayPlugin](https://github.com/ngld/OverlayPlugin).
"*`MiniParseOverlay`*" to add it.  
The URL to be displayed is "**`https://aromatibus.github.io/EorzeaClock/`**".  
If you are familiar with PC, you can save "*`index.html`*" to your PC and modify it.  
I hope you enjoy it.

![表示例1 (LTET-White)](https://user-images.githubusercontent.com/54123288/74087730-75503600-4ad2-11ea-9f67-bc2332726bd2.png)
![表示例2 (LTET-NeonBlue)](https://user-images.githubusercontent.com/54123288/74087731-75e8cc80-4ad2-11ea-86c1-0785a92ec943.png)
![表示例3 (LTET-NeonRed)](https://user-images.githubusercontent.com/54123288/74087732-76816300-4ad2-11ea-9dc8-0449bd92aebe.png)
![表示例4 (LTET-Black)](https://user-images.githubusercontent.com/54123288/74087734-7719f980-4ad2-11ea-9810-0814f1ecbe5f.png)

![表示例5 (STET)](https://user-images.githubusercontent.com/54123288/74087735-7719f980-4ad2-11ea-9c48-367ffc593cd8.png)
![表示例6 (LTSTET)](https://user-images.githubusercontent.com/54123288/74087736-77b29000-4ad2-11ea-8da5-6ea538bf00df.png)
![表示例7 (YYYYMMDD-LTET)](https://user-images.githubusercontent.com/54123288/74087737-77b29000-4ad2-11ea-8b31-86927c3df99f.png)
![表示例8 (Zoom)](https://user-images.githubusercontent.com/54123288/74087738-784b2680-4ad2-11ea-8e56-649f71b0556e.png)

表示された時計をクリックすると表示形式を変更します。  
ダブルクリックすると拡大します。一定まで大きくなると最小になります。  

ローカル時間、エオルゼア時間はPCの時間を基準にしています。  
サーバー時間はNICTのサーバーからJST（日本標準時）を取得し、UTC（協定世界時）を計算しています。

Click on the displayed clock to change the display format.  
Double click to enlarge. When it grows to a certain size, it becomes the minimum.  

Local time and Eorzea time are based on PC time.  
The server time is obtained from the NICT server in JST (Japan Standard Time) and calculated in UTC (Coordinated Universal Time).

[NICT クライアント開発者向け情報（NICT SERVER Guidelines）](http://www.nict.go.jp/JST/http.html)

# License

[MIT License](https://github.com/Aromatibus/vscode-kindfeeling-light/blob/master/./LICENSE) &copy; [Aromatibus](https://github.com/Aromatibus)
