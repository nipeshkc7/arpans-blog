---
title: Ubuntu
description: Ubuntu tips
date: 2020-08-11T14:00:00Z
tags:
- devlogs
layout: layouts/post.njk

---
## Npm on Ubuntu

Sometimes ubuntu won't let you install packages, with error 'EACESS no permissions'. Then,

    sudo npm install --save-dev  --unsafe-perm=true --allow-root