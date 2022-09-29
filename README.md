# Amazon_Vine_Analysis

## Overview of the analysis:
For this project you were supplied with and had access to approximately 50 datasets of Amazon.com reviews. Each dataset contained reviews of a specific product, which ranged across all of Amazon's product categories such as "Toys and Games", or "Home and Office". For this specific analysis the "Sports" category was chosen. PySpark was used to extract that specific dataset, transform it, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was used to determine if there is any bias toward favorable reviews from Vine members in the Sports dataset.

<br>

## Results:

### How many Vine reviews and non-Vine reviews were there?

![Total Vine Reviews](Resources/Vine_reviews.png)
<br>
<sub>Total Vine Reviews</sub>

- As is shown in the example there were 334 total reviews done by Vine program personel.

<br>

![Total Non-Vine Reviews](Resources/NonVine_reviews.png)
<br>
<sub>Total Non-Vine Reviews</sub>

- In contrast, as is shown, there were 61,589 total reviews done by non-Vine program personal.

<br>

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5-star Vine Reviews](Resources/5star_Vine_reviews.png)
<br>
<sub>5-star Vine Reviews</sub>

- Out of the 5-star reviews, 139 of them were Vine reviews.

<br>

![5-star Non-Vine Reviews](Resources/5star_NonVine_reviews.png)
<br>
<sub>5-star Non-Vine Reviews</sub>

- For Non-Vine reviews there were 32,660 5-star reviews.

<br>

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Percentage of Vine Reviews](Percentage_Vine_reviews.png)
<br>
<sub>Percentage of Vine Reviews</sub>

- The percentage of Vine reviews that were 5 star is ~42%.

<br>

![Percentage of Non-Vine Reviews](Percentage_NonVine_reviews.png)
<br>
<sub>Percentage of Non-Vine Reviews</sub>

- While the percentage of Non-Vine reviews that were 5-star is ~53%.

<br>
<br>

## Summary:

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
