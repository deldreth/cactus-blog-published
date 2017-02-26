# Cactus Blog with Published

This blog plugin allows for a new header attribute of `published` to be set to either `True` or `False`. If `False` the post will not be added to the generated post list. Just drop blog.py into the `plugins/` directory.

An example post header might be:
```
title: Best Post Ever
headline: There has never been a post better than this!
author: Devin
date: 26-02-2017
published: True
```

A post with published false can still be accessed with the direct URL.
```
title: Another Great Post
headline: But this post isn't ready for the public!
author: Devin
date: 26-02-2017
published: False
```
