# README

This application is a data analysis tool built for analyzing waste water data, specifically 
the percent removal for compounds moving from the influent to the effluent from a waste water 
treatment plant. 

The program will determine the lower 95% confidence interval for percent removal of compounds
moving from the influent to the effluent. It will also calculate the upper 95% confidence interval
for the effluent concentration.

It will take two data sets, one for a compounds concentration in the influent and another 
for the concentration in the effluent. Then for each data set a new data set of the same length will
be made by randomly sampling from the original data set. The medians will be found for both of these data
sets and used to calculate the percent removal. This percent removal value will be put into a list
and that whole process will be done 5000 times. The list will then be sorted by ascending order
and then the percent removal at position 250 will be used for the lower 95% confidence interval of 
percent removal.




# README


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
