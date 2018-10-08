[![Build Status](https://travis-ci.org/ncoghlan/walkdir.svg?branch=master)](https://travis-ci.org/ncoghlan/walkdir)
[![codecov](https://codecov.io/gh/ncoghlan/walkdir/branch/master/graph/badge.svg)](https://codecov.io/gh/ncoghlan/walkdir)
[![image](https://img.shields.io/github/contributors/ncoghlan/walkdir.svg)](https://github.com/ncoghlan/walkdir/graphs/contributors)

Overview
========

walkdir is a simple set of iterator tools intended to make it
easy to manipulate and filter the output of os.walk() in a way
that is also easily applicable to any source iterator that
produces data in the same format.

It offers tools such as:

- glob-style filtering for file and directory names
- depth limiting for directory recursion
- flattening of output into simple sequences of path names
- detection of symlink loops when following symlinks

Full documenation avaliable at http://walkdir.readthedocs.io


Maintainer History
------------------

* Maintained by @palaviv since June 2018
* Originally created by @ncoghlan in November 2011
