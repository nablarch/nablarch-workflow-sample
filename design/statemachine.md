# ステートマシンを実現するサンプルアプリケーション

## サンプルアプリケーションの内容
カード申し込み→自動審査→マニュアル審査の流れを実現する。

[bpmn](camunda/statemachine/new-card_カード発行(ステートマシン)_ver1_20170101.bpmn)

## カード申し込み
メニューより、カード申し込みリンクから、
名前と年収を入力することで、申込みを行う。

## 自動審査
カード申し込み一覧から、自動審査実行リンクをクリックすることで実行される。
年収が100万未満の場合は審査NGとなり、100以上の場合は継続審査となる。

## マニュアル審査
カード申し込み一覧から、審査OK or 審査NGリンクをクリックすることで実行される。
