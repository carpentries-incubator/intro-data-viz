---
title: "Graphical Elements of a Chart"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions

- When creating a chart, what graphical elements do I have to work with?
- How do these graphical elements translate into representations of data?
- Which chart design components are easier for people to perceive accurately?
- How do design components support or detract from a chart's message?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- possibly temporary:
- List elements of human perception that influence how well a chart communicates
- Identify elements of chart design that work with and against human perception

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown](https://pandoc.org/MANUAL.txt) for static files and
[R Markdown][r-markdown] for dynamic files that can render code into output.
Please refer to the [Introduction to The Carpentries
Workbench](https://carpentries.github.io/sandpaper-docs/) for full documentation.

What you need to know is that there are three sections required for a valid
Carpentries lesson:

 1. `questions` are displayed at the beginning of the episode to prime the
    learner for the content.
 2. `objectives` are the learning objectives for an episode displayed with
    the questions.
 3. `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge

## Challenge 1: List elements of human perception that interact with charts and graphs

From the list below, choose the three elements of human perception that interact with charts and graphs

a. Object position
b. Linear properties
c. Spatial properties
d. Scent
e. Texture

:::::::::::::::::::::::: solution

## Answers

a, b, and c are the correct choices.

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints

- Graphical elements of chart design represent data relationships through position, shape, size, shading, and color
  - *use this list to simplify the Cleveland & McGill 10 perceptual tasks below*
- Move details up into lesson material:
- The graphical elements available for chart design (Bertin, 1981) are:
  - point
  - line
  - area
  - volume
  - shading (percent black to white, or grayscale)
  - color
- These elements represent data relationships through design components:
  - position
  - scale alignment
  - length
  - direction
  - angle
  - size (area and volume)
  - curvature
  - shading
  - color saturation
- Research suggests that many people can evaluate some of these design components more quickly and with more accuracy than others (Cleveland & McGill, 1984)
- Design components that are easier to perceive accurately support a chart's message
- Design components that are more difficult to perceive accurately detract from a chart's message

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
