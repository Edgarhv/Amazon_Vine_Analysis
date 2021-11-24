# Amazon_Vine_Analysis
![Img](https://github.com/Edgarhv/Amazon_Vine_Analysis/blob/0e96d532a3d57c200b5f83c74ad61491d4678323/AfraidWideImperialeagle-mobile.gif)
### Source: https://gfycat.com/afraidwideimperialeagle-smashgifs-ssmb
# Overview of the analysis

The purpose of this project was to make an analysis of Amazon reviews. Furthermore, it was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. The main reason for this new task is to check if there is any bias towards favorable reviews from the paid Vine members in the available data.

Out of the 50 datasets of product categories available to choose from, I chose to analyze reviews in the Camera category - high-value, technical products requiring experience and knowledge to effectively review. The initial ETL portion of the project was conducted, as proscribed, using AWS, PostgreSQL, and PySpark in Google Colab. The data analysis segment was conducted using PySpark and Google Colab.

# Results
-------------------------

## Paid Vine Reviews.
![Img](https://github.com/Edgarhv/Amazon_Vine_Analysis/blob/e68c28dac9c26c169fc9e6e5ec6689437cc1d949/Images/Paid_Vines.png)

* How many Vine reviews reviews were there?
#### 266
* How many Vine reviews were 5 stars? 
#### 125
* What percentage of Vine reviews were 5 stars? 
#### 46.99 %
![Img](https://github.com/Edgarhv/Amazon_Vine_Analysis/blob/a51b8f1f80a08874bf7ac3843e3e9c39a23f11e0/Images/Vpaid.png)
-------------------------

## Upaid Vine Reviews.
![Img](https://github.com/Edgarhv/Amazon_Vine_Analysis/blob/3e09310a5fc9da4f7798a84ea580799d9da2844c/Images/Unpaid_vines.png)
* How many non-Vine reviews were there?
#### 38829
* How many non-Vine reviews were 5 stars?
#### 18246
* What percentage of non-Vine reviews were 5 stars?
#### 46.99%
