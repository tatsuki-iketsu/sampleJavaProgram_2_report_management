# Javaプログラムサンプル2:成績管理アプリ
Javaのサンプルプログラム:コンソール上で動作する成績管理アプリです。
JavaプログラミングのファイルI/Oやメソッドの学習として作成しました。

## プログラムの概要
コンソール上で動作する、生徒の名前と2教科のテスト点数を入力するアプリ

### プログラムの仕様条件
* テストの教科追加や複数回入力はしない想定
* 生徒の名前は名字のみ、IDで管理するので重複してもよい
* 入力項目は名前、組、英語(点数)、数学(点数)
* IDは自動的に設定され、最後のID+1となる
* メニューは一覧、検索、追加、修正、削除、保存(終了)
* 検索時は名前で完全一致、重複がある場合は全て表示
* 追加入力時に空欄があるとエラーになる
* 修正時の入力時はid?:と表示され、入力時空欄にした部分は修正されない
* 削除時の入力時はid:と表示され、削除前に再確認が必要
* 数字入力を求める部分で文字入力はしない想定

## 開発時状況
職業訓練授業で下記を学習し終えた時期に作成
* Javaのループ、ifやSwitch分岐、メソッド、クラス
* インポート
* try、catch 
* ファイルI/O

## ファイル構成
* Exec.java:アプリの実行クラス
* Input.java :ユーザー入力に関連したクラス
* ReportData.java:生徒名、成績のデータクラス

## プログラムプレビュー
![report_management_preview](https://user-images.githubusercontent.com/99540305/216822438-2b039455-ba8e-40bc-9747-80a48e7ef2de.gif)

## 将来的なメンテナンスや追加など
htmlやjspにてレイアウトを設定、ボタンクリックで動作するなどGUIコーティングを予定

## 更新履歴
* 2023-02-05　大まかなプログラム説明を追加、ファイルアップロード
