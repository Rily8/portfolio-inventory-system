# portfolio-inventory-system
#在庫管理システム(portfolio)
学習記録兼ポートフォリオ用リポジトリです。



## 環境構築メモ ##

### Git初期設定
\`\`\`bash
git config --global user.name "名前"
git config --global user.email "登録メールアドレス"
\`\`\`

### Docker Desktop インストール（Mac / Apple Silicon）

1. Macの種類を確認
   \`\`\`bash
   uname -m
   \`\`\`
   → `arm64` なら Apple Silicon版をダウンロード

2. 公式サイトからダウンロード
   https://www.docker.com/products/docker-desktop/

3. `.dmg`ファイルを実行 → Applicationsフォルダにドラッグ → 起動

4. 初回設定
   - Use recommended settings（Macパスワード入力）
   - 利用目的：Personal
   - （任意）GitHubアカウント連携

5. 動作確認
   \`\`\`bash
   docker --version
   docker run hello-world
   \`\`\`
   → `Hello from Docker!` が出たら成功