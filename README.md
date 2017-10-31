# Kindlize or Not

# Abstract
2007 changed the world of reading forever with Amazon’s launch of its first e-reader, Kindle. And only three years later, Amazon announced that sales of eBooks, for the first time, outnumbered sales of hardcover books. People began to keep asking the same question: “Do we still need hardcovers in the future?” Now, ten years after the birth of Kindle, we want to give you an answer. Our project, based on the datasets of Amazon reviews, focuses on the difference between the electronic and paper version of each book on reviews and on ratings. With interactive and intuitive visualization, we are going to show you the answer in different dimensions of books (type, size, language, publishing company, etc.). We want to study how the Kindle has changed the people’s ideas and passion about books and whether or not Kindlization is a good idea for each book. Basic machine learning and natural language processing methods are to be expected in the project.

# Research questions
* How to define the positive review and negative review of books?
* How to find the key words of positive/negative review of Kindle or hardcover book?
* Is there any difference on Average Rating between Kindle and paper versions?
* Chronologically, how the emergence of Kindle changed the rating of books?
* What’s the difference between the styles of people’s reviews on two versions of books?
* What are the advantages of these two versions respectively?
* Is there any inner connection between the properties of  a book and the version chose? We are going to classify books on the basis of several dimensions in order to help choose a better version for readers.
* How to make some valid amendments for kindle? (This is a potential research question because currently we haven’t seen the content of the dataset. If there are a large number of reviews which give us feedback concerning the user experience of Kindle instead of the reading experience of Kindle books, we will make some reasonable suggestions for the ebook reader itself as well.)

# Dataset
**Name**: Amazon reviews
**Source**: http://jmcauley.ucsd.edu/data/amazon/
**Description**:
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
**Usage**:
This project will mostly use two subsets of the Amazon reviews dataset: Books and Kindle Store. We are going to use reviews dataset for rating and review analysis and product metadata dataset for book categorization and classification. With the help of attribute asin, we can easily find the connections between two datasets.
The dataset of reviews provides us with the text of review, rating information, and importantly, the time of review, which is good for chronological analysis. The dataset of metadata provides us with various ways for book classification: price, brand and category. The data of sales rank is also helpful to determine the popularity and sales of one book.

# A list of internal milestones up until project milestone 2
We plan to schedule our project on the following big steps:
 
    * 01/11/2017 - 15/11/2017: data collection and wrangling
    * 15/11/2017 - 28/11/2017: Data analysis & Key point study
    * 15/11/2017 - 19/12/2017: Data Visualization & Website
    * 28/11/2017 - 19/12/2017: Conclusion & Result presentation
    * 19/12/2017 - 29/01/2018: Poster & Presentation
 
Thus, we will have finished the first two parts and the third part will have already started until the project milestone 2.

# Questions for TAa
* For Amazon reviews dataset, we would like to know whether the Book subset contains the reviews of Kindle as well? Are we supposed to use two subsets (Book & Kindle)?
* What is the content of Kindle subset? The reviews concerning books on kindle or concerning kindles? 
* For the language of reviews, are all the reviews in English?

