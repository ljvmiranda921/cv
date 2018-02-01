# Curriculum Vitae

[![download PDF](https://img.shields.io/badge/download-PDF-brightgreen.svg)](https://ljvmiranda921.github.io/downloads/LMiranda.pdf)
[![Build Status](https://travis-ci.org/ljvmiranda921/cv.svg?branch=master)](https://travis-ci.org/ljvmiranda921/cv)

This repository contains the Curriculum Vitae of Lester James V. Miranda. To build
this file, simply run the following command:

```shell
$ make latex
```
This will build the file in a directory called `_build`. You can change this directory by passing an argument to
the `make` command:

```shell
$ make latex BUILDDIR=new_dir
```
In some distributions, particularly in trusty, some compilation error happens when using `pdflatex`. In these cases,
use the `xelatex` compiler. Again, you can set this as an argument to the `make` command:

```shell
$ make latex COMPILER=xelatex
```

## Dependencies

This document is dependent on the [TexLive 2015 Distribution](ftp://tug.org/historic/systems/texlive/2015/). You can find the
install sequence in `.travis.yml`. It uses the following CTAN packages which
can be installed by typing `tlmgr install package-name`:

- `moderncv`: base package for cv theme and format
- `fontawesome`: for social icons in the header
- `libertine`: for Linux Libertine font family
- `cjk`: for Japanese characters
- `xcolor`: for blue colors in live links

## Contact

- Email: ljvmiranda@gmail.com
- Linkedin: [lesterjamesmiranda](https://www.linkedin.com/in/lesterjamesmiranda/)

