---
layout: post
title: Octopress 3 Surfaces
date: 2014-02-21T17:29:00-08:00
categories:
---
In this blog post we're going to talk a bit about [Octopress 3](https://github.com/octopress/octopress). 

>Octopress is a framework designed by [Brandon Mathis](http://brandonmathis.com/) for [Jekyll](http://github.com/mojombo/jekyll), the blog aware static site generator powering [Github Pages](http://pages.github.com/). 

Octopress 3 is described as ___A Ruby Command-Line Interface shipped as a Gem___ and as such is a complete rewrite of the old Octopress that we all love. It's currently at 3.0.0.alpha6 and getting better with every release. It is in no way complete however and is missing support for themes and plugins for example. There is also some oddities (missing bits) with the Markdown portion of it.

Regardless once completed, [Octopress 3](https://github.com/octopress/octopress) will be an pretty significant upgrade and improvement over [Octopress 2](https://github.com/imathis/octopress).

### Installation
Add this line to your application's Gemfile:

`gem 'octopress'`

And then execute:

`$ bundle`

Or install it yourself as:

`$ gem install octopress`

### Usage
**Generating a new site**

To create a new scaffold of directories and files in a new directory named my_blog:

`$ octopress new my_blog`

**Generating a new Post**

To create a new post just run:

`$ octopress new post "My Title"`

**Generating a new Page**

`$ octopress new page --path about/index.markdown`

### Other Options/Subcommands

```bash
$ octopress -h
octopress 3.0.0.alpha6 -- Octopress is an obsessively designed toolkit for Jekyll blogging.

Usage:

  octopress <subcommand> [options]

Options:
        -h, --help         Show this message
        -v, --version      Print the name and version
        -t, --trace        Show the full backtrace when an error occurs

Subcommands:
  new                   Creates a new Jekyll site scaffold in PATH
  publish               Convert a draft to a normal published post.
  build                 Build your site
  serve                 Serve your site locally
  serve                 Serve your site locally
  doctor                Search site and print specific deprecation warnings
  doctor                Search site and print specific deprecation warnings
  docs                  Soon: Launch local server with docs for Octopress v3.0.0.alpha6
  deploy                Deploy your Octopress site.
  ```


