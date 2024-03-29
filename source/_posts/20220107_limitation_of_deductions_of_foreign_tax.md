---
title: 【サラリーマンは効果なし？】外国税額控除の落とし穴
date: 2022-01-07 18:50:45
tags:
- 米国株投資
- ETF
- 外国税額控除
- 確定申告
- 二重課税
- 節税
- ふるさと納税
---

米国株など外国株やETFの配当金をもらったり、売却して利益がでたりしたときにかかってしまう10％の外国税は二重課税になるため確定申告で返ってくる話を人から教えてもらいましたが、
調べてみると限度額があって必ずしも外国税が全額返ってくるとは限らないということでした。

給与所得のサラリーマンの場合、具体的にその限度額の計算式は次の通りです。

```math
F: 課税前の海外の配当金や売却益の金額(円換算)
I = 年収 - 給与所得控除 
外国税額控除限度額 = 所得税 * F / I
```
ここでI(給与所得)の値に社会保険や基礎控除などは考慮されません、課税所得とは大きく異なる数字になるので注意してください。

仮に米国株の年間配当金が税引き前で10万円だったとしたとき、実際に返ってくる金額の限度額は次の通りです。(配偶者控除はありとします)

|年収|500万円|700万円|870万円|1000万円|
|----|----|----|----|----|
|給与所得|356万|520万|675万|805万|
|課税所得|196万|328万|468万|589万|
|所得税+復興税|100874|235340|519178|767485|
|外国税額控除限度額|2833|4525|7691|9533|
|↑限度額の率|2.83%|4.53%|7.69%|9.53%|

この表は控除が配偶者控除くらいしかない人向けの数字なので多めにでていますが、それでも年収が低いうちは少ししか返ってこないみたいです。
ただし、これは所得税分の控除計算であり、確定申告によって住民税も安くなります。だいたい所得税控除額の30%程度とのことなので、この表で言うと年収870万円以上ある人はほぼ全額外国税額をとりかえすことができそうです。

しかしながら、住宅ローン控除、iDeCoなどの小規模年金控除、扶養控除、ふるさと納税などを行っている人は課税所得が小さくなり、この限度額が大きく下がってしまいます。
サラリーマンは外国税額控除は期待しないか、大きく稼ぐように努力すべきかもしれません。米国株投資に集中したい人はふるさと納税などは控えた方がいいのかもしれません。

参考にしたリンクは以下のとおりです。

* [国税庁 確定申告作成コーナー](https://www.keisan.nta.go.jp/kyoutu/ky/sm/top#bsctrl)
* [外国税額控除制度とは？二重課税されないために知っておくべきこと](https://biz.moneyforward.com/accounting/basic/23344/)

具体的に作成した確定申告はこちら:
![年収870万の確定申告](/images/tax_report_foreign_tax_deduction.png)

