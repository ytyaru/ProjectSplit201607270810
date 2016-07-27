# このソフトウェアについて #

ProjectSplit201607270810は私個人が学習目的で作成したソフトウェアです。

プロジェクトは.libに分割するとファイルサイズが肥大化します。
そこで、.libにせずに分割してプロジェクトにする方法を考えました。

# 開発環境 #

* Windows XP SP3
* C++/Win32
* Visual C++ 2010 Express

# 分割方法 #

* プロジェクトはWindowsアプリケーション1つだけにする
* プロジェクトファイル上でフォルダ作成し、分割する

参照設定もしなくて済むので楽でした。
.libファイルも作成されなくなり、exeファイルだけなので軽いです。

ソースコードは[MultiWindowCreatorClass201607261835](https://github.com/ytyaru/MultiWindowCreatorClass201607261835)と同じです。
プロジェクト構成やディレクトリ構成が違うだけです。

# イメージ #

## プロジェクトディレクトリ構造 ##

![プロジェクトディレクトリ構造](https://cdn-ak.f.st-hatena.com/images/fotolife/y/ytyaru/20160727/20160727170902.png)

## ディレクトリ構造 ##

![ディレクトリ構造](https://cdn-ak.f.st-hatena.com/images/fotolife/y/ytyaru/20160727/20160727170936.png)

## 実行 ##

![完成図](https://cdn-ak.f.st-hatena.com/images/fotolife/y/ytyaru/20160726/20160726213827.png)

# ライセンス #

このソフトウェアはCC0ライセンスです。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
