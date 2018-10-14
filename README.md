javatool
========
c言語からJNIライブラリを使用したツールです。

## Description ##
### ツールの種類 ###
* dspfields  
  javaクラスのフィールド一覧を表示するプログラム 
  - フィールド名、修飾子、フィールドタイプ
* dspjarfileinfo  
  jarファイルの情報を表示するツールです。
  - ファイル名、最終更新日、最終アクセス日、最終作成日、サイズ、コメント
* dspmethods  
  javaクラスの情報を表示するプログラム
  - 修飾子、パラメータタイプ、リターンタイプ、Exceptionタイプ
* dsppropinfo  
  javaのシステムプロパティ情報を表示するプログラム
  - key、値
* dspScriptEngine  
  javaのスクリプトエンジン情報を表示するプログラム
  - エンジン名、エンジンバージョン、対応言語名、対応言語バージョン
  - 対応拡張子、対応MIME Type、対応ショート名
  

## Demo ##

## VS. ##

## Requirement ##
JDK1.8に依存する

## Usage ##
* dspfields  
  $ dspfields フルクラス名
* dspjarfileinfo  
  $ dspjarfileinfo jarファイル名
* dspmethods  
  $ dspmethods フルクラス名
* dsppropinfo  
  $ dsppropinfo
* dspScriptEngine  
  $ dspScriptEngine
  $ dspScriptEngine2

## install ##
    git clone https://github.com/siranovel/javatool.git  
    cd javatool  
    rpm -ivh <rpmファイル名>  

## Contribution ##

## Licence ##

## Author ##
