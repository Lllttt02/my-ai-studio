# MY AI STUDIO v0.3

無料の静的PWAです。プロンプト履歴（localStorage）、AIチャット用下書き（localStorage）、最大8枚の縮小画像ギャラリー（IndexedDB）を実装しています。AI推論、画像生成、AI編集、8K生成は含まれません。

## iPhoneから更新する方法
1. ZIPを「ファイル」アプリで解凍。
2. GitHub の `my-ai-studio` リポジトリの Code → Add file → Upload files を開く。
3. 解凍フォルダ**内**の `index.html`、`app.js`、`sw.js`、`manifest.webmanifest`、`icon.svg`、`README.md` の6ファイルを選択。ZIP自体や親フォルダをアップロードしない。
4. `main` ブランチに Commit changes。GitHub Pages のデプロイ成功を待つ。
5. Safariで公開ページを再読み込みし、v0.3表示を確認。ホーム画面アプリに古いキャッシュが残る場合は閉じて開き直す。

## 注意
v0.2から保存形式が変更されているため、v0.2の下書き・ギャラリーが自動移行される保証はありません。大事な文章や画像は事前に別途保存してください。データはブラウザのサイトデータ削除などで失われる可能性があります。外部AIサービスへの自動送信はありません。GitHub Pagesに秘密のAPIキーを置かないでください。
