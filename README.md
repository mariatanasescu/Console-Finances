# Console-Finances

Week 4 java challenge

## Description

We are given an array with dates and amounts or corresponding profits and asked to perform various tasks on the array.

## Whole Task

Instructions
Create a new GitHub repo called Console-Finances. Then, clone it to your computer.

Copy the starter files into your local git repository.

You have been given a dataset composed of arrays with two fields: Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

The total number of months included in the dataset.

The net total amount of Profit/Losses over the entire period.

The average of the changes in Profit/Losses over the entire period.

You will need to track what the total change in profits is from month to month and then find the average.

(Total/Number of months)

The greatest increase in profits (date and amount) over the entire period.

The greatest decrease in losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

Financial Analysis
----------------------------
Total Months: 25
Total: $2561231
Average  Change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)

## Licence

None

## New Concepts Learned

xxx = xxx.toFixed(2) => rounds up to first twwo decimals

let maxXxx = Math.max(...xxx); => Math.max picks the largest of an array of numbers and ... spreads out an array so to speak