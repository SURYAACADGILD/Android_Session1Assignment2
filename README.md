# Android_Session1Assignment2
Assignment - 2  Session 1 – Introduction to Working with R   Problem Statement  1. What should be the output of the following Script?  v &lt;- c( 2,5.5,6)  t &lt;- c(8, 3, 4)  print(v%/%t)   Answer:- > v&lt;- c(2,5.5,6) > t&lt;- c(8,3,4) > print(v%/%t) [1] 0 1 1  2. You have 25 excel files with names as xx_1.xlsx, xx_2.xlsx,……..xx_25.xlsx in a dir.  Write a program to extract the contents of each excel sheet and make it one df.   Answer:- Extract xx_1.xlsx library(data.table) data1 = read.table("xx_1.xlsx",header=T, sep=',') View(data)  Extract xx_2.xlsx library(data.table) data1 = read.table("xx_2.xlsx",header=T, sep=',') View(data)  . . . . . .  Extract xx_25.xlsx library(data.table) data1 = read.table("xx_25.xlsx",header=T, sep=',') View(data)  3. If the above 25 files were csv files, what would be your script to read?  Expected Output   Answer:-  Extract xx_1.csv library(data.table) data = read.table("xx_1.csv",header=T, sep=',') View(data)  Extract xx_2.csv library(data.table) data = read.table("xx_2.csv",header=T, sep=',') View(data) . . . . . . Extract xx_25.csv library(data.table) data = read.table("xx_25.csv",header=T, sep=',') View(data)
