[ETC RedTeam](https://etc-redteam.github.io)
================================

> I never expect this becomes popular.

![](https://etc.vn/resources/company/images/bg-wellcome.jpg)


Posts are simply just Markdown files in the _posts/. Metadata of posts are listed in a YAML style front-matter.

For instance, [JS in 20yrs])(https://etc-redteam.github.io/2021/04/10/js-20yrs-preface/) has the front-matter of this:

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
Note: tags section can also be written as tags: [Life, Meta].

After Rake is introduced, we can use the command below to simplify the post creation:

rake post title="Hello 2015" subtitle="Hello World, Hello Blog"
This command will automatially generate a sample post similar as above under the _posts/ folder.

There are a bunch of advanced configs:

a text style header like this with
header-style: text 
Turning on Latex support:
mathjax: true
Adding a mask to the header picture:
header-mask: 0.3
Etc.

SideBar


SideBar provides possible modules to show off more personal information.

# Sidebar settings
sidebar: true   # default true
sidebar-about-description: "your description here"
sidebar-avatar: /img/avatar-hux.jpg     # use absolute URL.
Modules Featured Tags, Mini About Me turned on by default and you can add your own. The sidebar is naturally responsive, i.e. be pushed to bottom in a smaller screen (<= 992px, according to Bootstarp Grid System)
