# 景品ルーレット

初期設定：A賞5％、B賞15％、C賞30％、はずれ50％。
シンプルな画面で、スタートを押すと約4秒で自動停止します。
景品名と確率は画面の「景品・当選確率の設定」から変更できます。
景品枠は4つ。各抽選は独立しており、在庫の減算はありません。
抽選結果と停止位置は一致します。外部ライブラリ・通信・インストールは不要です。

## PCで試す

ZIPを展開し、index.htmlをChromeまたはEdgeで開いてください。

## GitHub Pagesで公開する

1. GitHubにログインします。
2. 右上の「＋」→「New repository」を選択します。
3. Repository nameを「roulette」にし、Publicを選択して「Create repository」を押します。
4. 初期画面の「uploading an existing file」から、ZIP内のindex.htmlをアップロードします。README.mdも任意で追加できます。ZIP自体はアップロードしません。
5. 「Commit changes」で保存します。
6. リポジトリの「Settings」→「Pages」を開きます。
7. 「Build and deployment」の「Source」を「Deploy from a branch」にします。
8. Branchは「main」、フォルダーは「/ (root)」を選んで「Save」を押します。
9. 公開処理が完了するとPages画面にURLが表示されます。そのURLを開いて使用します。

URLの例：https://あなたのユーザー名.github.io/roulette/
設定は端末・ブラウザごとに保存され、他の端末とは共有されません。
公開した画面・コードは誰でも閲覧できます。個人情報は登録しないでください。
