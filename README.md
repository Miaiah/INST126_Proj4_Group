# Maryland COVID-19 Data Analysis and Visualization

As COVID-19 is the most crucial disaster and catastrophe that we are currently facing worldwide, we think that it is extremely important for us, as well as everyone around us, to understand how critical the situation actually is. Since December 2019, cases have been identified in a growing number of countries, including the United States, which eventually became the hot spot for the most amount of COVID-19 cases around the world. Our goals for this project are to summarize and analyze COVID-19 trends in the state of Maryland and compare them by County using four functions. 

Firstly, we have spent several hours searching the Internet to find an accurate open source dataset online containing all COVID-19 cases in each Maryland County, consisting of columns showing each county and rows showing the exact date, from March all the way until November, and the time that each case had been reported; this dataset as a whole, consisting of 255 days in which COVID-19 cases were reported, will aid us in analyzing and investigating COVID-19 trends in the state of Maryland. 

Linked below is a preview of the dataset consisting of Maryland County COVID-19 cases that we have chosen, consisting of the first few rows:

https://github.com/Miaiah/INST126_Proj4_Group/issues/1#issue-755671762

Our first function that we created, called def mdCountiesCases(), displays the data that is contained in the dataset above as a line graph. The second function that we created, called def mdCountiesIncreaes(), displays the Maryland County COVID-19 case increase by county as a line graph as well. With a visual aid, it is easier to see the trends in COVID-19 counties within each county.


Aside from the dataset containing all COVID-19 cases in each Maryland County, we have also created a dataset consisting of education rates in each Maryland County. Using this dataset along with the dataset consisting of all COVID-19 cases in each Maryland County, we will be able to analyze and investigate trends comparing educational rates and COVID-19 cases. This will be one of our defined functions, called educationalRates(). The way this function works is the user will be able to input any Maryland County that they would like to analyze. The function is porgrammed to print the output of educational statistics for that specific county as a pie chart. For example, when inputting Washington County, the output will look like this:

https://github.com/Miaiah/INST126_Proj4_Group/issues/2#issue-755750340

Other datasets that we used are: 1. dataset consisting of COVID-19 cases by different races in every state; 2. dataset consisting of population by different races in every state. Using these datasets, we created a function, called racialPlot(populations_by_races, covid_cases_by_races_by_states, state, stateCode), to generate plots of COVID-19 racial trends and compare the racial trends and COVID-19 cases in Maryland versus the racial trends and COVID-19 cases in three selected states: California, Georgia, and Massachusetts.
