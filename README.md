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

As you can see from the 
