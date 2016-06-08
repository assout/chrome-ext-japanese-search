# chrome-ext-japanese-search

## 概要 / Overview

Activeにしている間、Google検索結果を日本語のページのみに限定するChrome Extensionです。

Active、非Activeはアイコンをクリックすることで切り替えられます。

### Special thanks

[GitHub - amazedkoumei/chrome-ext-ato-ichinen: Chrome extension adding google search option automatically](https://github.com/amazedkoumei/chrome-ext-ato-ichinen)

## インストール / Install

Chrome Web Storeで公開しています。

https://chrome.google.com/webstore/detail/oiachocgoabholkhlpdpofinnkhfhaeo

デバッグを行う際にはchromeの設定->拡張機能で右上の「デベロッパーモード」チェックボックスをONにしたうえで
 「パッケージ化されていないされていない拡張を読み込む」ボタンでこのパッケージを読み込んでください。

 上記の画面には下記URLからもアクセスできます。

chrome://settings/extensions

Pull Request / Pull Request

テストにはqunit( http://docs.jquery.com/QUnit )を使用しています。

テストの追加・修正 が必要な場合は、test/test.jsを修正のうえ、Pull Requestに含めてください。

### ブラウザを利用してのテスト

ダウンロードしたパッケージをWebサーバのDocumentRootに配置し、chrome-ext-my-hatebu-search-in-google/test/ にアクセスすることでテストを実施できます。

### Grunt を利用してのテスト

    $ cd chrome-ext-japanese-search
    $ npm install -g grunt-cli (既に install 済みの場合は不要)
    $ npm install
    $ grunt test

## ライセンス / License

Copyright &copy; 2012 amazedkoumei
Licensed under the [MIT License][mit]
 
[MIT]: http://www.opensource.org/licenses/mit-license.php
