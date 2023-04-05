# win-setup
for set up windows by chocolatey

# 手順
## chocolatey install
[https://chocolatey.org/install](https://chocolatey.org/install) にアクセスし、インストールコマンドをコピーする。
ただしChoose How to Install Chocolatey は基本的に「Individual」でよい

## packageのインストール
本リポジトリに上がっているpackage.configを使えばよい。
管理者権限でpower shell を開き、package.configがあるディレクトリ下で以下を実行.

```
choco install package.config 
```

## 補足
[https://community.chocolatey.org/packages](https://community.chocolatey.org/packages)
で必要なパッケージは検索できる
