# EDAV Final Project

## Project members: 
Priyanka Lahoti, Hima Bindu Bhardwaj, Jasmine Bao, Yingnan Wu

## Topic: 
We decided to have our topic as wars in history. There are 4 data sets corresponding to inter-state wars, intra-state wars, non state wars and extra state wars. 

## Questions:
* General visualization explorations of wars, such as:
    + what types of wars happened most frequently,
    + which country initiated inter-state wars most frequently, 
    + which war type caused the most number of deaths,  
    + what wars caused the most number of deaths, 
    + is the number of deaths correlated to whether the country is an initiator of an inter-state war or not, 
    + is there a pattern between initiators and winners of inter-state wars, 
    + what countries had most losses of human lives due to the war, 
    + what countries participated most actively in the wars, 
    + is there a pattern of the starting month of all wars, etc.

* What are the similarities and differences between World War I and World War II? (e.g., How were the global food prices affected during WW1 and WW2 time periods?)

* What are the effects of wars on the economics, food production, population, and education of some countries? (We may focus on some countries like Japan, Russia, Germany, China, United Kingdom, France that both participated in WWI and WWII.)

## Data:
Our data is from [The Correlates of War Project](http://www.correlatesofwar.org/), a project that seeks to facilitate the collection, dissemination, and use of accurate and reliable quantitative data in international relations. There are four data sets which are about extra-state wars, inter-state wars, intra-state wars, and non-state wars respectively. Each data set is available as a `csv` file and comes with a codebook that defines each variable clearly. Therefore, our method of importing data is simply downloading the datasets and importing into RStudio with `read.csv()` function. 

In addition, we plan to merge other data sets about economics into our analysis, especially for the third question in Part 2 above. Our population and real GDP per capital data is from the [Maddison Project Database](https://www.rug.nl/ggdc/historicaldevelopment/maddison/releases/maddison-project-database-2018) which provides information on comparative economic growth and income levels over the very long run. Specifically, this dataset includes data on real GDP per capita in 2011 US dollars and population for the two world wars and is available in csv format.
