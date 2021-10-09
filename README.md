# Curriculum Vitae

[![download PDF](https://img.shields.io/badge/download-PDF-brightgreen.svg)](https://storage.googleapis.com/ljvmiranda/cv.pdf)

My CV uses the [blang/latex Docker image](https://hub.docker.com/r/blang/latex)
to compile the TeX document into PDF.  To compile, first clone this repository
and execute the following command:

```shell
$ git clone https://github.com/ljvmiranda921/cv.git
$ docker run --rm \
             --interactive \
             blang/latex:ubuntu \
             latexmk -pdf -outdir=./_build
```

This will generate the PDF file in the `_build` directory.
