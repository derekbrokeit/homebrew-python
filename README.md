# Overview

This repository contains formulae for [Homebrew](http://mxcl.github.com/homebrew/) with a special focus on **Python** libraries not yet well supported by `pip install x` due to compilation and dependency issues.


## Formulae you find here


* Numpy
    - using *suite-sparse* for fast sparse matrices (amd,umfpack)
    - optionally link against the fast *openBLAS* (--with-openblas)
* SciPy
    - optionally link against the fast *openBLAS* (--with-openblas)
* PIL (The *Python Image Library* in the newer distribution named "pillow", so `brew install pillow`)
    - Support for zlib/PNG
    - Based on the fast(er) *graphicsmagick* (imagemagick compatible)
    - *Freetype2* support
    - *Little-CMS* (for color management)
* _Open an issue if your favorite is missing_


## Install

 * `brew tap samueljohn/python`
 * `brew install scipy`
 * `brew test scipy --verbose`
