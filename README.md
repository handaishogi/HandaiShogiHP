# HandaiShogiHP

## デプロイ方法
デプロイ（=webpageの作成）には[jekyll](https://docs.github.com/ja/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)を使用している．
デプロイはコミットを`main`ブランチにpushするたびに行われる．

## ディレクトリ構造
```
root/
├── contrib/　　　　　　　　　　　// 引継ぎ資料など
│   ├── commit_screen.png
│   ├── markdown-guide.md // markdownの使い方
│   ├── responsibilities.md // 仕事内容
│   └── handover.md // 引継ぎ方法    
├── docs/　　　　　　　　　　　　// webページ本体
│   ├── _layouts/
│   ├── assets/css/
│   ├── image/                 // 画像ファイルを保存するディレクトリ
│   ├── _config.yml
│   ├── events.md　　　　　　　 // 過去の大会結果
│   ├── index.md               // ホーム
│   └── members.md             // 部員紹介
└── README.md
```


## その他

### コミットメッセージの規則
コミットメッセージの接頭辞には，以下のどれかを付ける．
| 接頭辞 | 内容 | 
| :---   | :--- | 
| `feat` | 既存のファイルに新しいコンテンツを追加する |
| `fix`  | 既存のファイルの一部を修正する |
| `add`  | 新しいファイルを追加する |
| `docs` | `README.md`などのwebページに関係ない`*.md`を変更する |

（例）feat: add new members of shogi club to members.md
