ポートフォリオとして開発した映画情報、レビューサービスです。

言語はTypeScript、フレームワークはNext.jsを使用しています。

起動にはあらかじめTMDBのAPIキーを取得し環境変数に設定する必要があります。

バックエンドは[別リポジトリ](https://github.com/ikeyu0806/movie-info-backend)で管理しています。

## TMDB
https://www.themoviedb.org/?language=ja

### Lint
`yarn eslint pages/index.tsx`

### test
`yarn test test/Layout.test.tsx`

### Deploy
Vercelでデプロイしています。

https://movie-info-frontend.vercel.app/

## Author
Yuki Ikegaya

<img width="1330" alt="スクリーンショット 2020-07-26 19 30 39" src="https://user-images.githubusercontent.com/30525452/88476879-bcde5780-cf76-11ea-85b5-46c5e7420d07.png">
