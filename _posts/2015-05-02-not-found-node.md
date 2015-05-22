---
layout: post
title: Not Found Node
date: 2015-05-02 12:00:00
categories: posts
---

If you have had this error:

<pre>
  <code data-language="ruby">
    /usr/bin/env:node: No such file or directory
  </code>
</pre>
<br />
Probably your installation of nodejs don't work jajaja, but this can serve of help

<pre>
  <code class="ruby">
    sudo ln -s "$(which nodejs)" /usr/bin/node
  </code>
</pre>
