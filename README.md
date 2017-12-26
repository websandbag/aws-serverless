# aws-serverless
AWSでサーバーレスを構築するための構成ファイル

## 構成（予定）

## 準備
- 開発環境でAWSCLIが使える状態
- AMIでS3バケットの作成が許可されている事

## コマンド
### スタック作成
``` bash
$ cd (プロジェクトフォルダ)
$ aws cloudformation create-stack \
    --stack-name myteststack \
    --template-body file://cloudformation.json

```
