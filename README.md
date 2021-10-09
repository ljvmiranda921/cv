# Curriculum Vitae

[![download PDF](https://img.shields.io/badge/download-PDF-brightgreen.svg)](https://www.dropbox.com/s/kmexsi1zxpa4829/LJMiranda_CV-latest.pdf?dl=0)
[![Build Status](https://travis-ci.org/ljvmiranda921/cv.svg?branch=master)](https://travis-ci.org/ljvmiranda921/cv)
[![GitHub license](https://img.shields.io/github/license/ljvmiranda921/cv.svg)](https://github.com/ljvmiranda921/cv/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/ljvmiranda921/cv.svg)](https://github.com/ljvmiranda921/cv/releases)

This repository contains the Curriculum Vitae of Lester James V. Miranda. The
compiled PDF is automatically deployed to Dropbox, where you can download from
the link above.

My cv is being compiled using a LaTeX Docker container from
[blang/latex](https://hub.docker.com/r/blang/latex/). To manually build this
file, simply download the command wrapper and compile via
[latexmk](http://mg.readthedocs.io/latexmk.html).

First, clone this repository and download the command wrapper:

```shell
$ git clone https://github.com/ljvmiranda921/cv.git
$ wget https://raw.githubusercontent.com/blang/latex-docker/master/latexdockercmd.sh
$ chmod +x latexdockercmd.sh
```
Then, compile via `latexmk`:

```shell
$ ./latexdockercmd.sh latexmk -pdf -outdir=./_build
```

This will build the file in a directory called `_build`.

## Contact

- Email: ljvmiranda@gmail.com
- Linkedin: [lesterjamesmiranda](https://www.linkedin.com/in/lesterjamesmiranda/)

