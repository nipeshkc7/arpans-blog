---
title: Node JS Tips
description: Tips about Node.js
date: 2020-10-22T13:00:00Z
tags:
- devlogs
layout: layouts/post.njk

---
### Debugging in Node.js

You can debug from the command line using: 

    node inspect index.js

Or, to debug using a different client like chrome browser use:

    node --inspect index.js

And visit `chrome://inspect` to visually debug the node.js app.