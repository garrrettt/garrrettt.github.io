---
title: "Visualizing Algorithms"
layout: post
image: "/assets/images/Algorithms/algorithm icon.png"
headerImage: true
category: blog
author: garrett
description: 2 algorithms that I have implemented in Java.
projects: true
skills: Implementing Algorithms, Java
weight: 7
---

**Skills:** Implementing Algorithms, Java

**GitHub link:** [Available upon request](mailto:smith.garr@northeastern.edu)

The following two small projects were made in my Fundies 2 class and are examples of implementing
algorithms and visualizing them. Also note that both of these algorithms were pair
programmed with [Nicholas Miklaucic](https://github.com/nicholas-miklaucic).

### Seam Carving
[Seam Carving](https://en.wikipedia.org/wiki/Seam_carving) is a content-aware image-resizing
algorithm. The algorithm tries to find "seams" of pixels to remove that are "uninteresting" to the
overall picture. In the image below to the left, you can see the seams visualized that the algorithm
chooses and wants to remove. In the image below to the right, you can see this algorithm in action,
removing "uninteresting" parts of the image, trying to just keep the most interesting part: the tree.
<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="/assets/images/Algorithms/colored seam carving.gif" 
        alt="This animation shows visual seams being carved through an image to reduce the image's size.">
        <figcaption class="caption">This animation shows visual seams being carved through an image to reduce the image's size.</figcaption>
    </div>
    <div class="toright">
      <img class="image" src="/assets/images/Algorithms/tree seam carving.gif" alt="This animation shows an image of a tree being reduced in size via the seam carving algorithm.">
      <figcaption class="caption">This animation shows an image of a tree being reduced in size via the seam carving algorithm.</figcaption>
    </div>
</div>

### Maze Solving
Maze solving is a classic algorithm to implement. First, Nicholas and I implemented a maze
generator, which used Kruskal's algorithm to make a minimum spanning tree to represent the maze.
Nicholas and I implemented both DFS and BFS algorithms to find a way through both a hexagonal and
a grid type of maze. It's important to note here that good abstraction was necessary here because
fundamentally, hexagonal mazes and grid mazes are similar and should be in the same type of
data structure so that we only needed to implement BFS and DFS once on that one data structure.
<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="/assets/images/Algorithms/grid maze.gif" 
        alt="This animation shows a grid maze being solved by a DFS algorithm.">
        <figcaption class="caption">This animation shows a grid maze being solved by a DFS algorithm.</figcaption>
    </div>
    <div class="toright">
      <img class="image" src="/assets/images/Algorithms/hex maze.gif" alt="This animation shows a hexagonal maze being solved by a DFS algorithm.">
      <figcaption class="caption">This animation shows a hexagonal maze being solved by a DFS algorithm.</figcaption>
    </div>
</div>