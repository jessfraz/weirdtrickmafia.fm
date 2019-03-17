# weirdtrickmafia.fm

Source code for [weirdtrickmafia.fm](https://weirdtrickmafia.fm).

## Adding a new episode

Create a new md file in [`content/post`](content/post) with the name of the episode.

It should have contents that look like the following:

```
+++
date = 2019-03-17T09:59:40-05:00
title = "Foundation Head"
description = "Andrew Clay Shafer and Jess Frazelle discuss open source foundations, specifically the Linux Foundation."
podcast_file = "foundation-head.mp3"
hosts = ["littleidea", "jessfraz"]
explicit = "yes" # values are "yes" or "no"
youtube = "bNfAAQUQ_54"
+++

Andrew and Jess discuss open source foundations, specifically the Linux
Foundation.
```

### Hosts

The `hosts` line above must line up with files in the [`data/hosts`](data/hosts) directory.
If there is a new host, they will need a new file in this directory.

### Audio Files

The `podcast_file` line above must correspond to the file in the [`static/audio`](static/audio) directory.
