# 課題3 -メモ帳アプリ-

## ①課題内容（どんな作品か）
### お絵描き水族館
 キャンバスで描いた生き物を水槽の中で飼うことができる
- 指定された枠内に、パレットを使って自由にお絵描きしてください 
　※ブラウザの画面が上までスクロールしきった状態でお絵描きしてください
- 書き直したい場合は「書き直し」ボタンをクリックしてください
- 書き終えたら「生き物の名前」を入力して「登録」ボタンをクリックしてください　※この時点ではまだ水槽に表示はされないです
- 「水槽をのぞいてみる」ボタンをクリックすると、登録した生き物が表示されます。クリックするたびに、生き物の場所が変わります
- 「新しい水槽にする」ボタンをクリックすると、今まで登録した生き物が全て削除されます

## ②工夫した点・こだわった点
-  生き物の名前をkey、キャンバスの絵をvalueにしてLocal Storageに保存することで、たくさんの生き物を水槽に表示できるようにしました
-  水槽内の生き物の位置をランダムにしました。また、生き物が見切れてしまわないように座標調整をしました
-  パレットを表示し、自由なお絵描きを可能にしました

## ③質問・疑問（あれば）
- 特になし

## ④その他（感想、シェアしたいことなんでも）
- 本当は生き物を動かしたり、餌をあげるようなアクションを追加したかったですが、時間の都合上断念しました
- cssは必要最小限です、、、
