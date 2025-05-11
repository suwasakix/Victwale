# Victwale

自作基板用 KiCAD ライブラリ

KiCAD symbol & footprint library for my own board

&nbsp;

## 目次 - Contents

 - [このソフトウェアについて](#このソフトウェアについて---about-this-software)
 - [ソフトウェアのダウンロード](#ソフトウェアのダウンロード---download-software)
 - [インストール方法](#インストール方法---how-to-install)
 - [動作環境](#動作環境---operating-environment)
 - [ライセンスについて](#ライセンスについて---license)

&nbsp;

## このソフトウェアについて - About this software

このソフトウェアは、オープンソースのプリント基板設計ツールである [KiCAD](https://www.kicad.org) で使用可能なシンボルとフットプリントで構成されたライブラリです。  

本ライブラリは、公開した自作基板で使用しているシンボルとフットプリントをまとめたものであり、基板の改変をサポートするために公開するものです。  

TThis software is a library of symbols and footprints that can be used with KiCAD, an open source PCB design tool.  

This library is a collection of symbols and footprints used in the my own boards, and is useful for modifying these boards.  

KiCAD で PCB を作成する際に KiCAD 付属のライブラリを使用していると、KiCAD 本体をバージョンアップした後で PCB のシンボルやフットプリントを更新しようとすると問題が起きることがあります。そのため、私は自作の基板を作成する際にはライブラリを別途作成して、PCB で使用するシンボルやフットプリントをそのライブラリに保存しています。そのライブラリが、このリポジトリで公開しているものです。  

本ライブラリに含まれる部品の多くは、KiCAD 付属のライブラリに含まれていたものを移植したものです。その一方で、フットプリントについては部品の実装しやすさを考慮してスルーホールやランドを大きめに改変しています。また、機構部品については類似品も取り付けができるように穴の大きさや位置を調整しているものがあります。  

&nbsp;

## ソフトウェアのダウンロード - Download software

こちらのページから最新のバージョンをダウンロードしてください。  

ダウンロードするファイルは「Source code (zip)」または「Source code (tar.gz)」のどちらでも構いませんが、Windows では zip の方が扱いやすいと思います。  

&emsp; https://www.github.com/suwasakix/Victwale/releases

&nbsp;

## インストール方法 - How to install

以下の内容は Windows 環境の説明です。  

ダウンロードしたファイルを解凍したものに含まれている footprints と symbols のフォルダを、ユーザーの ドキュメント\KiCad\<バージョン番号> の場所にフォルダごとコピーしてください。  

KiCAD のシンボル エディターを開き、メニューの「ファイル」→「ライブラリを追加...」を選択して、上記 symbols フォルダの中にある Victwale.kicad_sym を開いてください。  

KiCAD のフットプリント エディターを開き、メニューの「ファイル」→「ライブラリを追加...」を選択して、上記 footprints フォルダの中にある Victwale.pretty を開いてください。  

&nbsp;

## 動作環境 - Operating environment

本ライブラリは、以下の環境で動作することを確認しています。  

- KiCAD 9.0 on Windows 11

&nbsp;

## ライセンスについて - License

本ライブラリのライセンスは、[KiCAD のライブラリライセンス条項](https://www.kicad.org/libraries/license/) に従い、以下の例外条項を伴う [Creative Commons CC-BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/legalcode) とします。  

> To the extent that the creation of electronic designs that use 'Licensed Material' can be considered to be 'Adapted Material', then the copyright holder waives article 3 of the license with respect to these designs and any generated files which use data provided as part of the 'Licensed Material'.

- 本ライブラリを使用した作品（プリント基板、およびそのデータ）のライセンスは、その作者が自由に決めることができます。CC-BY-SA 4.0 License でライセンスする必要はありません。
- 本ライブラリの一部、あるいは改変物を配布する場合、そのライセンスは CC-BY-SA 4.0 License に基づいたものでなければなりません。

