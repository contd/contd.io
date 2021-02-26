---
title: Standard Output to Clipboard Buffer
lang: en-US
tags:
  - bash
layout: layouts/post.njk
---

# {{ $page.title }}

Adding `| pbcopy` to the end of any command will send the standard output to your clipboard.

`ls -al | pbcopy` inside a rails project directory allowed me to paste this:

```bash
Gemfile
Gemfile.lock
README.md
Rakefile
app
bin
config
config.ru
db
features
lib
log
public
script
spec
test
tmp
vendor
```