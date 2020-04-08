![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Introduction to Tableau

## Introduction

In this lab, we will practice loading data into Tableau, inspecting and modifying data types, and creating tabular views with metrics based on the information contained in the data set. We will be working with a COVID-19 dataset found in the data folder.

If you get stuck on any of the tasks in this lab, you can reference the excellent training video resources provided on the [Tableau website](https://www.tableau.com/learn/training). We have also referenced specific articles on topics such as binning variables and creating aliases that should be helpful in completing this lab.

## Getting Started

To complete this lab, follow each of the steps below.

1. Download the clean-covid-data.csv file from the data folder.
2. Launch the Tableau Public application.
3. Import the data set from your computer into Tableau.
4. Create new worksheets with tabular views for each of the following metrics.
    - Total Confirmed Cases(rows) for countries with more than 50,000 cases (columns) with color showing Total Deaths.
    - Confirmed cases (bubble size), Total Deaths (bubble color) and Median Age in a Packed Bubble Chart with labels for each country with greater than 50,000 cases.
    - Line plot for all countries (color) with greater than 50,000 cases with Days Since First Case on the x-axis and Confirmed Cases on the y-axis.  Include an animation to plot the data day by day.
    - Histogram with Countries and 3 measures including Total Confirmed, Total Deaths, Total Recovered (columns) and those measured values on the y-axis.
    - Lineplot with cumulative measures including Total Confirmed, Total Deaths and Total Recovered (rows) each day (columns).
    - Create a calculated field for the Recovery Rate in % and then use a colored map to visualize it (include labels when a country is selected).
    - Create a calculated field for the Death Rate in % and then use a colored map to visualize it (include labels when a country is selected.
6. Save your work to Tableau Public, ensure that your workbook is viewable, and copy the URL for the workbook into the deliverables file for this lab. It might take several minutes for this workbook to save to Tableau Public due to the number of records in the data set.

## Deliverables

- `main.txt` file with a link to your Tableau Public workbook.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

- [Tableau Training Videos](https://www.tableau.com/learn/training)
