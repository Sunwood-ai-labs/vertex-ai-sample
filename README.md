<p align="center">
  <img src="./assets/header.svg" alt="Vertex AI Sample Header">
</p>

# 🤖 Vertex AI サンプルプロジェクト

このリポジトリは、Google Cloud の Vertex AI との疎通確認を行うためのサンプルプロジェクトです。

## 📋 機能

- ✅ Vertex AI との接続確認
- 🔑 環境変数を使用したプロジェクト設定
- 📊 利用可能なモデルの一覧取得

## 🚀 セットアップ

### 前提条件

- Python 3.8以上
- Google Cloud アカウントとプロジェクト
- Google Cloud CLIのインストールと認証済み

### 📥 インストール

1. リポジトリのクローン:
```bash
git clone https://github.com/yourusername/vertex-ai-sample.git
cd vertex-ai-sample
```

2. 依存パッケージのインストール:
```bash
pip install -r requirements.txt
```

3. 環境変数の設定:
`.env`ファイルを作成し、以下の内容を設定:
```env
GOOGLE_CLOUD_PROJECT=your-project-id
GOOGLE_CLOUD_REGION=your-region
```

## 💻 使用方法

スクリプトを実行して、Vertex AIとの接続を確認:

```bash
python src/main.py
```

## 🔍 出力例

正常に接続された場合:
```
✅ 接続成功！
📁 プロジェクト: your-project-id
🌏 リージョン: your-region
```

## 🛠️ 開発環境

- Python 3.8+
- google-cloud-aiplatform
- python-dotenv

## 📝 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

## 👥 コントリビューション

バグ報告や機能改善の提案は、GitHubのIssueやPull Requestsを通じて受け付けています。

## ⚠️ 注意事項

- Google Cloud の認証情報が適切に設定されていることを確認してください
- プロジェクトIDとリージョンは実際の環境に合わせて変更してください
