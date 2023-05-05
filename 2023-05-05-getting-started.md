---
layout: post
title:  "Getting Started"
date:   2023-05-05
categories: tools
tags: jekyll ruby
---
To use a non-stock GitHub-hosted Jekyll theme add it as a [remote themes](https://github.blog/2017-11-29-use-any-theme-with-github-pages/). It is as simple as adding the [`jekyll-remote-theme`](https://github.com/benbalter/jekyll-remote-theme) gem and setting the `remote_theme` property in your `_config.yml` file to the GitHub repository that contains the theme you want to use.

Once you've installed a new remote theme, there's still a little bit of tweaking required to get everything working, since different themes rely on different Jekyll plugins and different configuration properties.
Unless the theme is extensively documented in the README, your best bet is to read the `_config.yml` for the theme to see which properties and plugins it uses and update your `_config.yml` and `Gemfile` accordingly.

The theme used her is [YAT](https://github.com/jeffreytse/jekyll-theme-yat) (Yet Another Theme), which pretty much just worked out-of-the box.
The main configuration settings: `defaults/home/banner` (which is used to set the header image), and `defaults/home/heading` and `defaults/home/subheading`, which are used to set to heading and subheading text that display over the banner image.
I've set them to empty strings for now while I think of something clever.
