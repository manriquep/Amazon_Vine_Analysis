# **Amazon_Vine_Analysis**

**Overview**

This analysis combined Amazon product review data, AWS, Google Collab, and PGAdmin using Postgres SQL. The purpose of this analysis was to determine if there was a difference in paid (called the Vine program) vs. unpaid 5 star reviews given to products in the electronic category. The dataset was filtered to view only 5 star results and reviews that were found to be helpful to the community of 20 or more votes with a ratio of greater than or equal to 0.5 for helpful votes to total votes.

**Results**

From the extracted dataset in the video games, two datasets were created, paid vs. unpaid Amazon reviews.

- There were 94 total paid (Vine) reviews and 40,471 total unpaid reviews I analyzed.
- There were 48 paid (Vine) 5 star reviews and 15,663 unpaid 5 star reviews.
- The percentage for paid (Vine) 5 star reviews to total paid reviews was 51.07% and the percentage for unpaid 5 star reviews to total unpaid reviews was 38.80%.

![image](https://user-images.githubusercontent.com/74743437/120904518-b0a53b00-c61a-11eb-975f-f98e41f3432d.png)

**Summary**

This analysis shows that unpaid reviews had a lower percentage of 5 star reviews. One additional test I could do to make sure there was no positivity bias would be to filter results based on viewing reviews only for verified purchases as this would be an additional step to make sure the reviewer actually purchased the product and did not just leave a review.
