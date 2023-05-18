---
layout: post
title: "Proof-of-Stake Is a Defective Mechanism"
description: "A paper why proof-of-stake implemented as a distributed consensus mechanisms in the base layer of blockchain networks are defective cryptosystems by nature."
date: 2022-03-24
tags: cryptocurrencies
comments: false
---

Available at [IACR (International Association of Cryptologic Research)](https://eprint.iacr.org/2022/409.pdf)

*Abstract:* Proof-of-stake algorithms implemented as distributed consensus mechanisms in the base layer of blockchain networks are defective cryptosystems by nature. By trying to improve the energy efficiency of blockchains using proof-of-work in the consensus mechanism, proof-of-stake is introducing a set of significant new flaws in both monetary and governance models. Such systems are plutocratic, oligopolistic, and permissioned.

## Features
- Compatible with Jekyll 3.x and Github Pages
- Live local reloading for faster development
- **Responsive layout** built-in
- Supports Jekyll's built-in Sass/SCSS preprocessor
- Supports **Google Analytics**
- Supports **Disqus** for commenting
- Minimum Dependencies
- Rakefile for automation
    - `rake check`    - Check links/html files of the generated site
    - `rake clean`    - Clean up generated site
    - `rake post`     - Begin a new post in `./_posts`
    - `rake preview`  - Preview with livereload on local machine


### Adding posts
```
rake post title="A Title" [date="2012-02-09"] [tags=[tag1,tag2]] [category="category"]
```
This will create a markdown file in the default folder where all posts are stored in Jekyll; `_post`.

If you wish to **change the directory where posts are saved**, go to the `Rakefile` and edit the `CONFIG = { 'posts': CUSTOM_PATH_HERE }`. This will allow `rake post` to know where to save the new posts to.

The **drafts** you are working on can be saved in the `_drafts` directory. When you push your code to the server, files in this directory will NOT be included to the list o posts.
