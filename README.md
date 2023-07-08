# dotnet

.NetCore のメモ

## MacBookでdotnetを使う

[公式ドキュメント](https://learn.microsoft.com/ja-jp/dotnet/core/install/macos)の通りにやれば良い。

## dotnetのバージョンを固定する

[global.json](https://learn.microsoft.com/ja-jp/dotnet/core/versions/selection)を書いてユーザーディレクトリに配置しておく。
なお、置く場所についてはCLIを実行するディレクトリではなくその上位のディレクトリから探索するのでそれより上においても良いが
わかりにくさを回避するために、ユーザーディレクトリに置いておく。

### dotnet 7

```json
{
  "sdk": {
    "version": "7.0.302"
  }
}
```

### dotnet 8

```json
{
  "sdk": {
    "version": "8.0.100-preview.5.23303.2"
  }
}
```
