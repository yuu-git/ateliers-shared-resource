# ateliers-shared-resource

ateliers.dev の系のプロジェクト共有リソースです。
サブモジュールとして使用し、各プロジェクトで共有されるデータや設定、画像などを管理します。

## サブモジュール化の手順

### 1. コマンド

現在のプロジェクトディレクトリに `.submodules` というディレクトリを作成し  
その中に `ateliers-shared-resource`  サブモジュールを追加したい場合：

```bash
git submodule add https://github.com/yuu-git/ateliers-shared-resource.git .submodules/ateliers-shared-resource
```

### 2. サブモジュールのブランチについて

基本的に master の使用を推奨します。  
開発中機能の使用は develop ブランチを使用し、試験的機能を試す場合は、新しくブランチを作ります。  
checkout および pull の手順は以下の通りです。

サブモジュールディレクトリに移動後：

```bash
git checkout master
git pull origin master
```

または

サブモジュールディレクトリに移動後：

```bash
git checkout develop
git pull origin develop
```
