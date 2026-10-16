# Apex Clipper

配信の録画から、キルの場面だけを自動で抜き出してつなげる Windows のアプリです。

**▶ [最新版のダウンロードページ](../../releases/latest)**

## インストールの手順（画像つき）

下の画面は Windows 11 の Edge です。**赤い枠を、番号の順に押して**いけば進めます。**Chrome の人**は、2 の代わりに「2'. Chrome の場合」を見てください。
推奨：Windows 10 / 11・**NVIDIA GeForce RTX シリーズ**（作者は RTX 4070 Ti で確認）・空き容量 50GB 以上・ネット回線。

⚠ AMD Radeon・内蔵 GPU・グラフィックボードの無い PC は**想定外**です（文字の読み取りを CPU で行うため、とても時間がかかります。一応は動きます）。

### 1. 最新版のページを開いて、setup.exe を選ぶ

<img src="guide/01-assets.png" width="1024" alt="">

[最新版のページ](../../releases/latest) を開き、下の「Assets」にある **①「apex-clipper-(版)-setup.exe」** を押します。ZIP ではなく、こちらです。

### 2. 「一般的にダウンロードされていません」と出たら（Edge）

<img src="guide/02-flyout-dots.png" width="644" alt="">

個人で作った（署名のない）アプリなので、Edge がこの表示を出します。ダウンロードの一覧の項目にマウスを載せると出る **①「…」** を押します（右クリックでも同じメニューが出ます）。

<img src="guide/03-menu-save.png" width="544" alt="">

**①「保存」** を押します。

<img src="guide/04-dialog-chevron.png" width="644" alt="">

確認の窓が出ます。**①「削除」の右の「∨」** を押します。**「削除」の文字そのものは押さないでください**（ファイルが消えます。消えたらもう一度ダウンロード）。

<img src="guide/05-keep.png" width="644" alt="">

**①「保持する」** を押します。

<img src="guide/06-open-file.png" width="644" alt="">

**①「ファイルを開く」** を押します。

### 2'. Chrome の場合（ダウンロードの警告は出ず、開いた時に青い画面）

<img src="guide/07a-chrome-blue.png" width="535" alt="">

「Windows によって PC が保護されました」と出たら、**①「詳細情報」** を押します（「実行しない」は押さない）。

<img src="guide/07b-chrome-run.png" width="535" alt="">

「発行元: 不明な発行元」と出ます（個人で作ったアプリのため）。**①「実行」** を押すと、次の 3 に進みます。

### 3. Windows の確認で「はい」

<img src="guide/07-uac.png" width="490" alt="">

「発行元: 不明」は、個人で作ったアプリのためです。**①「はい」** を押します。

### 4. セットアップを進める

<img src="guide/08-wizard-dest.png" width="615" alt="">

インストール先は変えなくて大丈夫です。**①「次へ」** を押します。次の2ページも「次へ」です。

<img src="guide/09-wizard-ready.png" width="615" alt="">

**①「インストール」** を押します。

<img src="guide/10-installing.png" width="615" alt="">

「1/6」から「6/6」まで進みます。初回は部品のダウンロードで **15〜40分** かかることがあります。途中で失敗したら、同じ setup.exe をもう一度実行するとやり直せます。

### 5. 起動する

<img src="guide/11-finish.png" width="615" alt="">

「Apex Clipperを起動する」にチェックが入ったまま **①「完了」** を押すと起動します。デスクトップに「Apex Clipper」のショートカットができます。

<img src="guide/12-initial-setup.png" width="620" alt="">

アプリの画面が出てから10〜20秒ほどで「はじめの設定」が出ます。最初は何も変えずに **①「この設定で利用開始」** で大丈夫です。使い方の案内は、アプリの右上の歯車 →「基本」→「案内を開く」にあります。

---

この置き場には配布物（ZIP・setup.exe）だけを置いています。ソースは含みません。
画面は、個人の設定やアカウントの無い試験用の Windows で撮ったものです。
