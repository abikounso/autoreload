= autoreload

* http://www.upp.or.jp

== DESCRIPTION:

  監視対象ディレクトリのファイルが更新（保存）された場合に、Firefoxが自動リロードを行う。

== SYNOPSIS:

Firefoxでの準備
* autoreloadに同梱されているmozlab.xpiをFirefoxにインストールし、【ツール】=>【MozRepl】=>【Start】で、telnetの待ち受けを開始。

使用方法
* ターミナルを起動し、
  autoreload <ディレクトリ名>
  ※ディレクトリ名を省略した場合は、app, publicが監視対象となる。
  ※スクリプト起動時に、Firefox側でtelnetの待ち受けが開始されていないと、エラーが発生してしまうので注意。

== REQUIREMENTS:

* Firefox 3.0.3
* Ruby 1.8.6
※その他の環境では、動作未確認。

== INSTALL:

* sudo gem install abikounso-autoreload

== LICENSE:

(The MIT License)

Copyright (c) 2009 FIX

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
