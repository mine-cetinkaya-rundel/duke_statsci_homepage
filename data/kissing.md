---
layout: data_dictionary
title: kissing.csv
---

### Get the data

Two options listed below:

1. Click <a href="kissing.csv" download="kissing.csv">
*here*
</a> to download the dataset.


2. Alternatively, use the following lines of code to load the data in R using the following:

<div class="highlight">
    <code>
    kissing <- read.csv("https://stat.duke.edu/~mc301/data/kissing.csv", stringsAsFactors = FALSE)
    </code>
</div>

### Data description

One of the earliest examples of behavioral asymmetry is a preference in 
humans for turning the head to the right, rather than to the left, during 
the final weeks of gestation and for the first 6 months after birth. This is 
thought to influence subsequent development of perceptual and motor 
preferences. A study of 124 couples found that 64.5% turned their heads to 
the right when kissing.

Reference: Güntürkün, Onur. "Human behaviour: adult persistence of head-turning asymmetry." Nature 421.6924 (2003): 711-711.

### Codebook

This data frame contains 124 observations (rows), each representing a couple,
and 1 variable (column):

1. `side` - preference of side couples turn their heads to when kissing 
(`left` or `right`)