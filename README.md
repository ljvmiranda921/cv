# Curriculum Vitae

[![download PDF](https://img.shields.io/badge/download-PDF-brightgreen.svg)](https://www.dropbox.com/s/kmexsi1zxpa4829/LJMiranda_CV-latest.pdf?dl=0)
[![Build Status](https://travis-ci.org/ljvmiranda921/cv.svg?branch=master)](https://travis-ci.org/ljvmiranda921/cv)

This repository contains the Curriculum Vitae of Lester James V. Miranda. The
compiled PDF is automatically deployed to Dropbox, where you can download from
the link above. To manually build this file, simply run the following command:

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

## Dependencies

This document is dependent on the [TexLive 2015 Distribution](ftp://tug.org/historic/systems/texlive/2015/). You can find the
install sequence in `tlsetup.sh`. It uses the following CTAN packages which
can be installed by typing `tlmgr install package-name`:

- `moderncv`: base package for cv theme and format
- `fontawesome`: for social icons in the header
- `libertine`: for Linux Libertine font family
- `xcolor`: for blue colors in live links

## Contact

- Email: ljvmiranda@gmail.com
- Linkedin: [lesterjamesmiranda](https://www.linkedin.com/in/lesterjamesmiranda/)

