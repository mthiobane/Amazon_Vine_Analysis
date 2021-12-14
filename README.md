# Amazon_Vine_Analysis

## Overview of the analysis: 
 The purpose of this analysis is to stydy the reviews written by members of the paid Amazon Vine program and determine if there is any bias toward favorable reviews from Vine members in the dataset available
For my case I choose to conduct this study on the US wireless by using AWS, postgresql, and PySpark in Google Colab.
## Results: 
* How many Vine reviews and non-Vine reviews were there?
The global number of reviews is about 65 547, but a small number of then is paid, around 0.953 for 613 reviews. The large majority is unpaid for 64 934 reviews.
## Total number of reviews![Total number of reviews](https://user-images.githubusercontent.com/89410157/145908199-61c5798e-e81c-4bfb-9276-832f4692e222.png)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
The number of 5 starts is around 46.915% for 30 752 reviews.
## Number of Five Stars reviews ![Number of Five Stars reviews](https://user-images.githubusercontent.com/89410157/145913706-4c47c7c7-b9ce-43f9-bd84-4c3bdc97bcc7.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Out of the 613 paid reviews 222 are 5 starts for 36.215%, and regarding the 64 934 unpaid reviews 52.983% are 5 starts for 34 404 reviews.

## Percentage of 5 stars ![Percentage of 5 stars](https://user-images.githubusercontent.com/89410157/145913992-4b394a49-0792-4b08-bc55-acaaf0864e66.png)

## Summary: 
Based on our finding we can say that the 5 stars reviews are not the majority in the paid review. So, the tendency is that the review tend to be critical. To support this statement, we could take the “review_body” and analyze the Term Frequency-Inverse Document Frequency Weight and build and pipeline into to run the Model and determine the tendency of the reviews. 

