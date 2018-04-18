# 環境とか構築手順とか

# firebase hostingのデプロイ先
https://infra-workshop-aa7e9.firebaseapp.com/

# ローカルでの構築・確認方法

## HugoのCLIツールを入れる

### Mac
[Homebrew](https://brew.sh/index_ja)が必要

```sh
brew install hugo
```

### Windows
[Chocolatey](https://www.cresco.co.jp/blog/entry/2127/)が必要

```posh
choco install hugo -confirm
```

### Linux
パッケージマネージャがないので自前でビルドするかバイナリを落としてくるか(Golangが必要)

## Hugoのローカルサイトを起動

```sh
hugo server
```

## Hugoでページ(コンテンツを追加する)

TBD

## HugoでStaticなHTMLを出力するには(必要な場合だけ)

```sh
hugo
```
