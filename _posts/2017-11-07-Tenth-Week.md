---
layout: post
title: Week 10
---

"What I've done"? 
---

I spent a large amount of time just for deploying the app (again) on Google App Engine (GAE). There were all sorts of issues that I ran into with the auto-generated Docker image of GAE, so after struggling for days, I decided to switch to Google Container Engine which allows me to deploy the app with my own Docker file. Thankfully, everything was up and running within a few hours.

I also worked on the NLP project later of the week and was so glad to get it done quickly thanks to all the regex-fu taught in this class!

What's in my way?
---

The next phase of the project & and catching up with lectures and assignments from other classes.

Plan for next week
---

Get things done.

My experience of the class
---

I am enjoying the class so far. I have learned a lot of new things compared to when I first started thanks to the projects and the lectures. I don't like my having my grade being brought down due to missing daily quizzes for interviews, but so far professor Downing has been understanding since there's been opportunities for extra credits, so I hope my grade won't end up badly.

Tips of the week 
---

Running out of space on UTCS lab machines and don't know which files to delete? 

The following command will sort all your files by size in descending order along with their paths, so you can just see which ones are eating up all your disk space!

```
du -sh ./* ./.??* | sort -h
```
