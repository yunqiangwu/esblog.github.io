## Overview

This repo is for development. Click the following links to `Deployed Repository` and `Web Site`

- [x] [Dev Repository](https://github.com/ESblog/esblog.github.io/tree/dev) 
- [ ] [Deployed Repository](https://github.com/ESblog/esblog.github.io/tree/master) is deployed by Hexo from `Dev Repository`
- [ ] [Demo Site](https://blog.eson.org) hosts site

## Setup & Deploy


```bash
$ git clone -b dev --recursive git@github.com:esblog/esblog.github.io.git blog-dev
$ npm install hexo --save  # install node_modules dependency
$ hexo s
$ hexo d
```

## Submodule

- [posts](../../../_posts)
- themes
  - [NexT](../../../hexo-theme-next)
- [images](../../../raw)


## Contribute

### Push

```bash
# 1. commit changes from all submodules (e.g. _posts)
$ cd _posts
$ commit & push

# 2. commit changes from blog-dev
$ cd blog
$ commit & push

```


### Pull
```bash
# 2. pull latest of all git submodules
$ cd blog
$ git submodule update --recursive --remote
$ git pull --recurse-submodules
# reference https://stackoverflow.com/questions/1030169/easy-way-to-pull-latest-of-all-git-submodules

```

### Update from remote themes (all forked branch)(optional)
**themes**
goto [NexT](../../../hexo-theme-next)

merge with Mater Branch



## third-party-services
- busuanzi
- disqus


## Config


## Miscellaneous
- [TODO List](https://github.com/ESblog/esblog.github.io/issues/2)
- [Setup Blog with Proper Way](https://blog.eson.org/pub/d3c1b8ca/)






