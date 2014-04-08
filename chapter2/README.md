# gitbook コマンドのオプション

- gitbook の build の際にオプションを指定できる

## タイトルの指定

- 一番上の帯に表示されるタイトル名を変更できる
- デフォルトでは repository の名前が採用される

` $ gitbook -t Gitbookの使い方をGitbookで説明する build `

## 説明の指定

- pending

## GitHubのリポジトリ指定

- pending

## outputするディレクトリの指定

- pending

## フォーマットの指定

- 出力するフォーマットを指定できる
  - デフォルトでは Static Website 形式
  - Single Page
    - `$ gitbook build . -f page`
    - 試したけどうまくいかない(´・ω・｀)
    - 一階層目のPageが表示されない
    - そういう仕様なのか？
  - PDF
    - `$ npm install gitbook-pdf -g `
    - `$ gitbook pdf .`
    - Single Page で build した場合の見た目のPDFができる
  - eBook
    - pending
  - JSON
    - `$ gitbook build . -f json`
    - json 形式で出力される

## GitHubのHost指定

  - pending

## テーマの指定

  - pending
