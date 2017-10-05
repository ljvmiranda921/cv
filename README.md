# Curriculum Vitae

[![Build Status](https://travis-ci.org/ljvmiranda921/cv.svg?branch=master)](https://travis-ci.org/ljvmiranda921/cv)

This repository contains the CV of Lester James V. Miranda. His list of
publications can be seen in `./publications.bib`. You can view the readable
version of this document by clicking the `./LMiranda.pdf` file.

## Building from source

This document uses the [moderncv](https://github.com/xdanaux/moderncv)
package. It is possible to build from source by performing the following
commands in succession:

```bash
$ pdflatex -synctex=1 -interaction=nonstopmode -file-line-error LMiranda.tex
$ bibtex LMiranda.tex
$ pdflatex -synctex=1 -interaction=nonstopmode -file-line-error LMiranda.tex
$ pdflatex -synctex=1 -interaction=nonstopmode -file-line-error LMiranda.tex
```

## Contact

- __Email__: ljvmiranda@gmail.com
- __Linkedin__: [lesterjamesmiranda](https://www.linkedin.com/in/lesterjamesmiranda/)
