---
title       : Data sharing policy
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

# Title
Adapted from [How to share data with a statistician](https://github.com/jtleek/datasharing) by Jeff Leek

---

## Why prescribe how to share data

1. Because it influences speed (and speed matters)
2. Helps you and the statistician better understanding data
3. Reduces errors and iterations (did we say speed matters?)
4. Improves reproducibility
5. Helps communicating
6. Makes the life of the statistician **much** easier
 
---

## What you should deliver and why


1. The raw data: because it's the most trustable source.
2. A tidy data set: because it is directly processable, more on this later.
3. A code book describing each variable and its values in the tidy data set: it reduces errors, helps understanding, enforces reproducibility.
4. An explicit and exact recipe you used to go from 1 -> 2,3

---

## The raw data

Examples:

1. FACS output (the `.fcs` file, before using Flowjow or anything else).
2. The `.csv` or `.txt` file from the plate reader (**before** loading into Excel).
3. Microscopy `.tiff` images.
4. NGS sequences in `.fastq` format

---

## Raw means:

1. No software analysis
2. No manipulation/removal of data
3. Data were not summarised

If manipulated data is reported as raw, the statistician has to perform an extra autopsy to find out what went wrong.

---

## Tidy data set

A tidy data set follows two fundamental principles:

1. Measured variables on the columns
2. Single observations of the variables on the rows

Moreover, use different tables for different types of variables (no Excel worksheet) and use ids to link different tables.

---

## Example of a tidy data set

Observation of incidence of diabetes Clinical observation




