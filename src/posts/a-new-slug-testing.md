---
title: A new slug testing
description: Does the slug on identifier field name work
author: Jason Checker
date: 2022-02-16T16:15:42.858Z
image: /static/img/old_rectory-5.jpg
---
Well what a naughty ask ...



For folder collections where users can create new items, the `slug` option specifies a template for generating new filenames based on a file's creation date and `title` field. (This means that all collections with `create: true` must have a `title` field (a different field can be used via [`identifier_field`](https://www.netlifycms.org/docs/configuration-options/#identifier_field)).

The slug template can also reference a field value by name, eg. `{{title}}`. If a field name conflicts with a built in template tag name - for example, if you have a field named `slug`, and would like to reference that field via `{{slug}}`, you can do so by adding the explicit `fields.` prefix, eg. `{{fields.slug}}`.