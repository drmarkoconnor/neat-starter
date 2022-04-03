---
name: Peter
email: email@theauthorsemail
twitter: #authorstwitterhandle
authorimage: /static/img/us-99.jpg
description:
  'Wow this author is great and I wonder whether the single quotes are needed'
tags: author
---

Generally via the CMS this blurb might not be needed. A short description in the
front matter helps the pages where authors are cycled through. In the CMS the
body tag area adds information about the author into this main space

Posts created in cms add to the widgets which have th same names as the fornt
matter inside a teemplate within authors. So you can create a template in the
local environment or the CMS will add it here locally after a GIT refresh. The
front matter data however created is then passed for use in loops if so desired
with any selection from a loop like collections.authors.url linking to the right
selection

