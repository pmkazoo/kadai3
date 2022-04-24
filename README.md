# 課題3 -メモ帳アプリ-

## ①課題内容（どんな作品か）
### お絵描き水族館
 キャンバスで描いた絵を水槽の中で飼うことができる
- 指定された枠内に、パレットを使って自由にお絵描きをする
- 任意のキーでスタート
- 降りてくるバーのじゃんけんに勝つように、左上の映像内におさまる形で自分の手でグー、チョキ、パーを出す　※できるだけ背景はシンプルにしてください（顔や体も極力画面外に、、、）
- タイミングは「f」キーを押下する

## ②工夫した点・こだわった点
-  じゃんけんを画像識別できるように「Teachable Machine」で学習・予測モデルを生成し、実装しました
-  PC内臓カメラを使って映像を表示してます

## ③質問・疑問（あれば）
- 特になし

## ④その他（感想、シェアしたいことなんでも）
- 「Teachable Machine」で簡単に機械学習モデルが作れて便利です
- 本当は「f」キーも押下せずにタイミング識別できるようにしたかったです、、
- チョキの識別精度が悪いかもです