# Does cooking time effect the number of calories?

by Akash Juwadi (ajuwadi@ucsd.edu)

***Note***: If you choose a repo name and title as uninspired as the ones here, I will be quite sad.

---

## Introduction

The goal of this project is to solve the main question of whether of not the cooking time of each recipe effects the number of calories?
In order to do this we will be using the recipes dataset which contains various different recipes and information about the different recipes.
This question is interesting to look at as its shows whether recipes that take a long time to prepare have more colorties than their counterparts with a shorter time. As such knowing this this would allow for people to make better use of their time and allow them to make the proper plans. 
The main columns from the dataset that I will be focusing on will be cooking time which is the length of time it takes to prepare a recipe, and number of calories which has the calories of each dish. 
---

## Cleaning and EDA

<iframe src="assets/10-80-enrollment.html" width=800 height=600 frameBorder=0></iframe>

---

## Assessment of Missingness

Here's what a Markdown table looks like. Note that the code for this table was generated _automatically_ from a DataFrame, using

```py
print(counts[['Quarter', 'Count']].head().to_markdown(index=False))
```

| Quarter     |   Count |
|:------------|--------:|
| Fall 2020   |       3 |
| Winter 2021 |       2 |
| Spring 2021 |       6 |
| Summer 2021 |       4 |
| Fall 2021   |      55 |

---