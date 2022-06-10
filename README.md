# Amazon_Vine_Analysis

## Table of Contents
- [Overview of Project](#OverviewProject)
- [Results](#Results)
- [Summary](#Summary)
- [Resources](#Resources)

## <a name="OverviewProject"></a>Overview of Project

We were tasked in analyzing customer reviews in the Amazon website, from a product of our liking [[1]](#1). We picked the cameras reviews. We first uploaded and cleaned the data into out AWS RDS - SQL data base  [[2]](#2). Then we extraced some of the data resulting from out data bases (the Vine Table [[4]](#4)) and used Pandas, to analyze if the Amazon Vine program creates a bias towards better reviews [[3]](#3).

## <a name="Results"></a>Results

In our analysis we found the following results: 

### Paid Vine program members reviews:
- Number of reviews: 580 reviews
- Number of 5-star reviews: 246 reviews
- Percentage of 5-star reviews: 42.4%

### Non-Vine reviews: 
- Number of reviews: 47,703 reviews
- Number of 5-star reviews: 23,849 reviews
- Percentage of 5-star reviews: 49.97%

### Overall Results 
- Total Number of reviews: 48,283 reviews
- Total Number of 5-star reviews: 24,095 reviews
- Percentage of 5-star reviews: 49.90%
- Percentage of Vine Member Reviews: 1.20%
- Percentage of Non-Vine Reviews: 98.80%


<p align="center"> <img src="Resources/Vine_Results.png" width ="70%" alt="Vine_Results"> </p>
<p align="center"> Figure 1: Vine Program Reults</p> 



## <a name="Summary"></a> Summary

This analysis is only of one of the 

## <a name="Resources"></a>Resources

<a name="1">[1]</a> [Amazona Reviews - we picked camera](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

<a name="2">[2]</a> [Code - Amazon Camera Reviews Data Base Set Up](https://github.com/tamiespinosa/Amazon_Vine_Analysis/blob/4da507d96a83990c9a758a4ec92a7e7c90434aff/Amazon_Reviews_ETL.ipynb)

<a name="3">[3]</a> [code - Vine Table Analysis](https://github.com/tamiespinosa/Amazon_Vine_Analysis/blob/4da507d96a83990c9a758a4ec92a7e7c90434aff/Vine_Review_Analysis.ipynb)

<a name="4">[4]</a> [Vine Data](https://github.com/tamiespinosa/Amazon_Vine_Analysis/blob/4da507d96a83990c9a758a4ec92a7e7c90434aff/Resources/vine_table.csv)

[5] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
