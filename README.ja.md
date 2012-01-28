# Eclipse Android Library Project of JSONIC 1.2.9 for Android 1.6 or later.

JSONICをADT (Android Development Tools)を導入したEclipseで使うために、Project Libraryとして再構成しました。
また1.6に対応するため、JSONICのコードからisEmpty()を使わないように修正しています。

保証はありませんが、御自由にご利用下さい。

オリジナルは Hidekatsu Izuno さんによって作成されています。
http://jsonic.sourceforge.jp

使い方については上記、オリジナルJSONICのページを参照してください。

オリジナルのコードに機能を追加しているわけではないので、判り易くするためにJSONICの名前を残していますが
質問などは上記サイト、作者に送らないでください。

## 使い方
1. $ git clone -b release_1.2.9 git://github.com/YasuhiroABE/jsonic4android.git
2. Eclipseのメニューで、 "Import ..." を選択します。
3. 次に "Existing Projects into Workspace." を選択します。
4. gitコマンドを実行してできた、jsonic4androidディレクトリを指定し、"Finish"ボタンを押します。
5. ここまでの操作が終ったら、あなたが作成しているAndroid ProjectのPropertiesの"Android"ページの下にある"Library"にある"Add"ボタンを押してjsonic4androidを追加します。

## 動作環境
このProjectは、Eclipse 3.6 (Windows, Linux)でテストしています。

## コンタクト情報
質問などは yasu@yasundial.org に送ってください。

## 謝辞
JSONライブラリ JSONIC は Hidekatsu Izuno さんにより開発されています。

## ライセンス
ライセンスはオリジナルに準じます。
この配布物はJSONIC 1.2.9のソースコードを使用し、このライセンスは Apache License,Version 2.0 です。

私が作成したコードは同様にApache License, Version 2.0により、下記の通りライセンスします。

     Copyright (C) 2011-2012 Yasuhiro ABE <yasu@yasundial.org>
     
     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.

______
