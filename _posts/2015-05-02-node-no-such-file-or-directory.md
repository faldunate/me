---
layout: post
title: Solution to /usr/bin/env: node: No such file or directory
date: 2015-05-02 12:00:00
categories: posts
---

## if you have had this error:

<pre>
  <code class="ruby">
    /usr/bin/env:node: No such file or directory
  </code>
</pre>

Probably your installation of nodejs don't work jajaja, but this can serve of help

<pre>
  <code class="ruby">
    sudo ln -s "$(which nodejs)" /usr/bin/node
  </code>
</pre>
