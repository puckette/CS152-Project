# Russian Propagandists and U.S. Politicians: Tweet Classification and Comparison

## Project Description

I will focus on training neural networks for the task of classifying tweets as having been written by Russian propagandists or U.S politicians in the years around the 2016 presidential election. These tweets will come from the time period of 2015-2017, and the Russian tweets will specifically come from propagandists at the Internet Research Agency, the Russian “online influence” institution financed by a close ally of Putin’s and indicted by the Department of Justice in 2018. The original neural network will be developed using the FastAI library, but subsequent networks will be developed using new tools to compare classification performance between NNs.

If this initial proves relatively simple, my next step will be to create a dataset of QAnon tweets and use it to train a NN that can differentiate between the existing tweets as well as the QAnon tweets, as it is a more recent conspiracy theory that has taken a lesson in disinformation from Russian propagandists. The trained neural networks will be deployed as an application, hopefully a fully developed publicly-available application.

The goal of this project will firstly be to determine the ability of a NN to differentiate between foreign propaganda for the purpose of election manipulation and speech by U.S politicians for their own political gain in order to advance the use of NNs in the detection of political disinformation. Secondly, it will be to raise questions about what constitutes disinformation, especially when it comes from the mouth of politicians as well as questions about what the role of NNs and other forms of AI should be in combatting disinformation.

## Project Goals

1. Develop a NN that classifies tweets as Russian propaganda or U.S. using the FastAI library
2. Explore new methods for building NNs that do the above task and compare performance between NNs
3. Build a dataset of QAnon tweets for training a NN in classification of tweets of QAnon followers, Russian propagandists, and U.S. politicians (potentially)
