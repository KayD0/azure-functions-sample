## Azure Functions Core Toolsをインストールする
### 用途：ローカル環境でAzure Functionsの開発とテストを行うためのツールセット
- https://learn.microsoft.com/ja-jp/azure/azure-functions/create-first-function-cli-powershell?tabs=windows%2Cazure-cli%2Cbrowser#install-the-azure-functions-core-tools

## Azure CLIをインストールする
### 用途：コマンドラインからAzureリソースを管理するためのツール
- https://learn.microsoft.com/en-us/cli/azure/install-azure-cli

## requirements.txtに記載された依存パッケージをインストールする
### 用途：プロジェクトに必要なPythonパッケージをインストールする
- py -m pip install -r requirements.txt

## Azureへのデプロイ
- az login 
- az account set --subscription "subscription_id"
- func azure functionapp publish hotel-search-test-fnc --publish-local-settings -i --build remote