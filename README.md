# Azure Functions を使用した音声変換及び文字起こし

ffmpeg を使用した音声ファイルの変換と、Microsoft Cognitive Services Speech Service を使用した文字起こしが利用できます

* **Mp3ToWav**: 関数名は Mp3ToWav となっておりますが、このフォークでは ffmpeg で対応可能な音声ファイルから Speech Services で利用可能な wav ファイル形式に変換します。変換パラメータを変更することも可能です。
* **WavToText**: SDK を使用した Speech Services による音声文字起こしを行います。

## Azure に簡単デプロイ

[![Deploy to Azure](http://azuredeploy.net/deploybutton.svg)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2F0GiS0%2Faudio-azure-functions%2Fmaster%2Fazure.deploy.json)

## デプロイ後の設定変更

- 監視対象コンテナ名を変更するにはソースの変更が必要です
- ローカルでのテスト時には BLOB の接続文字列などを設定する local.settings.json ファイルをが別途必要です
- デプロイ後はソース管理が有効になっている（KUDU含め）ため、必要に応じて変更してください
- デフォルトの設定では ffmpeg は 32bit のみ利用可能です。64bit 化する場合には別途実行環境の変更が必要です

## オリジナルソースの情報

元の作者の方 (GiS) によるブログ記事は [こちら](https://www.returngis.net/2018/11/azure-functions-para-procesar-mp3s-con-speech-service/) をご覧ください。
元のリポジトリは [こちら](https://github.com/0GiS0/audio-azure-functions) になります。
