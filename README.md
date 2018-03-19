## Overview

This repo is for development. Click the following links to `Deployed Repository` and `Web Site`

- [x] [Dev Repository](https://github.com/xsung/blog-dev/) 
- [ ] [Deployed Repository](https://github.com/xu-song/xu-song.github.io/) is deployed by Hexo from `Dev Repository`
- [ ] [Demo Site](http://xusong.vip) hosts the `Deployed Repository` 

## Setup & Deploy


```bash
$ git clone --recursive git@github.com:xsung/blog-dev.git blog
$ npm install hexo --save  # install node_modules dependency
$ hexo s
$ hexo d
```

## Submodule

- [posts](../../../_posts)
- games
  - [2048](../../../2048)
- demos
  - [todo](../../../demos)
- themes
  - [NexT](../../../hexo-theme-next)



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

### Merge with latest submodules (all forked branch)(optional)
**themes**
goto [NexT](../../../hexo-theme-next)

merge with Mater Branch



## third-party-services
- busuanzi
- disqus


## Config


## Miscellaneous
- [TODO List](https://github.com/xsung/blog-dev/issues/1)
- [Setup Blog with Proper Way](http://xusong.vip/2018/01/30/web/blog-framework/nodejs-hexo/Hexo%E4%BD%BF%E7%94%A8%E5%BB%BA%E8%AE%AE/)






