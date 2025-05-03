# ステージング

git add file1 file2

# ローカルにコミット

git commit -m "ここにメッセージ"

# クラウドにプッシュ

git push origin main

# クラウドから取得

git pull

# リモートリポジトリとの接続

名前を main に変更する（デフォルトが master）
git branch -M main

接続
git remote add origin git@github.com:r77tchan/name

# ステージングされていないものの差分

git diff

# ステージング解除

git restore --staged <filename>

# 修正をなかったことに

git checkout <filename>

# 用語

origin -> リモートリポジトリのこと
