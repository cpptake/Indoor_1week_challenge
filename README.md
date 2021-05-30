# Indoorコンペ 1週間チャレンジの解法
<br>Indoor competition https://www.kaggle.com/c/indoor-location-navigation

## 概要
<br>kaggleのIndoorコンペに1週間限定で参加して、銅メダルを獲得したのでその際のコードを記録します。
<br>詳細な内容については、下記のブログに記載されているのでご確認ください。
<br>https://cpptake.com/archives/791

## パイプライン
1. アンサンブル
2. 後処理1（device idのリークの適用）
3. 後処理2（Snap to gridという方法で、大きく外れている予測値を、近傍のGridに移動させる。）

## 活動のポイント
<br>限られた時間でコンペに参加する場合、
<br>**「Discussionと公開されているCodeの読み込みに尽きると思います。」**
<br>圧倒的に時間が足りない＋submit数が限られている状態であるので
<br>いかに効率的に実験を行うかが重要でした。
<br>反対に、自分のアイデアを入れ込んだモデルの作成などにはほとんど時間を使えなかったので
<br>次回からは2週間以上は時間をとる必要があると感じた。