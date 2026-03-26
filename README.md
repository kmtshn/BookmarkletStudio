🔗 Bookmarklet Studio

ブラウザ上でJavaScriptを書き、即座に最適化・圧縮されたブックマークレットを生成・管理できる「ブックマークレット専用」の開発スタジオです。

🌟 特徴

自動Minify (圧縮): Terser ライブラリを内蔵。コメントの削除やコードの最適化を行い、URL制限に配慮した最小限のサイズに変換します。

ドラッグ&ドロップ・インストール: 生成されたボタンをブックマークバーにドラッグするだけで、インストールが完了します。

マイリスト機能: 作成したブックマークレットをブラウザの LocalStorage に保存。後から編集や再利用が可能です。

インポート/エクスポート: 保存したデータをJSON形式でバックアップ、または別のブラウザに移行できます。

便利なプリセット: - 📸 要素スクショツール: 指定した要素を画像として保存

📝 Markdownリンクコピー: タイトルとURLを即座に取得

👁️ パスワード表示: *** 伏せ字を一時的に可視化

🚀 使い方

コードを入力: エディタにツール名、説明、JavaScriptコードを入力します。

自動変換: 入力と同時にコードが圧縮され、javascript: 形式のブックマークレットURLが生成されます。

インストール: プレビューエリアのボタンをブックマークバーにドラッグ＆ドロップします。

保存: 「リストに保存」を押すと、いつでもこのスタジオで再編集できるようになります。

🛠️ 技術スタック

Styling: Tailwind CSS

Core Engine: Terser (JavaScript Minifier)

Typography: LINE Seed JP / YakuHanJP

Storage: Browser LocalStorage API

📦 インストール / 開発

このプロジェクトは単一のHTMLファイルで完結しているため、サーバー構築は不要です。

# リポジトリをクローン
git clone [https://github.com/your-username/bookmarklet-studio.git](https://github.com/your-username/bookmarklet-studio.git)

# index.html をブラウザで開くだけ
open index.html


⚠️ 注意事項

一部のWebサイトでは、Content Security Policy (CSP) の制限により、ブックマークレットからの外部スクリプト読み込みがブロックされる場合があります。

実行するコードの安全性には十分注意してください。

📄 ライセンス

MIT License. 自由に変更・配布が可能です。
