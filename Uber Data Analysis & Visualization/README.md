Uber_NewYork_Data_Analysis
This project is an analysis of the 'Uber Pickups in NYC' dataset.

Throughout the project, various questions regarding the Uber pickup-trends in and around New York have been answered which can be used to gain insights into the customer behaviour and demands and subsequently make changes to their business model accordingly to serve them better.

In the analysis, some of the questions that have been answered are given below:

Which day of the week witnesses maximum rush for pickups, and at what time?
At what time during the day is the rush maximum?
Which places in and around New York have high pickup rates?
What is the demand versus supply chart of uber pickups in NYC?
The results have been effectively visualized.

Link to the dataset- https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city

SUMMARY OF THE DATASET

This data contains on over 4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015. Trip-level data on 10 other for-hire vehicle (FHV) companies, as well as aggregated data for 329 FHV companies, is also included. All the files are as they were received on August 3, Sept. 15 and Sept. 22, 2015.

The dataset contains, roughly, four groups of files:

Uber trip data from 2014 (April - September), separated by month, with detailed location information Uber trip data from 2015 (January - June), with less fine-grained location information non-Uber FHV (For-Hire Vehicle) trips. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number. aggregate ride and vehicle statistics for all FHV companies (and, occasionally, for taxi companies) Uber trip data from 2014

There are six files of raw data on Uber pickups in New York City from April to September 2014. The files are separated by month and each has the following columns:

Date/Time : The date and time of the Uber pickup Lat : The latitude of the Uber pickup Lon : The longitude of the Uber pickup Base : The TLC base company code affiliated with the Uber pickup These files are named:

uber-raw-data-apr14.csv uber-raw-data-aug14.csv uber-raw-data-jul14.csv uber-raw-data-jun14.csv uber-raw-data-may14.csv uber-raw-data-sep14.csv Uber trip data from 2015

Also included is the file uber-raw-data-janjune-15.csv This file has the following columns:

Dispatching_base_num : The TLC base company code of the base that dispatched the Uber Pickup_date : The date and time of the Uber pickup Affiliated_base_num : The TLC base company code affiliated with the Uber pickup locationID : The pickup location ID affiliated with the Uber pickup The Base codes are for the following Uber bases: B02512 : Unter B02598 : Hinter B02617 : Weiter B02682 : Schmecken B02764 : Danach-NY B02765 : Grun B02835 : Dreist B02836 : Drinnen