---
title: SQL
description: Tips about SQL
date: 2020-09-28T15:00:00Z
tags:
- devlogs
layout: layouts/post.njk

---
## Tips about SQL

### SQL Injection

DO NOT pass in parameters to an SQL query directly from user inputs as this can open you up to SQL injections.

For eg, if a user sends `id=1; SELECT 1=1;` and you pass this into your SQL query directly, this can open up your entire DB for the user to see, or maybe the user sends `id=1; DROP TABLE 'users'`

So always sanitize the user inputs;

### Node Mysql

You can passing in query params into a nunjucks template like done here: [https://gist.github.com/nipeshkc7/6b1efd7810c653101edb28f64af8b00a](https://gist.github.com/nipeshkc7/6b1efd7810c653101edb28f64af8b00a "https://gist.github.com/nipeshkc7/6b1efd7810c653101edb28f64af8b00a")

Keep in mind, node-mysql flattens the arrays so you can pass in nested arrays as well.