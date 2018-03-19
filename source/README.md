
## Introduction



This repo is for deployment only. Click the following links to `Dev Repository` and `Demo Site`.

- [ ] [Dev Repository](https://github.com/xsung/blog-dev/) 
- [x] [Deployed Repository](https://github.com/xu-song/xu-song.github.io/)  deployed by Hexo from `Dev Repository`
- [ ] [Demo Site](http://xusong.vip) host the `Deployed Repository` 



e.g
You can edit the README file in [Dev Repo](https://github.com/xsung/blog-dev/blob/master/source/README.md)

## Hexo Render

该文件未被render，但是能够被页面访问。

This file is not rendered by Hexo, in order to be readable in github markdown.

It can be accessible in `Web Site` by absolute path.


```yml
# _.yml  site_configuration
skip_render:
  - "**/README.md"
  - "*/README.md"
```
