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
- メモをとるにはとても便利
  - 手順書とかもこれで行けるんじゃないのか？

# github desktop? gitbash?
- こいつら共存できるのか？
  - gitbashでcloneしたところを指定しようとしたら空っぽじゃないとcloneさせてやらんって怒られた。

# 疑問点
- private と public は ファイル・フォルダ・リポジトリのどの単位で可能か？
  - リポジトリ単位で可能、他は不可
- githubdesktopとgitbashで同じ場所にローカルリポジトリを持つことは可能？
  - gitbash はただのツールだから
  - CTRL＋SHITF＋Oでリポジトリを指定してローカルパスを指定してClone
    - File > Add localRipository

- git関係ないけど、仮想デスクトップ切り替えのコツ
  - 開発・DB・その他 って感じに分けたけどやりにくかった（）
  - 同じ案件・プロジェクトは１デスクトップって形が良いのかな？
    - 1 をネット見る専用
      - Gitのレビューとかもここ
    - 2 コード書くところ
      - Tips書いたりするのも用のブラウザとか
      - 結果を表示するブラウザとか置いてる
    - 3 はブランク
      - DBを見るのに使う
    - 4 はチームスやSlask
      - レビュー依頼が着たらそこを開くとMacなら1で開く
    - 5 GithubDesktop
    - 6 お絵描き用
    - AutohotKeyでCTRL+数字で移動できるようにすると便利だよ
