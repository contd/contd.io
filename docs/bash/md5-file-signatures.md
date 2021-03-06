---
title: MD5 File Signatures
lang: en-US
tags:
  - bash
layout: layouts/post.njk
---

# {{ $page.title }}

The command `md5 <file>` generates a unique 32-digit hexadecimal number. This can serve as a signature for a file in its particular state, letting you know when it has changed.

Example usage:

```bash
touch test.txt
md5 test.txt
  MD5 (test.txt) = d41d8cd98f00b204e9800998ecf8427e
echo 'some content' > test.txt
md5 test.txt
  MD5 (test.txt) = eb9c2bf0eb63f3a7bc0ea37ef18aeba5
```
