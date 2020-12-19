---
title: "Once a Daily Do"
layout: post
date: 2020-09-13 12:00
image: "/assets/images/Once a Daily Do/oaddlogo-sm.png"
headerImage: true
category: blog
author: garrett
description: App that generates Daily Activity Suggestions to adapt to extra time during the COVID pandemic.
projects: true
skills: Flutter, Teamwork, Markdown
weight: 6
---

**Skills:** Flutter, Teamwork, Markdown

**GitHub link:** [https://github.com/levylevylevy/onceadailydo](https://github.com/levylevylevy/onceadailydo)

<iframe width="560" height="315" src="https://www.youtube.com/embed/rrRIjnT-4zk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Once a Daily Do was my team's submission for HopHacks 2020. I worked with [Sadie Levy](https://github.com/levylevylevy) who helped on
the frontend and [Joshua Qin](https://github.com/qinjoshua) who wrote the backend to generate meaningful activities. Once a Daily Do
suggests daily activities because in the times of COVID-19, many people have been pushed away from 
their normal routines. As a result, more people than usual are battling with symptoms of depression.
Depression often manifests itself as a lack of energy to do anything; our app tries to provide simple
activities that anyone can do to re-gain momentum in life. Once a user has finished an activity, the
activity will be stored in the app's calendar. The app also has an achievement page for completing
various amount and types of activities. For more details about the hackathon's 
submission, see our [Devpost Page](https://devpost.com/software/once-a-daily-do).

As far as technical notes, the primary technical challenge with this app was implementing a markdown
renderer. We wanted to use markdown as the way to write and display activities. This way, we could
show images, videos, and audio files within the text of the suggested activities without having to
build a custom solution. The markdown renderer can be seen rendering an activity on the suggestion
screen. 

![A screen recording of the app](/assets/images/Once a Daily Do/once-a-daily-do.gif)