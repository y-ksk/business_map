# シナジーマップ（俯瞰）— Vercel 手動デプロイ用
このフォルダを **そのまま** Vercel の「Manual Deploy（ドラッグ＆ドロップ）**」でアップロードすると、公開URLが発行されます。

## 手順（非エンジニア向け）
1. https://vercel.com にログイン（GitHubでOK）
2. 「Add New」→「Project」→ 右上の「**Deploy from... → Drag and Drop**」を選択
3. このフォルダ（`synergy-map-static`）を**まるごと**ドラッグ＆ドロップ
4. 数十秒でURLが出ます（例: `https://synergy-map.vercel.app`）
5. Notionで `/embed` → 上記URLを貼り付け

※ このサイトは **1ファイル（index.html）** だけの静的ページです。更新したい時は、同じ手順で新しいフォルダを再アップロードすればOK（URLは変わるので、Notionの差し替えが必要です）。URLを固定にしたい場合は、GitHub連携の自動デプロイ方式に切り替えてください。
