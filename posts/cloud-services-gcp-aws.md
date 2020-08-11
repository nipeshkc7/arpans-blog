---
title: Cloud Services (GCP/AWS)
description: Tips/Issues on GCP/AWS
date: 2020-08-11T14:00:00Z
tags:
- devlogs
layout: layouts/post.njk

---
### Cloud Run

Cloud Run lets you run stateless containers that scale up very nicely. You don't have to pay anything until you start getting millions of requests. However, CloudSQL does cost money from the start, (its a way of introducing states in the app)

### Cloud Pub/Sub

Lets you publish to a topic, and cloud pub/sub automatically pushes the message to all the subscribers(client apps in most cases). The advantage is, it lets you set up any number of subscribers to a single event.

### Weird issue on GCP

Trying to add environment variable 1, GCP sets it to '1' automatically.