
# Voxel World

ブラウザで遊べる、ブロックを置く・壊すタイプの小さな3Dサンドボックスゲームです。Three.jsをCDNから読み込むため、ビルド手順は不要です。

## GitHub Pagesで公開する

1. GitHubで新しいリポジトリを作成します（例：`voxel-world`）。
2. このフォルダ内の `index.html`、`style.css`、`game.js`、`README.md` をリポジトリの直下にアップロードします。
3. リポジトリの **Settings → Pages** を開きます。
4. **Build and deployment** の Source を **Deploy from a branch** にします。
5. Branch を `main`、フォルダを `/(root)` にして **Save**。
6. 数分待つと `https://あなたのユーザー名.github.io/voxel-world/` で公開されます。

## 操作

- **PC**：WASDで移動、マウスで視点、左クリックで破壊、右クリックで設置、1〜7でブロック選択。
- **iPad / タッチ端末**：左下パッドで移動、画面右側をドラッグして視点変更、画面の「壊す」「置く」「ジャンプ」を使用。
- **保存**：画面右上の「保存」。保存は同じブラウザ内に保存されます。

## 注意

- このプロジェクトはMinecraft公式ゲームではなく、独自の簡易ボクセルゲームです。名称・画像・素材を公式のものとして使用していません。
- Three.jsはjsDelivr CDNから読み込みます。初回起動時はインターネット接続が必要です。
