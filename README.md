# Datasets for "Machine Learning for Dummies" 2nd ed.
<p align="center">
  <img src="https://media.wiley.com/product_data/coverImage300/66/11197240/1119724066.jpg" alt="ml4d cover"/>
</p>

<P>This repository contains some of the datasets present in <B>"Machine Learning for Dummies" 2nd edition</B>.<BR>
<P>Presented in feather format for Python and R compatibility, readers can access these datasets by the code present on the book, or simply by downloading this entire repository or its single files of interest.</P>

> Feather is a portable file format for storing Arrow tables or data frames (from languages like Python or R) that utilizes the Arrow IPC format internally. Feather was created early in the Arrow project as a proof of concept for fast, language-agnostic data frame storage for Python (pandas) and R. See: [Feather File Format](https://arrow.apache.org/docs/python/feather.html)

## tennis.feather
<EM>Chapter 10, Starting with Simple Learners</EM><BR>
One of the original Ross Quinlan datasets that present and describe the ID3 algorithm in Induction of Decision Trees (1986) (http://dl.acm.org/citation.cfm?id=637969). The dataset is quite simple, consisting of only 14 observations relative to the weather conditions, with results that say whether it’s appropriate to play tennis. The example contains four features: outlook, temperature, humidity, and wind, all expressed using qualitative classes instead of measurements (you could express temperature, humidity, and wind strength numerically) to convey a more intuitive understanding of how the features relate to the outcome.

## titanic.feather / titanic.csv
<EM>Chapter 10, Starting with Simple Learners</EM><BR>
A dataset describing the survival rates of passengers from the RMS Titanic, the British passenger liner that sank in the North Atlantic ocean in April 1912 after colliding with an iceberg. Various versions of the dataset exist — the version used in the example is made of few key features such as gender, age, number of siblings or spouses aboard (sibsp), number of parents or children aboard (parch) and survival expressed as a binary where one means the individual has survived.
 
## spam.feather
<EM>Chapter 10, Starting with Simple Learners</EM><BR>
Hewlett-Packard Labs collected the dataset and classified 4,601 emails as spam or nonspam, using 57 features, many of them being just normalized counts of how many times certain words or symbols appear in the e-mail. You can also find the spam dataset on the free UCI machine learning repository at https://archive.ics.uci.edu/ml/datasets/Spambase.

## penguins.feather
<EM>Chapter 12, Leveraging Similarity</EM><BR>
The Palmer Penguins dataset is a recent dataset and, under an educational point of view, a very good replacement for the usual Iris dataset. The Iris dataset, introduced by the statistician Ronald Fisher in one of his papers in 1936, is a popular example dataset about three species of iris flowers that had their petals and sepals (part of the flower, supporting the petals when in bloom) measured. Because of its popularity, the Iris dataset has been widely explored in many books and tutorials, though its data proved not always being suitable for many statistical and machine learning tasks.
The dataset records the gender, body mass, the flipper length and the bill length and depth (called culmen) of three species of penguins (Adelie, Chinstrap, Gentoo, for more information please consult the article: http://marinebio.net/marinescience/04benthon/AApenguins.htm) living in the islands in the Palmer Archipelago, Antarctic. The examples are not balanced among classes (there are less Chinstrap), but it is balanced among genders (we have the same count for female and male).

## air_passengers.feather
<EM>Chapter 14, Hitting Complexity with Neural Networks</EM><BR>
A well-known problem in times series, the Air Passenger Data is an example first found in the classic book “Time Series Analysis, Forecasting and Control” by Box, Jenkins and Reinsel, published in 1976 by Wiley and it has now become a public classic to be found in all books and software about time series. 
The figures in the Air Passenger Data are the monthly totals of international airline passengers, 1949 to 1960, of an American airline company. The interesting aspect of such figures is that they feature a growing trend that is not linear and they display some seasonal recurrence (for instance more travelling during summer).

## mnist.feather
<EM>Chapter 15, Going a Step beyond Using Support Vector Machines</EM><BR>
A replica of the dataset of handwritten digits provided by Scikit-learn. This is just a portion of the real MNIST dataset, available at the website http://yann.lecun.com/exdb/mnist/. The full dataset consists of 60,000 training examples and 10,000 test examples. 

## wine_quality.feather
<EM>Chapter 16, Resorting to Ensembles of Learners</EM><BR>
The wine quality dataset (P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009), combines both white and red wines. The data associates physicochemical tests (alcohol concentration, density, acidity and so on) on some Portuguese wines with the quality evaluation of experts. The dataset offers the opportunity to treat it both as a regression or classification problem.

## lfw_people.feather
<EM>Chapter 17, Classifying Images</EM><BR>
Labeled Faces in the Wild dataset that contains images of famous people collected over the Internet: http://scikit-learn.org/stable/datasets/labeled_faces.html

## shakespeare_lines_in_plays.feather
<EM>Chapter 18, Scoring Opinions and Sentiments</EM><BR>
A dataset collecting all of Shakespeare’s plays. It contains 217 rows, each one storing in the column named “lines” the text of an act of a play. 

## imdb_50k.feather
<EM>Chapter 18, Scoring Opinions and Sentiments</EM><BR>
The Large Movie Review Dataset is a dataset released by the Stanford University.
The dataset (http://ai.stanford.edu/~amaas/data/sentiment/) has been presented in the 2011 paper “Learning Word Vectors for Sentiment Analysis” by Andrew Maas and other authors (http://ai.stanford.edu/~amaas/papers/wvSent_acl2011.pdf). It collects 50.000 movies reviews from IMDb, the Internet Movie Database, an online database of information related to movies, TV programs and even video-games. The dataset contains an even number of positive and negative reviews. Half of the reviews were intended for training and the other half for testing purposes.
