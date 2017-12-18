# Reviews are KING
**Team Members:** Shengzhao LEI, Tao SUN, Xiangzhe MENG

**Project Webiste(Chrome and Safari recommended):** [Reviews are KING](https://xiangzhemeng.github.io/)

**Project Notebook:** [Jupyter NBViewer](https://nbviewer.jupyter.org/gist/TaoSunVoyage/2319dfa47c3e73490b027fb635bede07)

# Abstract
Reviews and ratings are everything for Amazon. One of the main reasons why customers trust Amazon, is the presence of reviews and ratings about products, which basically helps them understand about almost every detail of the product. But, how people review? Tons of reviews on Amazon make themselves as the best dataset for numerical and textual data analysis which is exactly what we are eager to do.

Our project, based on the Amazon kindle store product and review datasets, focuses not only on the basic factors of reviews and rating on Amazon, but also on the relationship between these two. With interactive and intuitive visualization, we are going to show you how people’s ratings and styles of review vary in different categories of kindle books and also the over-year changings. We want to study whether or not the rate people scores has any connection with what they write in review. Basic machine learning and natural language processing methods are also to be expected in the project.

# Research questions
### 1. Kindle Book Store
**General Analysis**

* What's the most popular categories of books? How average rating varies between different categories?
* Chronologically, how the ratings of books change? And how do people rate?
* Can we get the keywords of reviews of each year? Is there any obvious difference?

**Review analysis:**

* How to label or categorize or even score the reviews? How to define positive and negative reviews? What's the difference between 1-star and 5-stars reviews in terms of sentiment?
* For each rating, what is the style of people’s reviews (e.g. type of words used, style of using punctuation, etc.)? 
* What's the most frequently used words in Amazon reviews?
* Is there any inner connection between one’s rating of a book and his/her review? How can we reasonably vectorize review to make it suitable for analytical handling? Futhermore, can we build our own model predicting ratings based on review?  (That's where Machine Learning shows up.)
* What's the topics for each categories? 

### 2. Kindle Short Reads

* Do people love short reads? What's the differernce in ratings between books of different length? 
* How about the style of reviews of short reads? e.g. Would it be shorter for shorter reads?   
* What's the role of price? How does price influence costumers' behaviours and books' ratings?

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

This project will mostly use two subsets of the Amazon reviews dataset: Kindle store metadata and review datasets. We are going to use reviews dataset for rating and review analysis and product metadata dataset for kindle book categorization and classification.

The dataset of reviews provides us with the text of review, rating information, and importantly, the time of review, which is good for chronological analysis. The dataset of metadata provides us with various ways for product classification in terms of category. The data of sales rank might also be helpful to determine the popularity and sales of one book.

# A list of internal milestones
We plan to schedule our project on the following big steps:

* 01/11/2017 - 15/11/2017: data collection and wrangling
* 15/11/2017 - 28/11/2017: Data analysis & Key point study
* 15/11/2017 - 19/12/2017: Data visualization
* 28/11/2017 - 19/12/2017: Conclusion & result presentation
* 19/12/2017 - 29/01/2018: Poster & Presentation

# Contributions

* Shengzhao LEI: data loading, word clouds and graphs plotting, word frequency statistics and analysis, part of speech statistics research
* Tao SUN: data pre-processing, general analysis for Kindle book store, analysis for Kindle short read, graphs plotting for data story, presentation
* Xiangzhe MENG: data pre-processing, general analysis for Kindle book store, review sentiment and part of speech analysis, data story construction

