---
title: "The Importance of Message"
teaching: 15
exercises: 5
---

:::::::::::::::::::::::::::::::::::::: questions

- What is a chart?
- What is the purpose of a chart?
- What do we need to make a chart?
- Why is chart message so important?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Define what a chart is
- Explain the purpose of a chart
- Identify the components of a chart
- Explain the importance of a chart's message

::::::::::::::::::::::::::::::::::::::::::::::::

## What is a chart?

A chart is a visual representation of the relationships among data elements. A visual representation allows people to see and quickly comprehend relationships among data elements by processing the information in the brain's visual cortex[^1].

[^1]: Bertin, J. (1981). Graphics and graphic information-processing (W. J. Berg & P. Scott, Trans.). de Gruyter.

## Purpose of a chart

The purpose of a chart is to communicate. An effective chart clearly communicates a message to the viewer. An ineffective chart confuses the viewer because it contains no message or several muddled messages.

## Components of a chart

The individual pieces that we need to build a chart are:

- Data arranged in a table
- A message about the data
- Graphical elements

An imbalance in any of these components will make a chart ineffective or impossible:

- Without data, a chart has no information to communicate
- Without a message, a chart has nothing clear to say about the data
- Without graphics, a chart cannot visualize information

In this episode, we will talk about data, tables, and messages. We will address graphical elements in the next episode.

:::::::::::::::::::::::: callout

### Why no software?

It may seem odd that the key components of a chart do not include software. While software is a useful tool for chart-making, it is not strictly necessary. You can create an effective chart by hand as long as you have the three essential chart components: a table of data, a message about the data, and graphical elements. Software can help you arrive at these three components more quickly, but it cannot automatically create an effective chart on its own. An effective chart communicates, and communication is a human activity.

:::::::::::::::::::::::::::::::::

### Prepare the data

Refer to Data Carpentry Ecology Spreadsheets lesson for more on tidying and cleaning data to prepare it for analysis - put this in a callout; specifics of how to do this are outside the scope of this lesson.

Preparing data before creating a chart,

Data that is clean - outliers, nulls, missing data, free of white space, - summarizable, countable, and calculable

Data that has consistent field (column) names

Free of formatting

Data that is tidy - columns for variables, rows for observations, one value per cell - leads into tables next

Cite Wickham[^2]

[^2]: Wickham, H. 2014. “Tidy Data.” Journal of Statistical Software 59 (10). 10.18637/jss.v059.i10 [http://dx.doi.org/10.18637/jss.v059.i10](http://dx.doi.org/10.18637/jss.v059.i10)


### The role of tables

Tabular formats - common spreadsheet programs and delimited files - csv and tsv - can create and save data in a tabular format - that is, vertical columns arranged on top that intersect horizontal rows arranged below the column headings. The intersections create individual cells that contain individual data points.

**Insert a hand-drawn table structure**

A table is a necessary precursor to a chart, but is not a substitute for a chart. A table must be read to convey its information, and it is difficult and time-consuming to try to understand any patterns that might be present in the data. Consider this data table:

| Average Monthly Temperature | Daily Walks per Dog |
|:---:|:---:|
|30 |0 |
|35 |1 |
|45 |1 |
|55 |2 |
|65 |3 |
|78 |2 |
|80 |2 |
|88 |1 |
|70 |3 |
|60 |3 |
|45 |1 |
|35 |0 |

:::::::::::::::::::::::: discussion

Take 1 minute to read the table and discuss it with your neighbor. How easy or difficult is it to understand the data? What patterns can you detect?

:::::::::::::::::::::::::::::::::

### From table to chart

To create a chart, data elements recorded in a table are arranged along the `x` and `y` axes of a Cartesian plane.

Need a figure here to illustrate x, y, and their intersections (the relationships) - maybe this is the activity? A blank chart and a data table?

**TODO**: Insert the chart for the table above

Insert figures into this section with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

:::::::::::::::::::::::: discussion

Take 1 minute to view the chart and discuss it with your neighbor. How easy or difficult is it to understand the data? What patterns can you detect?

:::::::::::::::::::::::::::::::::

## Chart message

The relationship between the two elements that emerges when `x` is plotted against `y` creates the message of the chart[^1].

The message is one sentence that describes the relationship between data elements that you plot against each other on x and y; ideally this sentence becomes the title of your chart.
If you are having trouble stating the relationship in one sentence, you may have too many relationships for one chart.

More here - it takes practice to identify and articulate a message for a chart, but knowing where it comes from is a first step. You'll practice this skill more during subsequent episodes.

::::::::::::::::::::::::::::::::::::: challenge

## Challenge 1: Identify a chart message

Choose the sentence that best describes the relationship depicted in the chart above:

1. Dogs get fewer daily walks during seasonal temperature extremes.
2. Monthly average temperature varies during the year.
3. Dogs get between 0 and 4 walks daily.

:::::::::::::::::::::::: solution

## Answer

The correct answer is 1. This sentence describes an interaction between seasonal temperature and number of daily walks. These are the two data elements plotted on the `x` and `y` axes of this chart.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Importance of Chart Message

Clearly-imparted information - messages - about relationships within a set of data drive problem-solving and decision-making about the entities represented by the data. These solutions and decisions have real-world consequences.

In this lesson we will use a dataset about large North American canids: wolves, coyotes, and foxes[^3]. Public policy and scientific decisions have drastically changed these populations over the past century. The presence or absence of these animals near population centers, livestock, and nature preserves stirs public debate in the present day.

In this lesson you will learn to craft messages about data and communicate those messages in charts. You will practice communicating scientific information about large North American canids in messages and charts that the public can understand.

[^3]: Newsome, T. M. & Ripple, W. J. (2015). Data from: A continental scale trophic cascade from wolves through coyotes to foxes, Dryad, Dataset, [https://doi.org/10.5061/dryad.s0d20](https://doi.org/10.5061/dryad.s0d20)

::::::::::::::::::::::::::::::::::::: keypoints

- A chart visualizes data relationships in a format that people can see instead of read.
- The purpose of a chart is to communicate.
- Data arranged in a table and a message about the data are two of the three components of a chart.
- A chart's message drives decision-making and problem-solving.

::::::::::::::::::::::::::::::::::::::::::::::::
