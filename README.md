# Blog Coding Guide

> Coding a basic blog from static html to WordPress

[View Web Version](https://steven-klein.github.io/blog-guide/)

## Development

Ensure you have git, [node.js, and npm](https://nodejs.org/en/) installed on your development machine.

``` sh
# clone
$ git clone git@github.com:steven-klein/blog-guide.git blog-guide

# change to root of project
$ cd blog-guide

# install dependencies
$ npm install

# development with live preview
$ npm run docs
```

## Release and Update Public Documentation

Ensure that [Calibre Library](https://calibre-ebook.com/download) is installed on your system and [ebook-convert](https://toolchain.gitbook.com/ebook.html) is in your $PATH.

```sh
$ npm run release
```
