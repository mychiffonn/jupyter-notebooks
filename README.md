# Inferential Statistics on Goodreads English Titles

This repository contains an analysis of Goodreads English titles using inferential statistics. Specifically, a two-sample t-test (difference of means) was conducted to compare the average rating of English books with long title names (>= 6 words) to the average rating of books with short titles.

### Dataset

The dataset used for this analysis `sampled-books.csv` was directly sampled from the Goodreads dataset on [Kaggle](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) (45K rows). It contains information about the title, author, average rating, and number of reviews of books on Goodreads.

Therefore, the statistical inference drawn from this repo can only be applicable to the population of English books found in the larger [Goodreads dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks).

### Analysis: EDA & Statistical Inference

The analysis was conducted using Python and the `pandas` and `scipy` libraries. 

The two-sample t-test was used to compare a two-sample t-test (difference of means) was conducted to compare the average rating of English books with long title names (>= 6 words) to the average rating of books with short titles. The results of the t-test show that **there is a statistically significant difference between the two groups** ($p = 0.01 < 0.05$).

However,  the average ratings of long-titled English books are **only slightly higher than** those of short-titled books ($\text{Cohen's } d = 0.36$).

### Results

The results of the analysis are presented in the [Jupyter Notebook](https://github.com/chiffonng/inferential-stat-goodreads/blob/main/Statistical%20Inference_Goodreads%20Books.ipynb). The Notebook contains the code used for the analysis as well as visualizations of the data.
