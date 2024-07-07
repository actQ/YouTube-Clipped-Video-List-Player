# YouTube-Clipped-Video-List-Player

## 概要
再生時間を指定した動画(切り抜き)のリストを再生します。  

**(想定利用例)**
* 複数の歌枠配信やライブのアーカイブから曲単位でランダムに再生する。  
    配信Aの曲X → 配信Bの曲N → 配信Aの曲Z → 配信Aの曲Y → 配信Cの曲M → ...

## 使い方

1. [こちら](https://actq.github.io/YouTube-Clipped-Video-List-Player/) にアクセスします。

2. テキストボックスに以下の形式を改行区切りで入力します。
  ```
  {Youtubeの動画URL}, {開始時間}, {終了時間}, {タイトル}
  ```
  ※1 開始時間,終了時間を省略した場合は動画全体とします。
  
3.  [Load Videos] をクリック。
   "Random"にチェックがついている場合はリストをランダムに再生します。

## 入力例

例として、私の推しの歌枠、3Dライブ、MVをリストにしました。ぜひ見てください。💫

```
https://www.youtube.com/watch?v=FzwYKoKN_KE
https://www.youtube.com/watch?v=mcQs0iQE0bs
https://www.youtube.com/watch?v=Otb3etOEe0A,14:27,17:15,Bling-Bang-Bang-Born
https://www.youtube.com/watch?v=Otb3etOEe0A,18:01,20:43,ラビットホール
https://www.youtube.com/watch?v=Otb3etOEe0A,22:31,26:51,もってけ！セーラーふく
https://www.youtube.com/watch?v=Otb3etOEe0A,29:52,31:49,人マニア
https://www.youtube.com/watch?v=Otb3etOEe0A,37:12,40:34,じゃじゃ馬にさせないで
https://www.youtube.com/watch?v=Otb3etOEe0A,43:10,47:19,微笑みの爆弾
https://www.youtube.com/watch?v=Otb3etOEe0A,51:46,54:47,トウキョウ・シャンディ・ランデヴ
https://www.youtube.com/watch?v=Otb3etOEe0A,57:50,1:00:44,鬼ノ宴
https://www.youtube.com/watch?v=xc6vQ3lzaUE,06:05,09:16,V.I.P
https://www.youtube.com/watch?v=xc6vQ3lzaUE,12:17,15:05,エゴロック
https://www.youtube.com/watch?v=xc6vQ3lzaUE,16:31,20:46,ロビンソン
https://www.youtube.com/watch?v=xc6vQ3lzaUE,22:57,27:57,中空の庭
https://www.youtube.com/watch?v=xc6vQ3lzaUE,29:50,33:57,astro
https://www.youtube.com/watch?v=xc6vQ3lzaUE,36:57,40:34,水たまり
https://www.youtube.com/watch?v=xc6vQ3lzaUE,43:09,46:30,勇者
https://www.youtube.com/watch?v=xc6vQ3lzaUE,47:53,50:35,テレキャスタービーボーイ(long.ver)
https://www.youtube.com/watch?v=lVQlIvUr5Dc,1:42,5:37,Over Soul
https://www.youtube.com/watch?v=lVQlIvUr5Dc,6:48,11:00,only my railgun
https://www.youtube.com/watch?v=lVQlIvUr5Dc,11:08,14:31,怪物
https://www.youtube.com/watch?v=lVQlIvUr5Dc,14:50,18:04,勇者
https://www.youtube.com/watch?v=lVQlIvUr5Dc,18:20,22:38,そばかす
https://www.youtube.com/watch?v=lVQlIvUr5Dc,23:00,27:38,Shangri-La
https://www.youtube.com/watch?v=lVQlIvUr5Dc,27:55,33:03,ETERNAL BLAZE
https://www.youtube.com/watch?v=lVQlIvUr5Dc,33:18,37:24,革命デュアリズム
https://www.youtube.com/watch?v=lVQlIvUr5Dc,37:28,41:25,佐賀事変
https://www.youtube.com/watch?v=lVQlIvUr5Dc,41:50,46:26,聖少女領域
https://www.youtube.com/watch?v=lVQlIvUr5Dc,47:00,50:22,おらくる
https://www.youtube.com/watch?v=lVQlIvUr5Dc,50:30,55:11,花の塔
```
