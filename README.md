# Sandbox

このリポジトリには、Unity WebGL のビルド成果物（`Build/`）が含まれています。

## ディレクトリ構成（抜粋）
- `Build/index.html`
- `Build/Build/Build.data`
- `Build/Build/Build.framework.js`
- `Build/Build/Build.loader.js`
- `Build/Build/Build.wasm`
- `Build/TemplateData/`（ローディング表示などの静的アセット）

## ローカルでの確認方法
> `file://` 直開きでは、ブラウザ設定や圧縮配信の都合で正常に動作しない場合があります。  
> **HTTP サーバー経由**で起動してください。

### 例: Python の簡易サーバーを使う
1. リポジトリルートで以下を実行
   ```bash
   python3 -m http.server 8000
   ```
2. ブラウザで以下を開く
   ```
   http://localhost:8000/Build/
   ```

## 注意
- このリポジトリはビルド済み成果物を保持する用途を想定しています。
- Unity プロジェクト本体（`Assets/` など）は含まれていません。
