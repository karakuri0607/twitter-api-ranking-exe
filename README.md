# 概要
CSVやスクレイピングから取得した一覧を対象にツイート数の多い順に並び替えし出力します。<br>

# 操作手順
* 「ツイート集計.exe」をダブルクリックしてアプリを起動してください。<br>
* 「検索条件」、「検索方法」、「出力形式」を設定してください。<br>
* 「出力」ボタンをクリックし集計を開始します。<br>

# 各ファイルの説明

## ツイート集計.exe
ツイート集計を行うための実行ファイルです。<br>

## sampleフォルダ
サンプルで使用する目的で設置してあります。<br>
検索方法を設定する際に「read.csv」を選択します。<br>

## chromedriver.exe
Seleniumでスクレイピングする際に使用しています。<br>

## config.ini
設定ファイルです。
特に変更する必要はありません。
* 「CHROME_DRIVER」に「chromedriver.exe」のパスを指定します。<br>
* 「API_TWEET_COUNTS_URL」はツイート集計を行うためのクエリです。<br>
* 「BEARER_TOKEN」はTwitter APIを使用するために必要なトークンです。<br>
* 指定しない場合はシステム標準のトークンを使用します。<br>

