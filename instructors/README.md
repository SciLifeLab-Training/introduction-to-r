# Instructor guide: Introduction to R

Notes for instructors teaching Introduction to R. These files are not
part of the training website: participants don't see them there. Each
day has its own file with teaching notes; this page covers the training
as a whole.

## Who can teach this training

- **Instructors:** you use R and the tidyverse in your own work, and are
  comfortable live coding in front of a group. Teaching experience helps,
  but isn't required.
- **Team size:** one instructor and one helper per 10 participants. With
  25 participants, that's three instructors or helpers in the room.

## Timing

Each day runs from 9:00 to 15:00, with a coffee break in the morning and
a one-hour lunch.

| Day | Topic | Teaching | Hands-on | Total |
|---|---|---|---|---|
| [Day 1: Getting started](day-1.md) | R and RStudio, reading data | 2 h 30 min | 2 h | 4 h 30 min |
| [Day 2: Data wrangling](day-2.md) | Tidy data, reshaping, descriptive statistics | 1 h | 3 h 45 min | 4 h 45 min |
| [Day 3: Plotting](day-3.md) | ggplot2, and the final exercise | 1 h 30 min | 3 h 15 min | 4 h 45 min |
| **Total** | | | | **14 h** |

Teaching includes the welcome and the wrap-up. Hands-on includes the
practicals, exercises and the final exercise. The times match the
schedule on the training website.

## Participant preparation

Participants install R and RStudio, and download the course data, before
the training. The Preparation page of the training website explains how.
Two weeks before, an announcement reminds them.

## Instructor preparation

**A few weeks before**

- [ ] Check that the materials and exercises still work with the current
      versions of R, RStudio and the tidyverse
- [ ] Book Air & Fire and the computer room, and order coffee and lunch
- [ ] Agree who teaches which part, and who helps

**The week before**

- [ ] Check that participants received the preparation instructions,
      and answer their installation questions
- [ ] Put the latest course data in the `docs` folder
- [ ] Print a few copies of the instructions for installing R, for
      participants who arrive without it

**On the day**

- [ ] Test the projector, and make the font in RStudio large enough to
      read from the back of the room
- [ ] Put up the sticky notes: green for "I'm done", pink for "I need
      help"

## Technical setup for instructors

- **Software and versions:** R 4.4 or later, RStudio, and the packages
  readr, dplyr, tidyr and ggplot2 (all part of the tidyverse).
- **Data:** `penguins.csv`, in the `docs` folder of this repository.
- **Accounts or access:** none needed.
- **How to check that everything works:** open RStudio, and run
  `library(tidyverse)` and `readr::read_csv("penguins.csv")` without
  errors.

## During the training

The instructor live codes, and participants type along on their own
laptops. Participants put up a pink sticky note when they need help, and
a helper comes over. At the end of each exercise, a green sticky note
means "I'm done". Wait until most notes are green before you move on.

## After the training

- [ ] Send the feedback survey on the last day
- [ ] Note what to improve for the next training instance, in these
      instructor notes
- [ ] Remove any participant data from the exercises before you commit
