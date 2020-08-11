---
title: Docker
description: Docker Tips
date: 2020-08-11T14:00:00Z
tags:
- devlogs
layout: layouts/post.njk

---
### Tips

* When using alpine as the base image in a Dockerfile, remember you won't be able to use Debian commands like `sudo apt-install`
* 'docker-compose up' builds and runs the app, but might need to rebuild if you've made changes to the dockerfile.
* Remember 'Docker' runs in an isolated environment and has no additional apps installed unless specified (like chromium for example).