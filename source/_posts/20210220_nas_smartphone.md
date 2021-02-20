---
title: Windowsパソコンがなくても大丈夫！スマホだけでIOデータのNASの初期設定をする方法
date: 2021-02-20 16:07:45
tags:
- IODATA
- LanDisk
- NAS
- スマホ
---

写真や失いたくないデータを保存しておくためにNASを買いました。(参考: [マンガで解説NAS](https://www.buffalo.jp/topics/knowledge/detail/nas-comic.html#a01))

購入したモデルはこれ
<table border="0" cellpadding="0" cellspacing="0"><tr><td><div style="border:1px solid #95a5a6;border-radius:.75rem;background-color:#FFFFFF;width:504px;margin:0px;padding:5px;text-align:center;overflow:hidden;"><table><tr><td style="width:240px"><a href="https://hb.afl.rakuten.co.jp/ichiba/1efd0fd7.abfabb73.1efd0fd8.c2516586/?pc=https%3A%2F%2Fitem.rakuten.co.jp%2Fyamada-denki%2F7154726015%2F&link_type=picttext&ut=eyJwYWdlIjoiaXRlbSIsInR5cGUiOiJwaWN0dGV4dCIsInNpemUiOiIyNDB4MjQwIiwibmFtIjoxLCJuYW1wIjoicmlnaHQiLCJjb20iOjEsImNvbXAiOiJkb3duIiwicHJpY2UiOjEsImJvciI6MSwiY29sIjoxLCJiYnRuIjoxLCJwcm9kIjowLCJhbXAiOmZhbHNlfQ%3D%3D" target="_blank" rel="nofollow sponsored noopener" style="word-wrap:break-word;"  ><img src="https://hbb.afl.rakuten.co.jp/hgb/1efd0fd7.abfabb73.1efd0fd8.c2516586/?me_id=1357621&item_id=10449467&pc=https%3A%2F%2Fthumbnail.image.rakuten.co.jp%2F%400_mall%2Fyamada-denki%2Fcabinet%2Fa07000039%2F7154726015.jpg%3F_ex%3D240x240&s=240x240&t=picttext" border="0" style="margin:2px" alt="[商品価格に関しましては、リンクが作成された時点と現時点で情報が変更されている場合がございます。]" title="[商品価格に関しましては、リンクが作成された時点と現時点で情報が変更されている場合がございます。]"></a></td><td style="vertical-align:top;width:248px;"><p style="font-size:12px;line-height:1.4em;text-align:left;margin:0px;padding:2px 6px;word-wrap:break-word"><a href="https://hb.afl.rakuten.co.jp/ichiba/1efd0fd7.abfabb73.1efd0fd8.c2516586/?pc=https%3A%2F%2Fitem.rakuten.co.jp%2Fyamada-denki%2F7154726015%2F&link_type=picttext&ut=eyJwYWdlIjoiaXRlbSIsInR5cGUiOiJwaWN0dGV4dCIsInNpemUiOiIyNDB4MjQwIiwibmFtIjoxLCJuYW1wIjoicmlnaHQiLCJjb20iOjEsImNvbXAiOiJkb3duIiwicHJpY2UiOjEsImJvciI6MSwiY29sIjoxLCJiYnRuIjoxLCJwcm9kIjowLCJhbXAiOmZhbHNlfQ%3D%3D" target="_blank" rel="nofollow sponsored noopener" style="word-wrap:break-word;"  >アイ・オー・データ機器 HDL2-AAX8 NAS PC向け 8TB搭載／2ベイ デュアルコアCPU搭載 HDL2-AAXシリーズ</a><br><span >価格：48730円（税込、送料別)</span> <span style="color:#BBB">(2021/2/20時点)</span></p><div style="margin:10px;"><a href="https://hb.afl.rakuten.co.jp/ichiba/1efd0fd7.abfabb73.1efd0fd8.c2516586/?pc=https%3A%2F%2Fitem.rakuten.co.jp%2Fyamada-denki%2F7154726015%2F&link_type=picttext&ut=eyJwYWdlIjoiaXRlbSIsInR5cGUiOiJwaWN0dGV4dCIsInNpemUiOiIyNDB4MjQwIiwibmFtIjoxLCJuYW1wIjoicmlnaHQiLCJjb20iOjEsImNvbXAiOiJkb3duIiwicHJpY2UiOjEsImJvciI6MSwiY29sIjoxLCJiYnRuIjoxLCJwcm9kIjowLCJhbXAiOmZhbHNlfQ%3D%3D" target="_blank" rel="nofollow sponsored noopener" style="word-wrap:break-word;"  ><img src="https://static.affiliate.rakuten.co.jp/makelink/rl.svg" style="float:left;max-height:27px;width:auto;margin-top:0"></a><a href="https://hb.afl.rakuten.co.jp/ichiba/1efd0fd7.abfabb73.1efd0fd8.c2516586/?pc=https%3A%2F%2Fitem.rakuten.co.jp%2Fyamada-denki%2F7154726015%2F%3Fscid%3Daf_pc_bbtn&link_type=picttext&ut=eyJwYWdlIjoiaXRlbSIsInR5cGUiOiJwaWN0dGV4dCIsInNpemUiOiIyNDB4MjQwIiwibmFtIjoxLCJuYW1wIjoicmlnaHQiLCJjb20iOjEsImNvbXAiOiJkb3duIiwicHJpY2UiOjEsImJvciI6MSwiY29sIjoxLCJiYnRuIjoxLCJwcm9kIjowLCJhbXAiOmZhbHNlfQ==" target="_blank" rel="nofollow sponsored noopener" style="word-wrap:break-word;"  ><div style="float:right;width:41%;height:27px;background-color:#bf0000;color:#fff!important;font-size:12px;font-weight:500;line-height:27px;margin-left:1px;padding: 0 12px;border-radius:16px;cursor:pointer;text-align:center;">楽天で購入</div></a></div></td></tr></table></div><br><p style="color:#000000;font-size:12px;line-height:1.4em;margin:5px;word-wrap:break-word"></p></td></tr></table>

届いた同梱物は
- 本体
- 説明書
- 電源アダプタ、ケーブル
- LANケーブル

![IOData_NAS](/images/151413618_3709472049170374_1324032740198089090_n.jpg)

## 機器の配線と設置

LANケーブルでルーターの空いているポートと接続してコンセントを指すだけです。私はルーターの近くの涼しいところに設置しました。
電源ボタンを押すと起動しランプの点滅が始まります。しばらくすると起動が完了します、ピーと音がなるのでびっくりしないでください。

![](/images/landisk_setup_connect_fig03.png)

## スマホから初期設定

スマホをWifiで接続し、ブラウザでNASの設定画面にアクセスすることができます。私はAndroidのXperiaで設定しました。自分のNASのアドレスについては [FileCommander](https://play.google.com/store/apps/details?id=com.mobisystems.fileman&hl=ja&gl=US)というアプリで確認できます。

### NASのアドレスを確認する

File Commander を起動し、メニューから「ローカルネットワーク」を選択します。↻ みたいなボタンを押すと設置したNASのアドレスがわかります。「LANDISK-XXXX」みたいな名前のやつがそれです。192.168.XXX.YYY みたいな数字のアドレスをメモしておきましょう。


### ブラウザでアクセスする

