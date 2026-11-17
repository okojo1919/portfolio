# portfolio

okojo1919 のポートフォリオサイト（静的1ページ）。Cloudflare Pages で公開する。

## 公開手順

1. Cloudflare ダッシュボード → Workers & Pages → Create → Pages → Connect to Git
2. GitHub の `okojo1919/portfolio` を選択
3. Build settings: Framework preset = None、Build command = 空、Output directory = `/`（ルート）
4. Deploy すると `https://portfolio-xxx.pages.dev` のようなURLが発行される

## メモ

- 本名は載せていない（ハンドル表記）。就活で提出用に使う段階で、氏名と連絡先を入れるか判断する。
- 内容を直したら GitHub に push するだけで自動で再デプロイされる。
