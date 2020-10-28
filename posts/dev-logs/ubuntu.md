---
title: Ubuntu
description: Ubuntu tips
date: 2020-08-11T14:00:00.000+00:00
tags:
- devlogs
layout: layouts/post.njk

---
## Npm on Ubuntu

Sometimes ubuntu won't let you install packages, with error 'EACESS no permissions'. Then,

    sudo npm install --save-dev  --unsafe-perm=true --allow-root

### Running processes in the background

Use the `nohup` command to run processes in the background. For example:

    $ nohup node index.js