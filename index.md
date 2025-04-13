---
title: none
---

<div class="jumbotron">
  <h1>{{ site.title }}</h1>
  <p>{{ site.description.en }}</p>
</div>

## About Red Data Tools {#about}

Red Data Tools is a project that provides data processing tools for Ruby.

Our policies:

  1. Collaborate across the Ruby community

     * We collaborate with the Ruby community and other communities. For example, we use Apache Arrow, shared with many languages, and join in development of Apache Arrow to share benefits.

  2. Acting rather than blaming

     * We spend our time writing code, writing tests, writing documentation, introducing our work to others, giving feedback to other projects and so on--rather than blaming the current situation (Python may have many more good tools than Ruby), blaming some current library implementations and so on.

  3. Continuous, iterative progress rather than a short, big project

     * We may need a diverse set of components to do many data processing tasks with Ruby. We need to work continuously to achieve complete tools for data processing. So steady progress is more important than a short sprint for us.

  4. The current lack of knowledge doesn't matter

     * We may also need knowledge about mathematics, statistics, linear algebra and other areas to implement fast tools. But we don't require them when someone joins us. We can learn about them while we work. We can use existing fast implementations and learn from existing fast implementations.

  5. Ignore criticism from outsiders

     * We may take a long time to achieve a complete set of tools for data processing. Some outsiders may criticize us until that time. We should ignore the blame. We don't have time to worry about them. :-)

  6. Fun!

     * Because we use Ruby!

## Community {#community}

  * [Chat room on Matrix (English)][matrix-en]

  * [Chat room on Matrix (Japanese)][matrix-ja]

## Products {#products}

In alphabetical order:

  * [Arrow packages][arrow-packages]: [Apache Arrow][apache-arrow] related packages for Debian GNU/Linux, Ubuntu and CentOS.

  * [Charty][charty]: Ruby library for visualizing your data in a simple way.

  * [GR.rb][gr-rb]: Ruby bindings for the [GR][gr] plotting library.

  * [Jekyll Jupyter Notebook plugin][jekyll-jupyter-notebook-plugin]: [Jekyll][jekyll] plugin to use [Jupyter][jupyter] notebook.

  * [Parquet GLib][parquet-glib]: Wrapper library for [Apache Parquet C++][apache-parquet-c++] for language bindings.

  * [RedAmber][red_amber]: A data frame library in Ruby built on [Red Arrow][red-arrow].

  * [Red Arrow GSL][red-arrow-gsl]: Ruby library that provides conversion methods between Red Arrow and [Ruby/GSL][ruby-gsl].

  * [Red Arrow NMatrix][red-arrow-nmatrix]: Ruby library that provides conversion methods between Red Arrow and [NMatrix][nmatrix].

  * [Red Arrow Numo::NArray][red-arrow-numo-narray]: Ruby library that provides conversion methods between Red Arrow and [Numo::NArray][numo-narray].

  * [Red Arrow PyCall][red-arrow-pycall]: Ruby library that provides conversion methods between Red Arrow and [pyarrow][pyarrow] in [PyCall][pycall].

  * [Red Arrow][red-arrow]: Ruby bindings of [Apache Arrow][apache-arrow].

  * [Red Chainer][red-chainer]: A flexible framework for neural network which ported Python's [Chainer][chainer] with Ruby.

  * [Red Datasets][red-datasets]: Example open datasets commonly used for machine learning collected in a Ruby gem for easy use in projects.

[apache-arrow]:https://arrow.apache.org/
[apache-parquet-c++]:https://github.com/apache/parquet-cpp
[arrow-packages]:https://github.com/red-data-tools/arrow-packages
[chainer]:https://chainer.org/
[charty]:https://github.com/red-data-tools/charty
[gr-rb]:https://github.com/red-data-tools/GR.rb
[gr]:https://github.com/sciapp/gr
[jekyll-jupyter-notebook-plugin]:https://github.com/red-data-tools/jekyll-jupyter-notebook
[jekyll]:https://jekyllrb.com/
[jupyter]:https://jupyter.org/
[matrix-en]:https://app.element.io/#/room/#red-data-tools-en:matrix.org
[matrix-ja]:https://app.element.io/#/room/#red-data-tools-ja:matrix.org
[nmatrix]:https://github.com/SciRuby/nmatrix
[numo-narray]:https://ruby-numo.github.io/narray/
[parquet-glib]:https://github.com/red-data-tools/parquet-glib
[pyarrow]:http://arrow.apache.org/docs/python/
[pycall]:https://github.com/mrkn/pycall
[red-arrow-gsl]:https://github.com/red-data-tools/red-arrow-gsl
[red-arrow-nmatrix]:https://github.com/red-data-tools/red-arrow-nmatrix
[red-arrow-numo-narray]:https://github.com/red-data-tools/red-arrow-numo-narray
[red-arrow-pycall]:https://github.com/red-data-tools/red-arrow-pycall
[red-arrow]:https://github.com/apache/arrow/tree/master/ruby/red-arrow
[red-chainer]:https://github.com/red-data-tools/red-chainer
[red-datasets]:https://github.com/red-data-tools/red-datasets
[red_amber]:https://github.com/red-data-tools/red_amber
[ruby-gsl]:https://github.com/SciRuby/rb-gsl
