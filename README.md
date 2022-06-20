# Amazon_Vine_Analysis

## Overview of Analysis

The following challange was a too show the cooperation between Google Colab, PySpark, SQL, and AWS to create a dataframe from the Amazon vine program service that has databases that shows paid and non paid reviews from this vine program. There were over 50 databses to choose from in this challange the one that was used was the Furniture reviews. The dataframes were created in a *.ipynb* file using Google Colab. Then we created a AWS RDS server and connected it to our PGAdmin and used the schema for our table and then imported our dataframes into our SQL databse.

## Results

> - How many Vine reviews and non-Vine reviews were there?

There are quite a bit of a difference between the Vine, and non-vine reviews, the table below shows that there are 2,775 Vine reviews. While the there are 789,338 non-Vine reviews that is quite a difference.

![VineRev](https://user-images.githubusercontent.com/97326526/174493145-9c5cf4d6-25d6-483d-8325-a9cd89e4108e.JPG)

> - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Again the difference between the 5 star reviews for vine and non-vine reviews. The vine reviews that were 5 stars is 1,356, while the non-Vine reviews that were 5 stars is 446,360.

![Vine5Rev](https://user-images.githubusercontent.com/97326526/174493245-06f19a30-c7a4-44d3-8ab5-72c648c5d9e6.JPG)

> - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

As you can see from the chart above the 5 star vine review percentage is 0.3%, while the 5 star non-Vine percentage is 99.7%. 

## Summary

In this summary I will explain wheather there is any positivity bias for reviews in the Vine program. I do not believe there is, we can compare between vine reviews, and 5 star vine reviews. If we do this it will be 2,775 for all vine reviews and 1,356 for 5 star vine reviews. If we subtract 5 star vine reviews from all vine reviews it is a difference of 1,419, and then if we use this total of 1,419 and divide by the all vine reviews which is 2,775 and then multiply the total by 100 we can get the percentage of how many of these reviews were 5 stars which is 51%. We can see half of these reviews are 5 star reviews, but we can now compare this percentage by how many non-vine reviews were 5 star reviews.We do the same as we did with the vine reviews. We start with 5 star non-vine reviews which is 446,360 and subtract that from all non-vine reviews which is 789,338 and get a difference of 342,978. We then take the total number which is 342,978 and divide it by all non-vine reviews which is 789,338 and multiple the total by 100 and get 44%. So now we can compare the percentages to see 
