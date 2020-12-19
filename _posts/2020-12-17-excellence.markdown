---
title: "Excellence Animation Editor"
layout: post
date: 2020-06-20 12:00
image: "/assets/images/excellence/Play n Pause and Speed Change.gif"
headerImage: true
category: blog
author: garrett
description: A powerpoint-like animation editor built in Java+Swing.
projects: true
skills: Java, Swing, Pair Programming
weight: 5
---

**Skills:** Java, Swing, Pair Programming

**GitHub link:** [available upon request](mailto:smith.garr@northeastern.edu)

I pair-programmed Excellence in Java (Swing) with [Dan Susman](https://github.com/dansusman) for a course called Object Oriented Design. As such, the code is not public but can be made public upon request.

<div class="side-by-side">
    <div class="toleft">
        <p>Features include creating, deleting, and modifying shapes as well as creating, modifying, and
deleting keyframes to animate these shapes along a timeline. This animation editor can also read from a custom
file format to produce a graphical animation. To the right is an example of such a file.</p>
    </div>

    <div class="toright">
        <img class="image" 
          src="/assets/images/excellence/Animation File Screenshot.png" 
          alt="An example of the file type that our code could read from.">
        <figcaption class="caption">Example file that our code can read from</figcaption>
    </div>
</div>

Something both Dan and I were proud of is our implementation of getting a single frame in the graphical animation. Our implementation of a binary search tree via a HashMap allowed us to find the properties a shape should have at the current time in logarithmic time, relative to the number of keyframes a shape went through. In other words, a shape could have millions of keyframes, and the animation player can still find the appropriate properties for that shape in time to play a smooth animation.

Some more screen recordings below if you're interested. 

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="/assets/images/excellence/Addding Shapes.gif" alt="Picture of adding a shape to the animation">
        <figcaption class="caption">Adding a shape to the animation</figcaption>
    </div>

    <div class="toright">
      <img class="image" src="/assets/images/excellence/Keyframe editing.gif" alt="Adding a keyframe to the animation">
      <figcaption class="caption">Adding a keyframe to the existing animation</figcaption>
    </div>
</div>