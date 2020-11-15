# アプリ概要
RRRead.com は読んだ本の内容をより効率よく定着させるために開発した、本のアウトプット専用アプリです。

読んだ本をアウトプットし知識を定着させるために、知識の定着に有用であると科学的に証明されている全20個の質問にお答えいただくことで、知識を定着させその知識を実生活に活かして欲しいと思い開発しました。

科学的に証明された記憶の定着に大切なことは主に下記の3つであるとのことです。

1. 想起すること
2. アウトプットするためのインプットする(本を何回も読む等は受け身のインプットになりやすいとのこと)
3. 現在自分が持っている知識と、インプットしたい知識の共通点を繋げる(知識のチャンク化) 


こちらで用意した全ての質問に、読んだ本の内容を想起しながらお答えいただくことで、"内容の想起" "能動的に本を読む" "知識のチャンク化を促進する質問" の3つを自動的に行っていただき、効率よく知識を定着させる助けになるように設計いたしました。 

## 現時点でデプロイが完了していないため、ローカルで使用したスクリーンショットを貼り付け致します。

トップページ
![localhost_3000_ (1)](https://user-images.githubusercontent.com/67489015/98756559-2bec9880-240e-11eb-911c-41c4276320c5.png)

本の登録アウトプットページ
![localhost_3000_](https://user-images.githubusercontent.com/67489015/98757037-01e7a600-240f-11eb-9145-34a07fe5b095.png)

マイページ
![localhost_3000_users_3 (1)](https://user-images.githubusercontent.com/67489015/98773722-de335880-242c-11eb-84aa-397330d35447.png)


本の詳細ページ
![localhost_3000_users_3](https://user-images.githubusercontent.com/67489015/98773535-77ae3a80-242c-11eb-9090-8266f9d0515b.png)



# 使用技術・言語
- フロントエンド(javascript, jQuery, HTML/CSS, Sass)
- バックエンド(Ruby on Rails6.0.3)
- Web サーバ(nginx, unicorn)
- データベース(MySQL
- AWS(EC2, ECS, SSM, S3, CLI)
- 開発環境(MacOS, VScode, Git, GitHub)

# 機能要件
## 本の登録
　- 本のアウトプットを記入し保存する
　- 質問とそれに紐付いた回答の観覧
　- 登録した本の編集、削除機能
## ユーザー機能
　- ユーザーの登録
　- マイページにて登録した本の一覧の観覧をする
 
# このアプリで解決したい課題
1. 本で得た知識を実生活に役立てて、日々の生活を豊かにする。

2. 読みたい本が沢山あるが、時間がないと言う方は多いと思いますが、そんな方のために、本で得た知識をより効率よく知識を定着させ、一冊に当てる読書の時間を短縮したい。

3. 現時点では実装できていないが、本の要約文の投稿機能、いいねボタン、ユーザーのフォロー機能を実装し、ユーザーが今まで興味がなかったようなジャンルの本との出会いを作る。

## 詳細
- 知識は使うことで初めて役に立つので、そのためには得た知識を覚えていることが重要と考え、知識の定着に役に立つと科学的に証明された質問に答えていただき、実生活に役立てていただきたいと思いこちらのアプリを作成いたしました。

- 全20問の質問はなかなか覚えていられないかと思いますが、RRRead.com を利用することで手軽に質問を観覧できます。

- 本を読んだ後に、本の内容を想起し質問に答えることを意識していただくことで、読書が受動的になりにくいので、結果的に一回の読書でより多くの情報を覚えることができ、その結果読書時間の短縮に繋がると思いました。

- RRRead.com の名前の由来は、ユーザーにより多くの本を効率よくインプットできるようにと思いを込めて、頭文字の「R」を3つに致しました。
