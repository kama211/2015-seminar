#2015 後期研究　箱積みゲーム

#作成したAIの結果
アルゴリズム:ミニマックス法
 - オープン戦 : 10戦8勝2敗
 - 公式戦 : 14戦10勝4敗
 - 決勝トーナメント : 準々決勝敗退

###箱が4つ並ぶと勝利する「箱積みゲーム」プログラム
 

####各プログラムの内容

[gamePvsP.c](https://github.com/OgamiP/2015/blob/master/gamePvsP.c)

二人のプレイヤーで箱積みゲームを行う

[v_plays.c](https://github.com/OgamiP/2015/blob/master/v_plays.c)

箱が4つ並ぶ手を見つける

[d_plays.c](https://github.com/OgamiP/2015/blob/master/d_plays.c)

箱が4つ並ぶことを防ぐ手を見つける

[gamePvsC_1.c](https://github.com/OgamiP/2015/blob/master/gamePvsC_1.c)

プレイヤーとCPUの対局（こちらはCPU側の手は完全ランダム）

[pvc_R.c](https://github.com/OgamiP/2015/blob/master/pvc_R.c)

中間発表時に使用したもの。実行時の引数にどちらが先行かの情報与える処理だけ追加

[min_max_d3.c](https://github.com/OgamiP/2015/blob/master/min_max_d3.c)

ミニマックス法を加えたPvC

[Min_Max_Auot.c](https://github.com/OgamiP/2015/blob/master/Min_Max_Auot.c)

vs乱数AI試行実験プログラム
