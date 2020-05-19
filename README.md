# This repo was archived

https://github.com/jumpingrivers/meetingsR for updated list of events


### RWeekly Conferences

Twitter is a great place to _share_ conference slides but... it doesn't seem to be the best place to _read_ all these shared information. Needless to say a few days after the conference, all those shared links are just gone from your timeline. 

Here we are trying to create a repo to organize shared conference slides or github repos. As a result, you, me and everyone can enjoy our awesome #rstats conferences even if we cannot make the trip. 

Please help us collect as many resources as possible by [submitting a PR](https://github.com/rweekly/conferences/compare). We also encourage conference presenters to post links to their slides directly here after their presentation. 

### To Contribute

1. All the conference posts are stored in the `_posts` folder as `yaml` headers in those `md` files. 
2. Besides slides, we also want to highlight interesting #rstats packages announced or demonstrated during the conferences. These information should go to the `packages` section. 
3. We will create an entry for big #rstats events ahead of time. 
4. If you are a presenter but you don't want your slides to be shared here, please let us know or [fix it by yourself](https://github.com/rweekly/conferences/compare). 
5. If you have any new ideas, let us know by [submitting an issue](https://github.com/rweekly/conferences/issues/new). 

### YAML Header

```yaml
---
title: conf title
name: conf name
edit_link: https://github.com/rweekly/conferences/edit/master/_posts/....md
year: conf year
location:  conf loc
date: conf date
talks:

  - title: title
    speaker: speaker
    url: url

  - title: title
    speaker: speaker
    url: url

packages:

  - title: title
    speaker: speaker
    url: url

```

### YAML Fields

```yaml
  - title: talks title
    speaker: speak
    url: https://... 
    topics: topic (optional)
    video_link: https://... (optional)
    iframe: https://... (optional)
    image: https://... (optional)
    video: https://... (optional)
```
