# Notebook 2013-10

This is notebook comprises my notes for October 2013.

## Table of Contents

- [Tasks](#tasks)
  - [Items to address in all Chapters](#items-to-address-in-all-chapters)
  - [Items to address in Chapter 5](#items-to-address-in-chapter-5)
  - [Appendices](#appendices)
- [18 (Friday)](#18-october-2013-friday)
- [19 (Saturday)](#19-october-2013-saturday)


## Tasks

### Items to address in all Chapters

- [ ] Remove all '.' from figure and table labels.

- [ ] Make sure to use "toward" instead of "towards" for the entire document.
      - [x] Chapter 5

- [ ] Make sure Chapter is capitalized in all cross references.
- [ ] Replace all references to single/multi source "studies" with "test case"
      - [ ] Chapter 1
      - [ ] Chapter 2
      - [ ] Chapter 3
      - [ ] Chapter 4
      - [x] Chapter 5, There is an ambiguity of "test case" vs "test cases".
      - [ ] Chapter 6

### Items to address in Chapter 5

- [ ] Consider removing chapter introduction
- [ ] Break figure tables that span multiple pages and repeat captions.
      - [x] Figure 5.1
      - [x] Figure 5.2
      - [x] Figure 5.3
      - [x] Figure 5.4
      - [ ] Figure 5.19

- [ ] Remake emission source plots with larger source location symbols.
      - Address after we submit
      - Scat Size = 5%,  This maybe to small.  Maybe 8% is better.
      - Line Thick = 0.8%
      - May need to move source labels
      - [ ] Single Source, Linear, Noise = 0, Beta = 0, Iter = 25
      - [ ] Single Source, Linear, Noise = 0, Beta = 0, Iter = 50
      - [ ] Single Source, Linear, Noise = 0, Beta = 0, Iter = 100
      - [ ] Single Source, Linear, Noise = 0, Beta = 0, Iter = 200

      - [ ] Single Source, Linear, Noise = 10, Beta = 0, Iter = 25
      - [ ] Single Source, Linear, Noise = 10, Beta = 0, Iter = 50
      - [ ] Single Source, Linear, Noise = 10, Beta = 0, Iter = 100
      - [ ] Single Source, Linear, Noise = 10, Beta = 0, Iter = 200

      - [ ] Single Source, Log, Noise = 0, Beta = 0, Iter = 25
      - [ ] Single Source, Log, Noise = 0, Beta = 0, Iter = 50
      - [ ] Single Source, Log, Noise = 0, Beta = 0, Iter = 100
      - [ ] Single Source, Log, Noise = 0, Beta = 0, Iter = 200

      - [ ] Single Source, Log, Noise = 10, Beta = 0, Iter = 25
      - [ ] Single Source, Log, Noise = 10, Beta = 0, Iter = 50
      - [ ] Single Source, Log, Noise = 10, Beta = 0, Iter = 100
      - [ ] Single Source, Log, Noise = 10, Beta = 0, Iter = 200

      - [ ] Single Source, Linear, Noise = 0, Beta = 1, Iter = 200
      - [ ] Single Source, Linear, Noise = 0, Beta = 10, Iter = 200
      - [ ] Single Source, Linear, Noise = 0, Beta = 100, Iter = 200
      - [ ] Single Source, Linear, Noise = 0, Beta = 1000, Iter = 200

      - [ ] Single Source, Linear, Noise = 10, Beta = 1, Iter = 200
      - [ ] Single Source, Linear, Noise = 10, Beta = 10, Iter = 200
      - [ ] Single Source, Linear, Noise = 10, Beta = 100, Iter = 200
      - [ ] Single Source, Linear, Noise = 10, Beta = 1000, Iter = 200

      - [ ] Multi-Source, Linear, Noise = 0, Beta = 0, Iter = 25
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 0, Iter = 50
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 0, Iter = 100
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 0, Iter = 200

      - [ ] Multi-Source, Linear, Noise = 10, Beta = 0, Iter = 25
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 0, Iter = 50
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 0, Iter = 100
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 0, Iter = 200

      - [ ] Multi-Source, Log, Noise = 0, Beta = 0, Iter = 25
      - [ ] Multi-Source, Log, Noise = 0, Beta = 0, Iter = 50
      - [ ] Multi-Source, Log, Noise = 0, Beta = 0, Iter = 100
      - [ ] Multi-Source, Log, Noise = 0, Beta = 0, Iter = 200

      - [ ] Multi-Source, Log, Noise = 10, Beta = 0, Iter = 25
      - [ ] Multi-Source, Log, Noise = 10, Beta = 0, Iter = 50
      - [ ] Multi-Source, Log, Noise = 10, Beta = 0, Iter = 100
      - [ ] Multi-Source, Log, Noise = 10, Beta = 0, Iter = 200

      - [ ] Multi-Source, Linear, Noise = 0, Beta = 1, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 10, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 100, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 0, Beta = 1000, Iter = 200
      
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 1, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 10, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 100, Iter = 200
      - [ ] Multi-Source, Linear, Noise = 10, Beta = 1000, Iter = 200

- [ ] Change the "Ideal" label in the legend of objective function and coefficient of determination.
      - Approx. Min. ?
      - Est. Min. ?
      - [ ] Figure 5.5: Single Source, Objective Function
      - [ ] Figure 5.8: Single Source, Coefficient of Determination
      - [ ] Figure 5.14: Multi-Source, Objective Function
      - [ ] Figure 5.17: Multi-Source, Coefficient of Determination

- [ ] Move normalizing values to underneath the legend.
- [x] Update multi-source filtered emission source figures.
- [ ] Move up lower bound of Objective Function Plots
      - [ ] Figure 5.5: Single Source
      - Figure 5.14: Multi-Source does not need to be addressed

- [ ] Talk about regularization being an advantage at a cost
- [ ] Reconsider the gradient plots
      - Maybe move to an appendix.
      - Combine gradient and projected gradient into a, b plots.
      - Shorten discussion
      - Do these plots have meaningful information?
      - Remove from summary table?

- [ ] Quantify spatial correlation of candidate emission sources
      - Consider Carol's spatial correlation measures
      - Add location correlation to summary table

- [ ] Combine Multi-Source linear and log scale appendices
      - [ ] Iteration, MSCONV1 (linear) + MSCONV2 (log)
      - [ ] Regularization, MSREG1 (linear) + MSREG2 (log)

### Appendices

- [ ] Appendix MSCONV
      - Combine the linear and log scale plots into a single appendix with section labels
- [ ] Appendix MSREG
      - Combine the linear and log scale plots into a single appendix with section labels


## 18 October 2013 (Friday)

Within Tecplot, the emission source labels for the multi-source studies need to move closer to source locations for zoomed in views and further away for views of the full domain.  This table shows the is the previous source label locations

### Old Emission Source Label Locations[old-labels]

- From 2013-09-26

| Label | x [m] | y [m] |
|------:|:-----:|:-----:|
|   A   |  683  |  591  |
|   B   |  713  |  757  |
|   C   |  412  |  580  |
|   D   |  513  |  783  |
|   E   |  811  |  780  |
|   F   |  577  |  727  |
|   G   |  673  |  904  |
|   H   |  502  |  687  |
|   I   |  568  |  626  |
|   J   |  736  |  668  |

The new suggested emission source label locations are shown as follows


### Plot Settings

- Set: Text Box = Filled
- Set: Position Coordinate System = Grid
- Set: Source Symbol Size = 5%
- Set: Source Symbol Thickness = 0.4%
- Set: Clipping = Viewport


### Full Domain Emission Source Label Locations

| Label | x [m] | y [m] | Text Anchor Location |
|------:|:-----:|:-----:|:---------------------|
|   A   |  705  |  585  |    Headline-Left     |
|   B   |  660  |  735  |    Headline-Left     |
|   C   |  425  |  575  |    Headline-Left     |
|   D   |  475  |  825  |    Baseline-Right    |
|   E   |  825  |  775  |    Headline-Left     |
|   F   |  615  |  825  |    Headline-Right    |
|   G   |  675  |  925  |    Baseline-Right    |
|   H   |  495  |  725  |    Headline-Right    |
|   I   |  585  |  615  |    Headline-Left     |
|   J   |  785  |  635  |    Headline-Left     |


### Zoom #1 Emission Source Label Locations

| Label | x [m] | y [m] | Text Anchor Location |
|------:|:-----:|:-----:|:---------------------|
|   A   |  655  |  600  |    Headline-Left     |
|   C   |  410  |  620  |    Headline-Left     |
|   D   |  495  |  810  |    Baseline-Right    |
|   H   |  520  |  700  |    Headline-Right    |
|   I   |  570  |  630  |    Headline-Left     |


### Zoom #2 Emission Source Label Locations

| Label | x [m] | y [m] | Text Anchor Location |
|------:|:-----:|:-----:|:---------------------|
|   H   |  526  |  685  |    Headline-Right    |
|   I   |  563  |  638  |    Headline-Left     |


## 19 October 2013 (Saturday)
- Added tasks from paper notebook to task list
- Combined the multi-source regularization appendices into a single properly formated appendix
- Worked on revision comments of chapter 5

## 20 October 2013 (Sunday)
- Calculated the error on the source location

### NO OBSERVATIONAL NOISE (location error [m])
--------------------------------------------------
| S |  B = 0 |  B = 1 | B = 10 | B =100 | B=1000 |
|:-:|:------:|:------:|:------:|:------:|:------:|
| A |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
| B |   0.00 |   0.00 |   0.00 |   0.00 |  21.95 |
| C |   9.82 |   9.82 |   9.82 |  14.70 |  14.70 |
| D |   4.50 |   4.50 |   4.49 |   4.49 |   4.49 |
| E |   0.00 |   0.00 |   0.00 |   4.20 |   4.20 |
| F |   0.00 |   0.00 |   0.00 |   3.79 |   0.00 |
| G |   0.00 |   0.00 |   0.00 |   8.40 |  15.88 |
| H |   3.93 |   3.93 |   3.93 |   6.35 |   6.35 |
| I |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
| J |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
--------------------------------------------------

### 10% OBSERVATIONAL NOISE (location error [m])
--------------------------------------------------
| S |  B = 0 |  B = 1 | B = 10 |  B=100 | B=1000 |
|:-:|:------:|:------:|:------:|:------:|:------:|
| A |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
| B |   0.00 |   0.00 |   0.00 |   0.00 |  21.95 |
| C |   9.82 |   9.82 |   9.82 |  14.70 |  14.70 |
| D |   4.50 |   4.50 |   4.49 |   4.49 |   4.49 |
| E |   0.00 |   0.00 |   0.00 |   7.20 |   4.20 |
| F |   0.00 |   0.00 |   0.00 |   3.79 |   0.00 |
| G |   0.00 |   0.00 |   0.00 |   8.40 |  15.88 |
| H |   3.93 |   3.93 |   3.93 |   6.35 |   6.35 |
| I |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
| J |   0.00 |   0.00 |   0.00 |   0.00 |   0.00 |
--------------------------------------------------


## 21 October 2013 (Monday)

- In addition to finding the location of the peak volumetric emission rate, I also need to quantify how diffuse these emission sources are
- Find the area of half peak volumetric emission rate.


### Single Source, NO OBSERVATIONAL NOISE
------------------------------------------------------------------------------
|                     |   B = 0  |   B = 1  |  B = 10  |  B = 100 | B = 1000 |
|--------------------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|  Location Error [m] |        0 |        0 |        0 |        0 |        0 |
| Half-Max Area [m^2] |      187 |      187 |      375 |      743 |     1182 |
------------------------------------------------------------------------------


### Single Source, NO OBSERVATIONAL NOISE
------------------------------------------------------------------------------
|                     |   B = 0  |   B = 1  |  B = 10  |  B = 100 | B = 1000 |
|--------------------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|  Location Error [m] |        0 |        0 |        0 |        0 |        0 |
| Half-Max Area [m^2] |      187 |      187 |      375 |      743 |     1182 |
------------------------------------------------------------------------------


### Multi-Source, NO OBSERVATIONAL NOISE (half-max area [m^2])
------------------------------------------------------------
| S |   B = 0  |   B = 1  |  B = 10  |  B = 100 | B = 1000 |
|:-:|:--------:|:--------:|:--------:|:--------:|:--------:|
| A |      514 |      514 |      539 |      743 |     1182 |
| B |      264 |      264 |      264 |      549 |      267 |
| C |     2856 |     2985 |     3638 |     5717 |     6934 |
| D |      836 |      836 |      933 |     1505 |     3194 |
| E |      866 |      866 |      916 |     2314 |     9058 |
| F |      130 |      130 |      220 |      469 |     1085 |
| G |     1270 |     1310 |     1444 |     2772 |     6364 |
| H |      220 |      220 |      230 |      608 |      691 |
| I |      377 |      377 |      403 |      626 |     1535 |
| J |      641 |      641 |      862 |     2266 |     4219 |
------------------------------------------------------------

### Multi-Source, 10% OBSERVATIONAL NOISE (half-max area [m^2])
------------------------------------------------------------
| S |   B = 0  |   B = 1  |  B = 10  |  B = 100 | B = 1000 |
|:-:|:--------:|:--------:|:--------:|:--------:|:--------:|
| A |      489 |      489 |      539 |      743 |     1182 |
| B |      264 |      264 |      264 |      549 |      267 |
| C |     2725 |     2842 |     3690 |     5336 |     7052 |
| D |      836 |      836 |      866 |     1489 |     3065 |
| E |      825 |      866 |      898 |     2512 |     9418 |
| F |      130 |      130 |      220 |      469 |     1065 |
| G |     1341 |     1375 |     1594 |     2908 |     6307 |
| H |      220 |      220 |      230 |      618 |      681 |
| I |      377 |      377 |      377 |      626 |     1531 |
| J |      641 |      641 |      862 |     2268 |     4218 |
------------------------------------------------------------

- Removed gradient sections to an appendix, since it makes little sense to compare gradients between test cases.  They are only meaningful to compare iterations within a single test case.


## 23 October 2013 (Wednesday)

- Accepted all revisions to chapter 4.
- Started assembling all sections into a single document.