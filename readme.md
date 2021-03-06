# プロダクトのタイトル
週末の家事分担アプリ「KAJI SHARE」

## プロダクトの紹介

- 「KAJI SHARE」は週末の2人の家事分担をカンタンに決められるアプリです。
- 男性・女性それぞれが週末の家事を「やりたい」「やってほしい」「やらなくていい」の３択で計５問選ぶと、週末の家事分担が決まります。
- お互いにやりたくない家事はランダムでどちらがやるか決まります。
- 結果発表のページでメモを残すことができます。
- スマホに特化したデザインで作成したので、ディベロッパーツールでスマホ画面の表示でご利用ください。
※GithubでデプロイしたページではCSSがうまく作動しなかったので、コードをダウンロードしてご確認ください。

## 工夫した点，こだわった点

- 前回のじゃんけんアプリの課題の際、途中で断念したプロダクトに再チャレンジしました。
- ローカルストレージで保存した結果をじゃんけん要素(かじのランダム表示)で利用しています。
- スライドで表示を切り替え、できるだけファーストビュー内に表示が収まるようにしています。

## 苦戦した点，共有したいハマりポイントなど

- 「次の家事選択へ」のボタンを押さなくても質問が切り替わり、最終的に分担結果を導き出す仕様にしたかったのですが、うまく書けず断念しました。
- 繰り返し同じような処理が走る箇所が多かったのでfor文などを使ってシンプルに書きたかったのですが、うまくいかず力技になりました。
- 1度回答が終わると、トップページから「前回の結果」が見れるボタンを追加していますが、結果にランダム関数があるので、ランダム関数部分は前回異なる場合があり、解決策がわかりませんでした。

## URL
https://nkunitake.github.io/memopad-kajishare/
