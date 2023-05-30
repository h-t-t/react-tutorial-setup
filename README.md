# react-tutorial-setup

```bash
# WSL環境にnode.jsをインストール
curl -fsSL https://raw.githubusercontent.com/tj/n/master/bin/n | sudo bash -s lts

# pnpm(高速版npm)インストール
sudo npm install -g pnpm

# Reactプロジェクトの新規作成(npmのcreate-react-appを使う)
pnpm dlx create-react-app react_form_study

# Reactプロジェクトの開発用Webサーバ起動
cd react_form_study
pnpm start
```
