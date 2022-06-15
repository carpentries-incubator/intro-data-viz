---
title: "Communicating the Message"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- TODO

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Identify what you would like to communicate about a dataset.
- Identify what kind of data is best presented by which chart types

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

:::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::

:::: challenge 

## You have data on the number of carrots consumed by hares and by tortoises, what kind of message do you want to communicate
1. The relationship between number of hares and number of carrots of consumed
2. The distribution of hares and tortoises
3. A comparison of the number of carrots eaten by tortoises and hares

::: solution 

## Correct Answer 3
You have two groups each having consumed a different number of carrots, this is best described as a comparison.

:::
::::

:::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::

[r-markdown]: https://rmarkdown.rstudio.com/
