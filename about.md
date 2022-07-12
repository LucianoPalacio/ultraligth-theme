---
layout: page
title: About
permalink: /about/
---

Ultralight is super-lightweight responsive super Jekyll theme.
It can be hosted on GitHub Pages/IPFS.

#### Internal link

On IPFS, all internal links must be relative links.
You can use `relative` template like this:

```
{% raw %}[link]({% include relative %}{% post_url your-article-filename %}){% endraw %}
```
