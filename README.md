# Project-1

Effect of Moon Phase on Crime Rates in Austin, Texas
Team: Jon Argoitia, Erin O'Brien, Gregory Talbott & Fatima Shami

Does a full moon really make people act crazier? In this project, we use daily reported crime data to examine to common trope.

Our project is to uncover patterns in criminal activity in Austin as they relate to four of the eight lunar phases. Covering data between 2014 to 2021, we examine relationships between types of crime and moon phase, crime rates and moon phase, and related questions..

We used an API to scrape historical daily crime report data from https://data.austintexas.gov/Public-Safety/Crime-Reports/ and a moon phase .csv file from https://www.calendar-12.com/moon_phases/ to create the dataframe that we based our plots and statistical analysis on. After cleaning up the data and merging the .csv and the dataframe we pulled from the database, we were able to create multiple plots with simple, repeatable code where we could input small tweaks to create a robust analysis that can be built on as additional questions arise. For this project, as the time allowed, we were able to create plots of daily crime reports over time (full study period, individual years, and by month), with the full moon date plotted on top of the crime curve to examine if there was a local maxima on the curve that corresponded with the full moon. We also analyzed the curves by month to draw conclusions about trends in the highest reported crime days per month. Additionally, we created box and whisker plots of the number of crimes reported during the full moon and the number of crimes reported on non-full moon days across the entire study period.

This analysis provided a number of conclusions
  -proved the null hypothesis: the moon phase does not have an influence on crime rates 
  -the mean of the number of crimes reported per day during the full moon and all other times was almost the same 
  -the highest crime day annually was January 1, and monthly the highest crime day was the first of the month
  -crime reports decreased during Christmas time 

To view the full analysis and final code please see the notebook and powerpoint presentation in the master folder.
To view the process of writing the code, including commented out trials and logic, view the notebooks in individual folders. 




