# HandaiShogiHP

## デプロイ方法
pushするとデプロイされる．

## 引継ぎの仕方
これ以降，以前サイトの管理を行っていた人を**先輩**，サイトの管理を引継ぐ人を**後輩**と呼ぶ．

### GitHubのアカウントを所持していない場合
後輩がGitHubのアカウントを所持していない場合，以下の手順によりアカウントを作成する．
1. [GitHub](https://github.com/)にアクセスする
2. サインアップを行い，アカウントを登録する
3. サインインする

> [!WARNING]
> アカウント作成時に登録したE-mailアドレスは必ず保管しておく．Organizationへの招待に必須となる．

サインインが完了したら，Organizationの招待を行う．

### [Organization](https://github.com/handaishogi)に招待
先輩が後輩を阪大将棋部の[Organization](https://github.com/handaishogi)にinviteする．
1. [Organization](https://github.com/handaishogi)をweb上で開く
2. 画面右側のPeople欄にある`invite someone`ボタンを押す
3. 後輩がGitHubに登録したE-mailアドレスを入力し，`invite`ボタンを押す
4. 後輩のE-mailアドレス宛に阪大将棋部の[Organization](https://github.com/handaishogi)への招待メールが届くので，参加する

> [!NOTE]
> E-mailアドレスはこれ以降保管する必要はない．

## ディレクトリ構造
まだ分からない．`README.md`がホームディレクトリにある都合上，各ページの`*.md`は別のディレクトリにすべて保存しておく必要がありそう．

## その他

### コミットメッセージの規則
コミットメッセージの接頭辞には，以下のどれかを付ける．
| 接頭辞 | 内容 | 
| :---   | :--- | 
| `feat` | 既存のファイルに新しいコンテンツを追加する |
| `fix`  | 既存のファイルの一部を修正する |
| `add`  | 新しいファイルを追加する |
| `docs` | `README.md`などのwebページに関係ない`*.md`を変更する |