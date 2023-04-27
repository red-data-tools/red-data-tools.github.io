---
title: none
---

<div class="jumbotron">
  <h1>{{ site.title }}</h1>
  <p>{{ site.description.ja }}</p>
</div>

## Red Data Toolsについて {#about}

Red Data ToolsはRuby用のデータ処理ツールを提供するプロジェクトです。

私たちのポリシーです。

  1. Rubyコミュニティーを超えて協力する

     * 私たちはRubyコミュニティーとも他のコミュニティーとも協力します。たとえば、私たちは多くの言語が共通で使っているApache Arrowを使いますし、Apache Arrowの開発に参加して開発成果を共有します。

  2. 非難することよりも手を動かすことが大事

     * 私たちは現状（RubyよりもPythonの方がたくさんよいツールが揃っているかもしれません）や既存ライブラリーの実装を非難することなどに時間を使うよりも、コードを書いたりテストをしたりドキュメントを書いたり私たちの活動を紹介したり他のプロジェクトにフィードバックをしたりといったことに時間を使います。

  3. 一回だけの活発な活動よりも小さくてもいいので継続的に活動することが大事

     * Rubyでたくさんのデータ処理をできるようになるために私たちはたくさんやることがあるかもしれません。データ処理のためのすばらしいツール群一式を揃えるために継続的に活動する必要があります。そのため、1回だけの活発な活動よりも継続的な活動の方が大事です。

  4. 現時点での知識不足は問題ではない

     * 私たちは高速なツールを実装するために数学や統計学や線形代数学などの知識が必要かもしれません。しかし、このプロジェクトに参加する時点でそれらの知識は必須ではありません。なぜなら活動をしていく中で学んでいくことができるからです。私たちは既存の高速な実装を使ったり、既存の高速な実装から学んだりすることができます。

  5. 部外者からの非難は気にしない

     * 私たちがデータ処理のためのすばらしいツール群一式を揃えるまでに時間がかかるかもしれません。そうなるまでは部外者が私たちの活動を非難するかもしれません。私たちはそれらを気にしません。私たちにはそれらを処理している時間はありません。 :-)

  6. 楽しくやろう！

     * Rubyを使っているんですから！

## コミュニティー {#community}

  * [Gitter上のチャットルーム（英語）][gitter-en]

  * [Gitter上のチャットルーム（日本語）][gitter-ja]

## プロダクト {#products}

アルファベット順：

  * [Arrow packages][arrow-packages]：Debian GNU/Linux、Ubuntu、CentOS向けの[Apache Arrow][apache-arrow]関連のパッケージ。

  * [Charty][charty]: 簡単にデータを可視化できるRubyライブラリー。

  * [GR.rb][gr-rb]: グラフ描画ライブラリ[GR][gr]のRubyバインディング。

  * [Jekyll Jupyter Notebook plugin][jekyll-jupyter-notebook-plugin]：[Jupyter][jupyter] notebookを使うための[Jekyll][jekyll]のプラグイン。

  * [Parquet GLib][parquet-glib]：言語バインディングのための[Apache Parquet C++][apache-parquet-c++]のラッパーライブラリー。

  * [RedAmber][red_amber]: Rubyで書かれたデータフレームライブラリ。[Red Arrow][red-arrow]を利用している。

  * [Red Arrow GSL][red-arrow-gsl]：Red Arrowと[Ruby/GSL][ruby-gsl]間の変換メソッドを提供するRubyライブラリー。

  * [Red Arrow NMatrix][red-arrow-nmatrix]：Red Arrowと[NMatrix][nmatrix]間の変換メソッドを提供するRubyライブラリー。

  * [Red Arrow Numo::NArray][red-arrow-numo-narray]：Red Arrowと[Numo::NArray][numo-narray]間の変換メソッドを提供するライブラリー。

  * [Red Arrow PyCall][red-arrow-pycall]：Red Arrowと[PyCall][pycall]経由での[pyarrow][pyarrow]間の変換メソッドを提供するライブラリー。

  * [Red Arrow][red-arrow]：[Apache Arrow][apache-arrow]のRubyバインディング。

  * [Red Chainer][red-chainer]：Pythonの[Chainer][chainer]をRubyに移植したニューラルネットワーク用のフレキシブルなフレームワーク。

  * [Red Datasets][red-datasets]: 機械学習でよく利用されるオープンなデータセットの例をプロジェクトで利用しやすいように提供するRuby gem。

[apache-arrow]:https://arrow.apache.org/
[apache-parquet-c++]:https://github.com/apache/parquet-cpp
[arrow-packages]:https://github.com/red-data-tools/arrow-packages
[chainer]:https://chainer.org/
[charty]:https://github.com/red-data-tools/charty
[gitter-en]:https://gitter.im/red-data-tools/en
[gitter-ja]:https://gitter.im/red-data-tools/ja
[gr]:https://github.com/sciapp/gr
[gr-rb]:https://github.com/red-data-tools/GR.rb
[jekyll-jupyter-notebook-plugin]:https://github.com/red-data-tools/jekyll-jupyter-notebook
[jekyll]:https://jekyllrb.com/
[jupyter]:https://jupyter.org/
[nmatrix]:https://github.com/SciRuby/nmatrix
[numo-narray]:https://ruby-numo.github.io/narray/
[parquet-glib]:https://github.com/red-data-tools/parquet-glib
[pyarrow]:http://arrow.apache.org/docs/python/
[pycall]:https://github.com/mrkn/pycall
[red_amber]:https://github.com/red-data-tools/red_amber
[red-arrow-gsl]:https://github.com/red-data-tools/red-arrow-gsl
[red-arrow-nmatrix]:https://github.com/red-data-tools/red-arrow-nmatrix
[red-arrow-numo-narray]:https://github.com/red-data-tools/red-arrow-numo-narray
[red-arrow-pycall]:https://github.com/red-data-tools/red-arrow-pycall
[red-arrow]:https://github.com/apache/arrow/tree/master/ruby/red-arrow
[red-chainer]:https://github.com/red-data-tools/red-chainer
[red-datasets]:https://github.com/red-data-tools/red-datasets
[ruby-gsl]:https://github.com/SciRuby/rb-gsl
