# Curriculum Vitae

[![download PDF](https://img.shields.io/badge/download-PDF-brightgreen.svg)](https://www.dropbox.com/s/kmexsi1zxpa4829/LJMiranda_CV-latest.pdf?dl=0)
[![Build Status](https://travis-ci.org/ljvmiranda921/cv.svg?branch=master)](https://travis-ci.org/ljvmiranda921/cv)
[![GitHub license](https://img.shields.io/github/license/ljvmiranda921/cv.svg)](https://github.com/ljvmiranda921/cv/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/ljvmiranda921/cv.svg)](https://github.com/ljvmiranda921/cv/releases)

This repository contains the Curriculum Vitae of Lester James V. Miranda. The
compiled PDF is automatically deployed to Dropbox, where you can download from
the link above. To manually build this file, simply clone this repository and
run the following command:

```shell
$ make latex
```
This will build the file in a directory called `_build`. You can change this
directory by passing an argument to the `make` command:

```shell
$ make latex BUILDDIR=new_dir
```
Compilation error happens when using `pdflatex` with the `fontspec` package.
To resolve this, use the `xelatex` compiler. Again, you can set this as an
argument to the `make` command:

```shell
$ make latex COMPILER=xelatex
```

If you are interested to know more about my continuous integration and deployment
workflow, checkout my [blog post](https://ljvmiranda921.github.io/notebook/2018/02/04/continuous-integration-for-latex/).
I wrote about how to integrate LaTeX with Travis-CI to deploy artifacts to Dropbox.

## Dependencies

This document is dependent on the [TexLive 2015 Distribution](ftp://tug.org/historic/systems/texlive/2015/). You can find the
install sequence in `tlsetup.sh`. It uses the following CTAN packages which
can be installed by typing `tlmgr install package-name`:

- [moderncv](https://ctan.org/pkg/moderncv?lang=en): base package for cv theme and format
- [fontawesome](https://ctan.org/pkg/fontawesome?lang=en): for web-related social icons in the header
- [libertine](https://ctan.org/pkg/libertine): for Linux Libertine font family
- [xcolor](https://ctan.org/pkg/xcolor): for blue colors in live links

## Contact

- Email: ljvmiranda@gmail.com
- Linkedin: [lesterjamesmiranda](https://www.linkedin.com/in/lesterjamesmiranda/)

