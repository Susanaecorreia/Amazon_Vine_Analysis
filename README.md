# Amazon_Vine_Analysis


# Overview of the analysis: 

In this project I have picked a data set from amazon reviews regarding books and used Pyspark to perform the ETL process by extracting the data, transforming the data and connecting to the database that was generated for me through the AWS webserver. With the reviews my goal is to try and determine if there is favorable review bias from the Vine members of our data set.


# Results: 

How many Vine reviews and non-Vine reviews were there?

- Total Vine Reviews: 543
- Total non-Vine Reviews: 112803

https://github.com/Susanaecorreia/Amazon_Vine_Analysis/blob/main/TotalReviews.png



How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 5 Star Vine Reviews: 241
- 5 Star non-Vine Reviews: 52195

https://github.com/Susanaecorreia/Amazon_Vine_Analysis/blob/main/5StarReviews.png



What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- Percentage of Vine Reviews: 44%
- Percentage of non-Vine Reviews: 46%

https://github.com/Susanaecorreia/Amazon_Vine_Analysis/blob/main/PercentReviews.png


# Summary: 

It does not appear to be any sort of positivity bias because the percentages shown above are very similar: 44.38% for paid reviews and 46.27% for unpaid reviews.
