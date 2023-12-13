[Hocdidungluoi AI blog writing structure](https://hocdidungluoiai.github.io)
====================================

> I never expect this becomes popular.

![](https://hocdidungluoiai.space/resources/company/images/bg-wellcome.jpg)


Posts are simply just Markdown files in the _posts/. Metadata of posts are listed in a YAML style front-matter.

For instance, [JS in 20yrs](https://hocdidungluoiai.github.io/2021/04/10/js-20yrs-preface/) has the front-matter of this:

```yml
---
layout:     post
title:      "JS in 20yrs"
subtitle:   " \"Hello World, Hello Blog\""
date:       2023-01-29 12:00:00
author:     "Admin"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Life
    - Meta
---
```
> Note: `tags` section can also be written as `tags: [Life, Meta]`.

After [Rake](https://github.com/ruby/rake) is introduced, we can use the command below to simplify the post creation:

```
rake post title="Hello 2015" subtitle="Hello World, Hello Blog"
```

This command will automatially generate a sample post similar as above under the `_posts/` folder.

There are a bunch of _advanced_ configs:

1. a _text style_ header like [this](https://huangxuan.me/2019/09/08/spacemacs-workflow/) with

```yml
header-style: text 
```

2. Turning on Latex support:

```yml
mathjax: true
```

3. Adding a mask to the header picture:

```yml
header-mask: 0.3
```

Etc.


### SideBar

![](http://huangxuan.me/img/blog-sidebar.jpg)

**SideBar** provides possible modules to show off more personal information.

```yml
# Sidebar settings
sidebar: true   # default true
sidebar-about-description: "your description here"
sidebar-avatar: /img/avatar-hux.jpg     # use absolute URL.
```

Modules *[Featured Tags](#featured-tags)*, *[Mini About Me](#mini-about-me)* turned on by default and you can add your own. The sidebar is naturally responsive, i.e. be pushed to bottom in a smaller screen (`<= 992px`, according to [Bootstarp Grid System](http://getbootstrap.com/css/#grid))  

