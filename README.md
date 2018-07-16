# 0xbu.github.io

Latest version of the 0xBU website. Migrated from original self hosted Ghost blog. 
Feel free to add posts on your hacks in the `_posts/` folder. 
Feel free to make any styling changes!

## Installing jekyll on Ubuntu

```
sudo apt-get install ruby ruby-dev build-essential
sudo gem install jekyll bundler
sudo apt-get install zlib1g-dev
sudo gem install jekyll-sitemap jekyll-paginate jemoji --verbose
```

### Run locally

```
jekyll serve
```

Visit [http://127.0.0.1:4000](http://127.0.0.1:4000) to see the site.

## Adding new posts to the site

It is really easy to add new blog posts. We should update it often because there is so much historical value by keeping track of what we've done!

```
cd _posts/
```

Create a file like `2012-03-22-buildsbot-12-ounce.md` with the `YYYY-MM-DD-name.md` format.

```
touch 2012-03-22-buildsbot-12-ounce.md
```

### Header

Add a Header like this. Tags can be anything, but you should use the ones that already exist like `projects`.

```
---
layout: post_layout
title: 5 Steps to Get Started Hacking and CTFing
date: '2016-09-14 06:08:51'
---

Start writing.
```

You can see examples of the existing ones in `_posts/`.

## Licensing

MIT

## Acknowledgments
Based off of [BUILDS-.github.io](https://github.com/BUILDS-/BUILDS-.github.io/blob/master/README.md) and 
[liungkejin.github.io](https://github.com/liungkejin/liungkejin.github.io)
