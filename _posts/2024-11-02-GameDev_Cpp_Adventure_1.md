---
title: GameDev C++ Adventure - Pt. 1
date: 2024-11-02
categories: [GameDev, Cpp]
---

A delve into the gamedev adventures with `C++`.
<!--excerpt-->

For a long time, I wanted to create games. I am mainly a casual gamer and am interested more in the underlying systems of games rather than on the actual gameplay. 3 weeks ago, I set myself a task that I will learn some gamedev. I started to closely follow [Chili Tomato's Beginner Tutorial](https://www.youtube.com/playlist?list=PLqCJpWy5FohcehaXlCIt8sVBHBFFRVWsx) with some occasional watching [TheCherno's C++ Playlist](https://www.youtube.com/playlist?list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb).

Despite being a bit familiar with C++ language (but not using it for few years), I still think it's valuable to go through the beginner's playlist. The videos are well done, the overall structure of the framework is well prepared for a newcomer as well as an experienced person. The coding practices that are taught I really recommend. The course pacing is followable, but it's better to spend some time tinkering and hacking around the code alone, not following the tutorial. This is also what the author recommends.

I am now 14 videos in, covering topics like:
- basics like loops, conditionals, variables
- basics of object-oriented programming, references
- encapsulation, constructors
- debugging
- arrays

So far I tend to closely follow the tutorial so I have code prepared for the next one, however I have implemented few of my own additions, such as `Point` object with `x` and `y` coordinates to address certain anchor points on the list and moved all rendering and drawing calls to the `Graphics.h/cpp` files. Other than that, I have a feeling that sooner or later, I will want to write my own framework or "engine", because the problems are very interesting. I am also interested in the graphics itself, such as graphics APIs and rendering pipeline. I will definitely want to visit that.

# Tutorial 14 - Snake Game
14th tutorial is the Snake game tutorial. It is split into two parts - the first part creates a basic framework for the snake and it is up to the viewer to take the challenge and try to implement the rest of the game. I have taken the challenge and tried to finish the snake game. I got stuck at creating the movement delay for the snake, however the rest was pretty functional. After having a functional prototype, I watched the second part of the tutorial and implemented the snake according to it. My code was a bit messy so I went with the provided one. I ended up adding several types of food:
- food that will shorten the snake by 2 cells
- food that will lengthen the snake by 2 cells
- food that will speed up the snake for certain amount of time

I have couple of other ideas for extension of the game - I can add:
- obstacles
- menu that will allow the player to select how big the board should be (using arrow keys)
