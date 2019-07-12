---
layout: post
title: TIL - Configuring your jekyll site
#permalink: /til/configuring-your-jekyll-site/
categories: til
---
Some of the rule should be noted here:

> [Configuring jekyll for user and project github pages](http://downtothewire.io/2015/08/15/configuring-jekyll-for-user-and-project-github-pages/)

### Some issue iam having with:
- Wrong setting between User Page and Project page
- When click on post, it's show wrong index
- Baseurl issue, must use baseurl

### Checklist for User site
- [x] `baseurl` must be empty
- [x] `href="\{\{ site.baseurl \}\}\{\{ post.url \}\}` no / between baseurl and posturl
- [x] Always start links with `\{\{ site.baseurl \}\}`
- [x] Always use a trailing after `\{\{ site.baseurl \}\}` => Fix link to resources
