# Work Time Logger is 何

ボタンを押した時刻とボタンのラベルの組みを JSON 形式で localStorage（ブラウザ内の保存場所）に記録し、保存ボタンでダウンロードするシングル・ページ・アプリケーションです。

## 使い方

1. テキストボックスにラベルを入力します。
2. 「追加」ボタンを押して、項目リストにボタンを表示させます。
3. 必要な作業の種類だけ 2. を繰り返します。
4. 作業開始のタイミングに当該ラベルを押します。  
  localStorage にボタン押下時の時刻が打刻され、画面に追記されます。

## 特殊な操作

1. ×アイコンを押すと、押した×アイコンの行の項目を削除することができます。
2. 「保存」ボタンを押して打刻記録を JSON 形式のファイルでダウンロードします。
3. 「削除」ボタンを押すと、画面に表示されているログと localStorage 内のログが全て削除されます。

## 困った時は

本リポジトリの Issues までお気軽にご連絡ください。