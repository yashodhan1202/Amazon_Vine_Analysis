# Amazon_Vine_Analysis

# Overview of the analysis
In this project we had to choose from a list of datasets which had the same column names. I have picked a data set from amazon reviews regarding video games and used Pyspark to perform the ETL process by extracting the data, transforming the data and connecting to the RDS database that was generated through the AWS webserver. With analysing the reviews, my goal is to try and determine if there is favorable review bias from the Vine members of our data set.

# Results:

# How many Vine reviews and non-Vine reviews were there?
There were total 40,565 reviews in the filtered dataset out of which 40,471 were non-vine reviews and 94 were vine reviews

# How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were total 15,711 5-star reviews, out of which 15,663 were non-vine and 48 were vine

# What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
38.2% of the five star reviews were vine
38.9% of the five star reviews were non-vine

# Summary:

There does not appear to be any sort of positivity bias because the percentages mentioned above are very similar at 38%. To conclude the analysis the vine program does not show any bias.
