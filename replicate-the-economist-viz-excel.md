# Replicate visualization examples from The Economist with Excel

*Shenyue Jia*
[jiashenyue.info](https://www.jiashenyue.info/)

## Bar plot example
### Difference between the default viz from Excel and The Economist example

- Below is a bar plot showing the parts sourced from China and the U.S. from The Economist

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/The-Economist-example.png)

- Below is a bar plot using the same data but generated with the default set up from MS Excel

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/bar-plot-excel-example.png)

- The first example is more compact and **easier to read**

### Obtain data for practice

- Download a Excel spreadsheet from [this link](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/tree/main/data)

### Create this bar plot using Excel

- Insert a bar plot with 100% stacked bar
  - Select data from cell `A5` to `C10`

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/01-bar-plot-select-type.png)

- Reorder Y-axis to keep the labels the same as our example

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/02-bar-reorder-y-axis.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/03-bar-reorder-y-axis-reverse.png)

- Delete unnecessary elements in the bar
  - Select all bars and press `delete` on your keyboard
  - 
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/04-bar-delete-minor-y-axis.png)

  - Select all x-axis labels and press `delete` on your keyboard
    
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/05-bar-delete-x-labels.png)

- Move legend from bottom to top

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/06-bar-mv-legend-top.png)

- Change colors for different countries

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/07-bar-change-color-cntry.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/08-bar-change-color-fin.png)

### Change bar labels

- Add data labels
  - Select a category (United States) and right-click to open **Add Data Labels** menu
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/09-bar-add-data-labels.png)

- Align data labels
  - Select a category (United States) and right-click to open **Format Data Labels** menu
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/10-bar-format-data-labels.png)

  - Align the labels for the United States to the right (inside end)
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/11-bar-format-data-labels-inside-end.png)

  - Align the labels for China to the left (inside base)
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/12-bar-format-data-labels-inside-base.png)

- Format label fonts
  - **Bold** font face for both countries
  - White color for China (shows better on a dark background)
  - Dark grey for United States (shows better on a light background)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/13-bar-format-label-font.png)

- Remove x-axis labels as well since we will add the labels above the bars
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/14-bar-rm-y-axis-labels.png)

### Add bar titles

- **Select the bar plot first**
- Insert a text box from **Insert** tab
  - This will allow the text box to go along with the plot we created
    
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/15-bar-insert-textbox.png)

- Select the text box we just inserted
- In the formula bar, enter `=` and select the `Battery cells` (cell `A6`) as the value for the content
  - This can ensure the bar plot is updated when we have a new bar title

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/16-bar-obtain-bar-labels.png)

- Select the text box we just updated and hold `Ctrl` key
- Drag the box to obtain a new text box with the formula set up

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/17-bar-duplicate-titles.png)

- Update the formula for this box to cell `A7`

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/18-bar-update-duplicated-title-box.png)

- Finish updating all bar titles

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/19-bar-updated-bar-title.png)

### Update bar plot title

- Select Chart Title box and enter `=` in formula bar to update plot title

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/20-bar-update-plot-title.png)

## Dumbbell chart example

### Why we need this?
- A simple and intuitive way to visualize the change (notice the use of color as well)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/23-dumbbell-example.png)

- Remember change can go the other way (worse now, better before)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/24-dumbbell-negative.png)

- Let's use our data in Sheet `Dumbbell` to produce a chart like this

### Create a *scatterplot* to start with

- Why we need to start with a scatterplot?
  - Best solution to create a chart showing the differences between numbers

- Create a new column for y-position for the scatterplot (value 1-8)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/25-dumbbell-add-y-position.png)

- Insert a basic scatterplot with `y-position` as Y-axis

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/26-dumb-insert-scatter.png)

- Right-click over the empty scatterplot to **Select Data**

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/27-dumb-select-data-scatter.png)

### Select correct cells for X, Y, and Series Name

- Select `B3` (**Engagement Score in 2023 (%)**) as `Series Name`
- Select `B4` to `B11` as `X Values`
- Select `D4` to `D11` as `Y Values`
  - At the end, we need to use the **Department**, but for a scatterplot, we need numbers
  - Therefore, we are using `y-position` column from 1-8 for `Y Values`

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/28-dumb-add-series.png)

- Replicate the steps above to add another series of **Engagement Score in 2024 (%)** (column C)
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/29-dumb-series-setup.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/30-dumb-add-2nd-series.png)

### Add connecting lines between two series

- Use connecting lines to indicate the difference between two series
- Calculate the difference between **Engagement Score in 2024 (%)** and **Engagement Score in 2023 (%)**
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/31-dumb-diff-23-24.png)

- We will insert error bars for our **after** series (**Engagement Score in 2024 (%)**)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/32-dumb-insert-error-bars.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/33-dumb-error-bars-inserted.png)

- Delete the vertical error bars and keep the horizontal ones
  - Press `Delete` button on your keyboard to remove vertical error bars


![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/34-dumb-delete-ver-err-bars.png)

- We will format the horizontal error bars so that the tail can cross over the **before** and **after** series

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/35-dumb-format-err-bars.png)

- We do not use cap
- We will also specify the **negative error** with the `Difference` column we just calculated

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/36-dumb-minus-err-bars.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/37-dumb-specify-err-val.png)

- Connecting lines created between the two years

    - Specify the value for negative error bars in **Customize** to make sure the error bar represents the difference correctly

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/38-dumb-specify-neg-err-val.png)

- Two years are connected in our chart
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/39-dumb-connecting-line-done.png)


### Update labels on Y-axis

- Why we need to add another series to obtain the correct Y-axis label?
  - Since we are using a scatterplot rather than a bar plot, we do not have the option to update Y-axis labels
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/40-dumb-y-axis-data.png)

- We can add a series with all x values = 0 and `y-position` as y values, then add labels next to points from this new series to achieve our goal

- Add a new column for x values
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/41-dumb-add-zero-xval.png)

- Right-click over the chart and select add a new series
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/42-dumb-add-new-series.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/43-dumb-finish-new-series.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/44-dumb-finish-new-series-2.png)

- After adding a new series, we can right-click over this series and select **Format Data Labels**

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/45-dumb-add-data-labels.png)

  - Change label position from **right** to **left**
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/46-dumb-change-label-pos.png)

  - Change label values to `Department`
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/47-dumb-change-label-vals.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/48-dumb-change-label-vals-2.png)

  - Make sure we also *deselect Y value* from **Format Data Labels** panel
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/49-dumb-deselect-y-val.png)

- Continue formatting y-labels
  - We can also remove the unnecessary original numeric labels on Y-axis and resize the chart to show the y-labels
    - To resize the chart, select the char plotting area

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/50-dumb-rm-unneed-labels.png)

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/51-dumb-resize-chart.png)

  - We can also set the fill color of the label series to transparent and remove any outline
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/52-dumb-rm-color-outline.png)

### Finalize formatting the chart

- Use a much lighter color for the major guidelines for x and y-axis

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/53-dumb-change-guidelines-color.png)

- Change fill color and size of markers

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/54-dumb-format-markers.png)

- Change color and size for error bars (connecting lines b/w two markers)
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/55-dumb-format-error-bars.png)

- Add chart title

- Change text color to match the markers in our scatterplot

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/56-dumb-format-title-colors.png)

### Save chart as a picture for future use

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/62-save-excel-pic.png)
