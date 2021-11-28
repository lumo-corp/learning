# Learning

プログラミングなどを学習する際のお手伝いになりそうなドキュメントまとめ。

ここに書いていないものは適宜ネットから見つけてやってください。仕様などで困ったときは公式ドキュメントを読むと幸せになれるかも。

マークダウンで記述されているので、誤字脱字、内容にミス等あれば修正依頼のPull Request(PR)をお願いします。また、何か書き残したい場合は是非どうぞ。
編集したい場合は以下の方法で可能です。

- GitHub.com上のエディタ（簡易的なもの）
- クローンしてローカルでの編集
- リポジトリページでキーボードの` . `キーを押下→`github.dev`版のVSCode
  - https://github.dev/novalumo-developers/learning

## カテゴリー一覧

- [JavaScript](./javascript/README.md)
- [Node.js](./nodejs/README.md)
- [Git](./git/README.md)
- [Discord](./discord/README.md)

## GitHub.com上でのファイル追加

1. `Add file`→`Create new file`を選択

![](./_img/00001.png)

2. コードを書ける画面が表示されるので、`Name your file...`にファイル名を入力して内容を書き込んだら、一番下にある`Commit changes`でコミットする

＊ファイル名を入力する際、スラッシュ`/`で区切ると下の階層のディレクトリに移動できる

![](./_img/00002.png)

## その他

### 設定ファイル

VSCodeで編集する際に`Prettier`をインストールしていると、マークダウンを記述する際に日本語の後に半角スペースが入ってしまう問題があるため、`.vscode`フォルダ内の`settings.json`でフォーマットを無効にしています。
何か解決できる良い方法があればPR等でお知らせください。
