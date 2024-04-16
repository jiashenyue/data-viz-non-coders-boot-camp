# Replicate visualization examples from The Economist with Excel

*Shenyue Jia*
[jiashenyue.info](https://www.jiashenyue.info/)

## Bar plot example
### Difference between the default from Excel and The Economist example

- Below is a bar plot showing the parts sourced from China and the U.S. from The Economist

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/The-Economist-example.png)

- Below is a bar plot using the same data but generated with the default set up from MS Excel

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/bar-plot-excel-example.png)

- The first example is more compact and **easier to read**

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

## Add bar titles

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

## Update bar plot title

- Select Chart Title box and enter `=` in formula bar to update plot title

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/20-bar-update-plot-title.png)

