# Recommender Systems
Assignment 1 of the Advances in Data Mining course of Leiden University, year 2021-2022.

Recommender Systems with Naive Approaches, UV Matrix Decomposition and Matrix Factorization. Based on Chapter 9 of the MMDS book.

In the repository we have included a folder of results that our jupyter notebook uses in order to fetch the results of the experiments done.
They were saved in csv files since the runtime of all our experiments for the UV decomposition and the matrix factorization was pretty long.

In order to run the notebook properly, please make sure to have the following 
libraries installed:
numpy >= 1.19.2, 
pandas >= 1.2.3,
matplotlib,
sklearn.

The notebook fetches everything from the results folder so make sure to include it in the same directory as the notebook. The datasets of the 1M ratings also need to be in the same directory as the notebook. This includes the movies.dat, the ratings.dat and the users.dat files.

In case you might want to re-run all the experiments from scratch you need to uncomment the following cells: 20, 28 and 29 before running.
