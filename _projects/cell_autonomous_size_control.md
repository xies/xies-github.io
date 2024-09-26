---
layout: page
title: Cell-autonomous size homeostasis in mammals
description: Studying how cell growth and cell cycle progression are coupled in adult mouse skin stem cells.
img: assets/img/publication_preview/cell_autonomous.png
importance: 1
category: science
related_publications: true
toc:
  sidebar: left
---


## I study how cells keep to the same size

Size is one of the most fundamental parameters of a cell. Yet, we do not
understand what sets a cell's size, and once cells are formed, how they
maintain that size over time.

This mechanism is especially important in cell types in our bodies that are
constantly proliferating, that is, the stem cells. Both growth and division can
change cell size, and must be coordinated to keep cell size stability.

<br>
<br>
<br>

## What we knew (about yeast) and didn't know (about mammals)

Budding yeast cells coordinate their G1-to-S cell cycle transition to cell size.
Two cells that were born at different sizes end up more similar in size as they
enter S phase.

However, despite more than a decade of research in cell culture models, it was
unclear whether mammalian cells coupled their cell cycle progression to their
cell growth in quite the same way.

I set out to develop an <a href="https://xies.github.io/projects/2_project/">experimental
system</a> in which we can study cell size homeostasis in an _in vivo_ animal.
<br>
<br>
<br>

## The G1/S transition _in vivo_ is sensitive to cell size
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/skin/size_control_g1_length.png" title="growth curves" class="img-fluid rounded z-depth-5" %}
  </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/skin/size_control_g1.png" title="growth curves" class="img-fluid rounded z-depth-5" %}
    </div>
</div>
By analyzing how single cells grow _in vivo_, I found that cells that are born
smaller spend longer in G1 phase compared to larger born cells. This longer G1
time means they are allowed to grow more compared to their larger-born cousins. {% cite xie_g1} In
comparison, the rest of the cell cycle combined (S, G2, and M phases), was
insensitive to cell size.

This coordination between cell growth and the G1/S progression is very similar
to what was observed in budding yeast, and contrary to the majority of cell culture
models.
<br>
<br>
<br>

## The G1/S transition happens at an autonomously-encoded cell size threshold

Clearly, cell size is influencing whether skin stem cells _in vivo_ enter S phase or not
at any given time. However, it was unclear how much influence cell size (as opposed to
  a slew of other environmental signals and changes these stem cells).

Using quantitative image analysis, I analyzed how the dividing cell's morphology
as well as the tissue microenvironment surrounding it changed over time. Then,
using this rich set of information of <u>cell and microenvrionment morphometrics</u>, I
built statistical models to isolate which feature can predict whether cells will enter
the G1/S transition.

<br>
<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/skin/cell_intrinsic.png" title="cell morphology" class="img-fluid rounded z-depth-5" %}
  </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/skin/microenvironment.png" title="tissue microenvironment dynamics" class="img-fluid rounded z-depth-5" %}
    </div>
</div>
<div class="caption">
Image analysis pipeline to measure _in vivo_ cell and microenvironment morphometrics
</div>


Using quantitative image analysis, I analyzed how the dividing cell's morphology
as well as the tissue microenvironment surrounding it changed over time. Then,
using this rich set of information of <u>cell and microenvrionment morphometrics</u>, I
built statistical models to isolate which feature can predict whether cells will enter
the G1/S transition.

<br>
<br>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/skin/cell_intrinsic.png" title="cell morphology" class="img-fluid rounded z-depth-5" %}
  </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/skin/microenvironment.png" title="tissue microenvironment dynamics" class="img-fluid rounded z-depth-5" %}
    </div>
</div>
<div class="caption">
Image analysis pipeline to measure _in vivo_ cell and microenvironment morphometrics
</div>
<br>
<br>

These models predict G1/S transition with ~90% accuracy. Surprisingly, these models
reveal that _only_ cell volume had any significant predictive power. In fact, a
simplified model using only cell volume, a single variable, performed nearly
as well as the full model that had access to the full cell and microenvironment
features combined.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/skin/model.png" title="G1/S prediction model" class="img-fluid rounded z-depth-5" %}
  </div>
</div>

<br>
<br>

## Variation in reaching the G1/S cell size threshold accounts for >70% of stem cell cycle heterogeneity
