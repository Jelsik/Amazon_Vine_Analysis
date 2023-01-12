# Amazon Vine Analysis

## Assignment Purpose

The purpose of this assignment was perform analysis and test for bias of product reviews.
Firstly, a database of reviews was aquired from Amazon, and secondly this data was broken
down into a split between reviews that were part of the Vine program, and those that were not.

## Results

Sample Dataframe:
!["Sample"](https://github.com/Jelsik/Amazon_Vine_Analysis/blob/main/dataframe.PNG)

After splitting the data down, we were left with two chunks:

The Vine reviews
!["Vine"](https://github.com/Jelsik/Amazon_Vine_Analysis/blob/main/vineData.PNG)

And

The Non-Vine reviews
!["Non-Vine"](https://github.com/Jelsik/Amazon_Vine_Analysis/blob/main/nonVineData.PNG)

From this we observe:

* There were 94 Vine reviews
	* 48 of which were Five-Star
	* 51% of Vine reviews were Five-Star
* There were 40471 non-Vine reviews
	* 15663 of these were Five-Star
	* 39% of non-Vine reviews were Five-Star

### Summary

From the data gathered, there is evidence to support the theory that there may be some positivity bias for
reviews in the Vine program: 51% compared to 39% of non-Vine. There is a difference of 13% between the two.
However, the vast difference in the number of reviews between Vine and non-Vine reviews cannot be ignored. 
In order for a more concrete analysis to be made, filtering the dataset by a higher total votes number could help even the numbers out theoretically.
In addition more categories of reviews could be brought in to have their percentage ratios measured.
