---
layout: page
title: Cell-autonomous size homeostasis in mammals
description: Studying how cell growth and cell cycle progression are coupled in adult mouse skin stem cells.
img: assets/img/publication_preview/cell_autonomous.png
importance: 1
category: work
related_publications: true
toc:
  sidebar: left
---


## I study how cells keep their size

The mouse replaces almost all the cells in its skin every week.
Skin stem cells continually proliferate to generate these new skin cells.
Despite undergoing constant cycles growth and division, these stem cells
maintain very uniform and stable size distribution over the life of the mouse,
suggesting that they 'remember' big they are supposed to be from cycle to cycle.

How is this 'target size' encoded by the molecular constituents of the cell?
Is this 'target size' autonomously calculated by individual cells, or is it a
phenomena that emerges from cells interacting with each other in the tissue?
Can we change this 'target size'?

## What we knew and didn't know

We knew a lot from yeast that a key aspect of cell cycle control is coupling
cell cycle progression to cell growth, such that yeast cells don't grow too large
in size. For budding yeast, the G1-to-S transition is sensitive to cell size. If
a yeast cell is born too small compared to another cell, it waits longer in the G1 phase
so as to grow more. Thus, cells that were initially quite different in size when they
were born end up much more similar in size by the time they enter S phase.

However, despite more than a decade of research, it was unclear whether mammalian
cells coupled their cell cycle progression to their cell growth in quite the same
way. Conflicting observations from different _in vitro_ cell lines painted a really confusing
picture. I wanted to side-step these cell lines altogether. Therefore, I set out
to develop an experimental system in which we can study cell size homeostasis
in an _in vivo_ animal.

## Developing _in vivo_ imaging of mouse skin for quantitative 4D analysis of single cells

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/skin/intravital.png" title="intravital imaging" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
      How about just text?
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
