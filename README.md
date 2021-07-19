# Commodities Analysis

Exploring Commodities dataset gotten from [United States Department of Agriculture (USDA)](https://apps.fas.usda.gov/psdonline/app/index.html#/app/downloads).

## 🗄 Files

- [commodities_EDA](https://github.com/gabrielatrindade/commodities_analysis/blob/master/commodities_EDA.ipynb): 
Exploratory Data Analysis of `All_Commodities` dataset. 
Here I explore how the data is organized - what each row represents, columns and their values meaning - with the help from FAQ's and Reference Data from the website. 
I also picked up the 5 commodities I want to work on - which are 'Coffee, Green', 'Grapefruit, Fresh', 'Lemons/Limes, Fresh', 'Oranges, Fresh', and 'Tangerines/Mandarins, Fresh'. \
*Besides pandas library I used `pandas_profiling` to have an overview of each column.

- [5_commodities_visualization](https://github.com/gabrielatrindade/commodities_analysis/blob/master/5_commodities_visualization.ipynb): 
Getting information from 5 commodities, using visualization. Some graphs are plotted here for the following questions: \
              1. Largest producers / consumers per commodity ✔️ \
              2. Balance between production and consumption in respective origin countries ✔️ \
              3. Percentage of consumption of commodity for the largest producers ✔️ \
              4. Stock level balance throughout the years ✔️ \
              5. Top 7 Exporters per Commodity in a year ✔️ \
              6. Top 7 Importers per Commodity in a year \
              7. How is the distribution of the production of different coffees? (Arabica, Robusta, Other) \
              8. Who are the biggest producers of each coffee type? 

   I used Pandas, numpy, seaborn, and matplotlib libraries.

 ## 🗂 Folder

- [outputs](https://github.com/gabrielatrindade/commodities_analysis/tree/master/outputs): 
This folder contains two pandas_profiling reports of the dataset.
