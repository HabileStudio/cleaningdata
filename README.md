---
title: "README"
author: "Pietra"
date: "8/27/2020"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

The analysis script presents the following steps:

File is downloaded and unzipped.
Files mentioned above are read separetely.
Two data frames are created, one for training data and one for test data.
These data frames are merged into one, together with information on subjects, activity, and features.
Means and standard deviations are calculated for each feature and are added to a new data frame.
Activity labels are added, and variables are renamed.
A tidy dataset is created, including subjects, activities, and means.
Finally the tidy data is saved as a .txt file.

There is a comment for each step in the script explaining what that piece of code does. 