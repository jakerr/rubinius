---
layout: doc_ja
next: Getting Started
next_url: getting-started
---

## Rubiniusとは？

Rubiniusは[Ruby](http://ruby-lang.org)というプログラミング言語の実装です。

Rubiniusは以下の機能が含まれています

* バイトコードのVM(仮想マシン)
* Rubyのシンタックスのパーサ
* バイトコードのコンパイラ
* 世代別ガベージコレクター
* ジャストインタイム（JIT)ネイティブコードコンパイラ
* Rubyのコアとスタンダードライブラリ

Rubiniusは現在、Ruby バージョン1.8.7を実装しています。


## ライセンス

RubiniusはBSDのライセンスを使用しています。 詳しくはソースのLICENSEというファイルを参考にしてください。


## インストール

Rubiniusは　Mac OS X 様々な Unix/Linux のオペレーティングシステムで実行できます。
Microsoft Windowsのサポートは近々登場予定です。

Rubiniusをインストールするには、次の手順に従ってください。 さらに詳しくは[Getting Started](/doc/ja/getting-started/)を参考にしてください。

1. `git clone git://github.com/evanphx/rubinius.git`
1. `cd rubinius`
1. `./configure --prefix=/path/to/install/dir`
1. `rake install`

インストールが完了したら、画面の指示に従ってRubiniusのプログラムのディレクトリ(bin)をPATHに追加します。

RubiniusにはRubyGemsが最初から含まれています。rake、rdoc、gemsも初期の段階でインストールされています。
例えばnokogiriのgemをインストールするには `rbx gem install nokogiri`と入力します。
