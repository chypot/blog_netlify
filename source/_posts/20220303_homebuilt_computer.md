---
title: 16万円で最新の部品で作るコスパ最強の自作PCの作り方
date: 2022-03-03 17:50:45
tags:
- 自作PC
- CPU
- Intel
- MagTOMAHAWK
- Mdot2SSD
- HomebuiltComputer
---

最新の第12世代Intel CPUと次世代規格のDDR5メモリ、そして M.2 SSDストレージを使ったパソコンをパーツから自作しました。

## 概要

||メーカー|モデル・性能|値段|
|----|----|----|----:|
|CPU|Intel 🇺🇲|[第12世代 Core i7 12700K](https://amzn.to/36ZpAl1)|49,990|
|CPUファン|Ainex 🇯🇵|[120mmファン Intel&AMD用](https://amzn.to/3CavvPz)|3,273|
|マザーボード|MSI 🇹🇼|[MSI MAG B660 TOMAHAWK WIFI DDR5](https://amzn.to/3sBZdK5)|31,300|
|メモリ|Kingston 🇺🇲|[DDR5 5200MHz 16GBx2枚](https://amzn.to/3pw4wZy)|39,600|
|ストレージ|Western Digital 🇺🇲|[M.2 SSD 2280 2TB](https://amzn.to/3sCTnZ0)|28,500|
|グラフィックボード|なし||0|
|ケース| Thermaltake 🇹🇼|[ミドルタワー型PCケース](https://amzn.to/36Ri9Mt)|4,850|
|電源|玄人志向 🇯🇵|[80PLUS Bronze 750W](https://amzn.to/35olbri)|9,380 |
|||合計|163,620|

## 組立作業
### マザーボード
2022年2月に発売されたばかりのMSIの新しいモデルです。DDR5を使いたいので似たモデルのDDR4と間違わないように注意です。
M.2 SSD が3枚、SATA接続のストレージが6つ取り付けることができます。Wifi 6 にも対応しています。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B09NVQX9RK&linkId=cc82a56655990dbb66baef6ff0972736"></iframe>

袋からマザーボードを取り出し、箱の上に袋を敷いてその上で作業を始めます。取扱説明書は今は付属していないようなので、[公式サイトからPDFを参照します](https://download.msi.com/archive/mnu_exe/mb/MAGB660TOMAHAWKWIFI.pdf)。

![マザーボードの図](MsiMagTomahawkB660_DDR5.png)

### CPUを取り付ける

このCPUはピンがないのでピンを折る心配はありません。上下の向きを気をつけて配置します。黒い蓋は自動的に取れるものなので無理に取らないようにします。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B09FXNVDBJ&linkId=6c805ffab7664e13f3fe302e25cf0175"></iframe>

最近はリテールクーラーは付属していないので別途CPUクーラーを購入する必要があるので注意しましょう。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B097CXXDTW&linkId=07adf291d851ac2f7ac70f72db617db9"></iframe>

このファンはマザーボードの裏側から台座を取り付けて取り付けます。
マザーボード上の文字が `CPU_FAN1` だけ小さくて見にくいですが右上にあるので、ファンのケーブルがちょうど届くように向きを注意して取り付けます。

### メモリ

メモリを2枚だけ指す時はBチャネルの `DIMMB1` `DIMMB2` に指すのが一番いいらしいのでマニュアルを見つつそうしました。

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B09KCLP63B&linkId=6b21f20e66e190de83ca00c175966dc0"></iframe>

### M.2 SSD

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B07SQXHQ6J&linkId=e71b550e6c6260a96d8f8d0a0992f815"></iframe>

M.2 SSDが刺さる場所は `M2_1`, `M2_2`, `M2_3` と3箇所ありますが、 このタイプのSSDは 2または3 に刺さないと認識されないようです。
フタみたいなやつはヒートシンクです。ビニールを外して忘れず取り付けましょう。

### ケースへのとりつけ

まずケースから出ているいくつかのケーブルをマザーボードに接続してからマザーボードをケース内に取り付けます。


フロントパネルの電源ボタンなどのためのフロントパネルコネクター、フロントパネルのUSB接続のためのUSB Gen 1 コネクター、フロントのオーディオジャックのためのオーディオコネクターを差し込みます。
次に、ケースに付属するスペーサーをマザーボードのねじ穴に合わせて配置してマザーボードを取り付けます。

ケースファンのケーブルを最も近い `SYS_FAN` のどこかに差します。

### 電源

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//rcm-fe.amazon-adsystem.com/e/cm?lt1=_blank&bc1=000000&IS2=1&bg1=FFFFFF&fc1=000000&lc1=0000FF&t=renzoku-22&language=ja_JP&o=9&p=8&l=as4&m=amazon&f=ifr&ref=as_ss_li_til&asins=B078HFLJ4C&linkId=9e27a8e555af52c0beee9e573d0a6e74"></iframe>

電源をケースに取り付けます。次に今回は以下のケーブルだけを使うので、それぞれを背面から出してマザーボードに接続します。

- CPU電源コネクター1つを `CPU_PWR1` へ
- 電源コネクタを `ATX_PWR1` へ


## 起動確認

電源プラグ、キーボードとディスプレイを接続して電源スイッチを入れます。ファンが回転し、画面にBIOSが表示されれば接続されている部品が認識されているか確認することができます。

電源スイッチを長押しすることでOFFにできます。

## トラブルシューティング

### パワースイッチを押しても、ファンが回転せずウンともスンともいわない

- 電源のスイッチがOFFになっている
- フロントパネルコネクターの取り付けが間違っている: 左右逆にしているとリセットボタンで電源がついちゃったりします

### M.2 SSDが認識されない

`M2_1` へは取り付けることはできますが、マザーボードから認識されません。今回のSSDは `M2_2` または `M2_3` に取り付ける必要があります。


