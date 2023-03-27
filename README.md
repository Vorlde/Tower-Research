# Tower-Research Data Challenge

This repository contains the code and related materials for my participation in the quantitative competition hosted by Tower Research Capital at IIT Bombay. The competition aimed to showcase innovative strategies and techniques for financial forecasting and trading using quantitative methods.

Within this repo, you can find the codebase that I developed for the competition, including scripts, notebooks, and data preprocessing and visualization tools. I have also included relevant research papers, reports, and presentation materials related to my work.

Through this competition, I have gained valuable experience in developing and implementing quantitative strategies in finance

## Problem Statement:
Given the prices of 100 stocks at different timestamps and 15 indices with their corresponding prices at each timestamp, analyze and answer the following questions: 

a. Determine the value of M, where M is the number of sectors that the 100 stocks belong to.

b. Partition the 100 stocks into M sectors and store the set of stocks for each sector to help speed up the next part.

c. Using the functional form given in equation (1) and the constraint that each index Ii is a function of stocks only from a particular sector, solve for as many indices as possible. Construct a model that implements fi and reports which sector the index pertains to.

d. Collect all the indices you can solve and compute the covariance Σk×k for your predictions µk×N.

e. Construct a trading strategy using µ and Σ from the previous part, subject to the constraints given in the problem statement.
