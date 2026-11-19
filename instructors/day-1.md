<!-- Not on the website, but public on GitHub and Zenodo: never write
     passwords, access codes or exam answers here. -->

# Day 1: Getting started

**Time:** 9:00 to 15:00. 2 h 30 min teaching, including the welcome, and 2 h hands-on.

**Pages:** [content/day-1](../content/day-1/)

## Key points

The three things participants must take away from today:

- RStudio is where they write, run and save R code, organised in
  projects.
- Data is read into R with `read_csv()`, and stored in a data frame.
- They can look at their data with `head()`, `nrow()`, `ncol()` and
  `summary()`.

## Teaching flow

| Time | What |
|---|---|
| 9:00 | Welcome, introductions, and the practical arrangements |
| 9:30 | R and RStudio basics: live coding, with participants typing along |
| 10:30 | Coffee break |
| 11:00 | Reading data into R: live coding with `penguins.csv` |
| 12:00 | Lunch |
| 13:00 | Exercise: explore your first dataset |
| 14:30 | Go through the solutions together, and questions |
| 15:00 | End of day 1 |

## Materials

Materials participants use are linked on the pages of
[day 1](../content/day-1/).

Materials for instructors only:

| Material | Link | Notes |
|---|---|---|
| Slides for the welcome (editable) | [Link](https://example.org/slides-day-1) | Update the names of the team before each training instance |
| Live coding script | [Link](https://example.org/script-day-1) | Follow it, but type everything live: don't paste |

## Exercises

- **Explore your first dataset:** participants read `penguins.csv`, and
  find out how many penguins and columns it has, and which species are
  in it. Expected outcome: 32 penguins, 6 columns, and three species:
  Adelie, Chinstrap and Gentoo.

## Common problems

- **"Could not find function read_csv":** the readr package isn't
  loaded. Run `library(readr)`, or `library(tidyverse)`.
- **"File not found" when reading the data:** the file isn't in the
  project folder. Show how to check the working directory with
  `getwd()`.
- **Participants without R installed:** a helper installs it with them
  during the welcome. Keep the printed instructions at hand.

## If you're short of time

- **Skip or shorten:** the tour of the RStudio settings.
- **If there's time left:** show how to read an Excel file with the
  readxl package.
