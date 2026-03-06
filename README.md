# 水流 創一朗（そっぴー）Portfolio

AI×SNS集客専門家のポートフォリオサイトです。

🌐 **サイト**: https://YOUR_USERNAME.github.io

---

## 📁 ファイル構成

```
.
├── index.html                  # ポートフォリオ本体
├── README.md                   # このファイル
└── .github/
    └── workflows/
        └── deploy.yml          # 自動デプロイ (GitHub Actions)
```

---

## 🚀 GitHub Pages デプロイ手順

### 1. リポジトリ作成
GitHubで **`あなたのユーザー名.github.io`** という名前のリポジトリを作成

### 2. ファイルをプッシュ
```bash
git clone https://github.com/ユーザー名/ユーザー名.github.io.git
cd ユーザー名.github.io

# このフォルダの全ファイルをコピー
# (.github フォルダも含めて)

git add .
git commit -m "🎉 Initial portfolio deploy"
git push origin main
```

### 3. GitHub Pages を有効化
- **Settings → Pages**
- Source を **`GitHub Actions`** に変更 → Save

### 4. 完了 🎉
数分後に `https://ユーザー名.github.io` で公開されます！

---

## ローカル確認

```bash
python3 -m http.server 8000
# http://localhost:8000 で確認
```
