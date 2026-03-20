---
layout: ../layouts/MarkdownLayout.astro
title: Projects — Tudor Evans
---

# Side projects

Here I keep a list of a few things I've built in my own time. It's currently sparse because my time is spare, but I'm hoping that Claude Code can change that!

## Goodspeed

***Puts on dramatic voice*** In a world where resources are deeply constrained, prioritising what to work on is everything. A firehose pipeline like Kafka is just fine if you want to process messages at or near realtime speeds. But if you have high-resource use cases, where jobs take a whole to complete, prioritising workloads is all-important, especially if you're serving client requests for priority users.

Goodspeed attempts to solve this problem by providing a fair queueing, distributed priority queue system. It's currently a working PoC (or maybe MVP). It's written in rust, has an easy-to-use Docker deployment at the ready, and also has python bindings for the rust client so you can quickly get setup with it in your system.

Find the GitHub repo [here](https://github.com/TudorLEvans/goodspeed)


