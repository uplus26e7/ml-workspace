# ML Workspace

Python の機械学習向け統合開発環境を docker-compose で用意するテンプレートです。  
[Machine Learning Workspace][1]という機械学習向けの Web ベース IDE を使っています。  
Jupyter Notebook/Lab、GUI Desktop 環境、VS Code、FileBrowser などを Web ブラウザー上で使うことができます。

## Dependency

- Docker version 20.10.5
- docker-compose version 1.29.0

## Setup

`.env.example`を参考に同階層に`.env`ファイルを作成してください。

## Usage

```bash
docker-compose up -d
```

## Preferences

1. [Machine Learning Workspace][1]

[1]: https://github.com/ml-tooling/ml-workspace
