# Reviews are KING
**Team Members:** Shengzhao LEI, Tao SUN, Xiangzhe MENG

# Abstract
Reviews and ratings are everything on Amazon. One of the main reasons why customers are attracted towards Amazon, is the presence of reviews and ratings about that product, which basically helps them understand about almost every detail of the product. But, how people review? Tons of reviews on Amazon make itself as the best dataset for language analysis which is exactly what we are eager to do.

Our project, based on the datasets of Amazon reviews, focuses not only on the basics of reviews and rating on Amazon, but also on the relationship between these two. With interactive and intuitive visualization, we are going to show you how people’s ratings and styles of review vary in different categories of books and also the over-year changings. We want to study whether or not the rate people score has connection with what they write in review. Basic machine learning and natural language processing methods are to be expected in the project.

# Research questions
**Facile analysis:**
* How average rating varies between different categories?
* Chronologically, how the ratings of books change?
* How to label or categorize or even score the reviews? e.g. How to define positive and negative reviews? (Sentiment analysis)
* Can we get the keywords of reviews of each category? How they change over years?

**Comprehensive analysis:**
* For each rating, what’s the style of people’s review (e.g. length of reviews, type of words used, concerning points, etc.)? 
* Is there any inner connection between one’s rating of a book and his/her review? How can we reasonably vectorize review to make it suitable for analytical handling? (Try to make use of spectral graph theory and machine learning)
* Based on the review and rating, is it possible to automatically generate the summary? Maybe with the key words we have already found. Or, maybe it’s the stage for neural network.

# Dataset
**Name:** Amazon product data

**Source:** http://jmcauley.ucsd.edu/data/amazon/

**Description:**
This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014.

This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).

In the dataset of reviews, format is one-review-per-line in (loose) json. One typical review has following attributes:
* reviewerID - ID of the reviewer
* asin - ID of the product
* reviewerName - name of the reviewer
* helpful - helpfulness rating of the review
* reviewText - text of the review
* overall - rating of the product
* summary - summary of the review
* unixReviewTime - time of the review (unix time)
* reviewTime - time of the review (raw)

In the dataset of metadata, format is one-product-per-line in json and following attributes of products are included:
* asin - ID of the product
* title - name of the product
* price - price in US dollars (at time of crawl)
* imUrl - url of the product image
* related - related products (also bought, also viewed, bought together, buy after viewing)
* salesRank - sales rank information
* brand - brand name
* categories - list of categories the product belongs to

**Usage:**
This project will mostly use two subsets of the Amazon reviews dataset: Books and Kindle Store. We are going to use reviews dataset for rating and review analysis and product metadata dataset for book categorization and classification. With the help of attribute asin, we can easily find the connections between two datasets.

The dataset of reviews provides us with the text of review, rating information, and importantly, the time of review, which is good for chronological analysis. The dataset of metadata provides us with various ways for book classification: price, brand and category. The data of sales rank is also helpful to determine the popularity and sales of one book.

# A list of internal milestones up until project milestone 2
We plan to schedule our project on the following big steps:
* 01/11/2017 - 15/11/2017: data collection and wrangling
* 15/11/2017 - 28/11/2017: Data analysis & Key point study
* 15/11/2017 - 19/12/2017: Data Visualization & Website
* 28/11/2017 - 19/12/2017: Conclusion & Result presentation
* 19/12/2017 - 29/01/2018: Poster & Presentation
