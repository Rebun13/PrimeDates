# PrimeDates

## Description

Given two dates each in the format dd-mm-yyyy, you have to find the number of lucky dates between them (inclusive). To see if a date is lucky,

- First, sequentially concatenate the date, month and year, into a new integer _x_ erasing the leading zeroes.
- Now if _x_ is divisible by either _4_ or _7_, then we call the date a lucky date.

For example, let's take the date "02-08-2024". After concatenating the day, month and year, we get _x = 2082024_. As _x_ is divisible by _4_ so the date "02-08-2024" is called a lucky date.

## Prints

For each test case, print a single integer the number of lucky dates between _u_ and _v_ in a single line.

## Input

The only line of the input contains two strings _u_ and _v_ denoting the two dates following the format dd-mm-yyyy. Consider, _d_ is the day number, _m_ is the month number and _y_ is the year number.
