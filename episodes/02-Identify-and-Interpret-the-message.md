---
title: "Identify and Interpret the Message"
teaching: 0
exercises: 0
---


:::::::::::::::::::::::::::::::::::::: questions 

1. What are four common messages usually communicated in a chart?
2. What are useful charts to communicate these messages?
3. How do we construct text to describe these messages?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

After completing this episode you will be able to:

- interpret and describe the message in four common chart types
- illustrate the message of four common chart types 

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

## Challenge 1

Choose the answer that most closely reflects your opinion.
Data visualization is for ____.

a) scientists
b) everyone
c) formal reports
d) economists

:::::::::::::::::::::::: solution 

## Output
 
`b) everyone!`

:::::::::::::::::::::::::::::::::


## Challenge 2: Pair the data type names with the examples    

Data Types  |   Example
1. discert   |  a. 1,2,3,...1000
2. continuous  |  b. 0,1
3. catagorical  |  c. dog, cat, turtle

:::::::::::::::::::::::: solution 

1. -> b
2. -> a
3. -> c

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![Example figs](https://excalidraw.com/#json=M5p-guinhbiUarNN8Y_fK,GZXhOkPA4qLCIgbEx9i12A)

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![Figure ? Pie chart of the abundance of caninids are fox or coyote](fig/compositionPlot.png){indicate the percentages}


![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Charts convey messages with interchangeable nouns and verbs
- Chart types ..
- Practice with linking chart types with charts is a valuable skill

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/