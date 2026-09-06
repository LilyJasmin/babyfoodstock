離乳食ストック PWA プロトタイプ

このフォルダには、iPhoneのホーム画面に追加して使えるPWA用ファイルが入っています。

内容:
- index.html : アプリ本体
- manifest.webmanifest : PWA設定
- sw.js : オフラインキャッシュ
- icons/ : iPhone/Android用アイコン

公開方法（GitHub Pages）:
1. GitHubで新しいPublicリポジトリを作成
2. このフォルダ内のファイル・フォルダをすべてアップロード
3. Settings > Pages > Deploy from a branch > main / root > Save
4. 表示されたURLをiPhoneのSafariで開く
5. Safariの共有ボタン > 「ホーム画面に追加」 > 「追加」

注意:
- 初回アクセス後は、アプリ本体を端末にキャッシュしてオフラインでも開けるようにしています。
- ストックデータは端末のブラウザ内（localStorage）に保存されます。GitHubには保存されません。
- iPhoneのSafariデータを削除したり端末を変更したりするとデータを失う可能性があります。
