# github

ソース管理するサービス

# com? enterprise?
comは個人
enterpriseは有料っぽい

# コマンド

## フォルダコピー

```
git mv oldfolder newfolder

# 初期設定
$ git config --global user.name "user name"
$ git config --global user.email mail@address.com
```

# private? public?

プライベートだと招待した人しか見れない
そしてリポジトリ単位でしか変更できない

# コマンド

## ファイル名の変更
$ git mv 元ファイル 先ファイル

## コミット対象にするやつ
$ git add howToUse.md
## コミット（ローカルでやるやつ）
$ git commit -m ”コミットコメント"
## プッシュ（本体に登録するやつ）
$ git push

コマンドはみんなこのあたりに書いてある。
https://qiita.com/2m1tsu3/items/6d49374230afab251337

## github繋がらんのだけど。
- gitbashでのどうにも繋がらない
  - 解決方法：githubには.pubの全文、configには.pub無い方を指定する。
  - 日本語ユーザだと駄目だとかあった。
    - とりあえず英語だけのユーザ作成したら何事もなく接続できた。
      - configファイルが読めないことが原因な気がするので、
      日本語ユーザで↑の鍵を読み込みに行くように設定したら接続はできたが、
      そもそもの原因としてconfigに.pubを設定していたことだった。（白目）

# .mdファイル
- マークダウンでの書き方について調べたい。

# github desktop? gitbash?
- こいつら共存できるのか？
  - gitbashでcloneしたところを指定しようとしたら空っぽじゃないとcloneさせてやらんって怒られた。




