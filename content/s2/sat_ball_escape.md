# [SAT] Ball Escape

And finally, welcome to the last challenge for this academic year! After this, you will be graduated to the upper grade!

This time, we challenge you to re-create the **Ball Escape** Scratch 3.0 project as the final challenge. We will use it for your final score in this semester. Not taking much further, let's go!

---

## Code Review on the Ball Escape

:::{iframe} https://scratch.mit.edu/projects/1175372410/embed
**Ball Escape**

How to control:
Use your finger, the ball will follow you!
:::

Let's take a look at this slide!

```{image} ../../_static/images/content/sat/batasan-materi.jpg
:alt: Batasan Materi
:align: center
```

The criterias means:

**The ball must not pass through the wall**
It means the code on the ball should precisely coded carefully and without any single mistake

**Can advanced to the next level**
It means that when the ball touches the red color, it will make the screen change to the next level, and if the ball touches the blue color, it will bring us to the game end screen

**Have victory screen**
You should create your own image/pictures/sketch for the game end screen, it will pump your score higher than you use the stock assets from the Scratch 3.0

---
To make it clear, let's dive in deeper into the code:

### Code Insight

#### Basketball
```{image} ../../_static/images/content/sat/ball.png
:alt: Basketball
:align: left
```


::::{tab-set}
:::{tab-item} 1
:sync: 01
**Color detection**

The ball should detect these 3 colors
```{image} ../../_static/images/content/sat/ball-01.png
:alt: Basketball Code 01
:align: center
```
:::

:::{tab-item} 2
:sync: 02
**The ball direction**

The ball always points to the cursor/touch
```{image} ../../_static/images/content/sat/ball-02.png
:alt: Basketball Code 02
:align: center
```
:::

:::{tab-item} 3
:sync: 03
**The ball movement**

The ball movement is also affected by speed value
```{image} ../../_static/images/content/sat/ball-03.png
:alt: Basketball Code 03
:align: center
```
:::

:::{tab-item} 4
:sync: 04
**The ball initial state**

The ball position starts from the left bottom, clear any graphic effects, and make it small
```{image} ../../_static/images/content/sat/ball-04.png
:alt: Basketball Code 04
:align: center
```
:::

:::{tab-item} 5
:sync: 05
**The ball detects when the backdrop changes to finish**

The ball will stop other ball scripts and move to the center, then rotate, grow, and brighten
```{image} ../../_static/images/content/sat/ball-05.png
:alt: Basketball Code 05
:align: center
```
:::
::::
