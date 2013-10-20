# Notebook 2013-10

This is notebook comprises my notes for October 2013.

## Table of Contents

- [Tasks](#tasks)
  - [Items to address in all Chapters](#items-to-address-in-all-chapters)
  - [Items to address in Chapter 5](#items-to-address-in-chapter-5)
- [18 (Friday)](#18-october-2013-friday)


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