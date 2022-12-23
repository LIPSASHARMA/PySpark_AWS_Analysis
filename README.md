# PySpark_AWS_Analysis
UoT Module for AWS and PySpark


## Overview of the analysis:

The purpose of this analysis is to analyze the Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- Create RDS database and add tables in PostGreSQL DB
- Use Amazon Review datasets and extract it into a DataFrame
- Extract and transform the DataFrame into four separate DataFrames that match the table schema in PostGreSQL.
- Upload the transformed data into the appropriate tables and run queries

## How many Vine reviews and non-Vine reviews were there?
Total Vine reviews: 613
Total non-Vine reviews: 64968

![ScreenShot](https://github.com/LIPSASHARMA/PySpark_AWS_Analysis/blob/main/images/vine_vs_non-vine_count.png   )

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
5-star vine reviews: 222
5-star non-vine reviews: 30543

![ScreenShot](https://github.com/LIPSASHARMA/PySpark_AWS_Analysis/blob/main/images/vine_5-star_vs_non-vine_5-star_count.png)

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Paid 5-star reviews percentage: 36.22 %
Non-paid 5-star reviews percentage: 47.01 %

![ScreenShot](https://github.com/LIPSASHARMA/PySpark_AWS_Analysis/blob/main/images/vine_vs_non-vine_percentage.png)

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

Comparing the results of paid (i.e. Vine program) versus the non-paid program (i.e. Non-vine program), we see that there were 47% that were not part of the Vine program and they provided a 5-star ratings. There were 36% of people who provided 5-star ratings and they participated in the Vine program. So, it is evident that there was less possibility of bias in these reviews. 

