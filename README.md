# Game Purchasing Data Analysis

![Image](https://2s7gjr373w3x22jf92z99mgm5w-wpengine.netdna-ssl.com/wp-content/uploads/2019/08/KPI_shutterstock_everything-possible.jpg)

## Background
Heroes of Pymoli is a new fantasy online game that allows people to play for free where they can alos purchase items to enhance their experience.  A CSV dataset has been provided to uncover demographic trends and preferences so that the company can determine optimal marketing strategies to increase revenues.  To conduct the data analysis , Python with Pandas (through Jupyter Notebooks) will be  used to clean and process the data, as well as calculate the desired outputs.

## Datasets
* [Heroes of Pymoli Purchasing Dataset](https://github.com/cecileung1208/Game-Purchasing-DataAnalysis/blob/master/Heroes%20of%20Pymoli/Resources/HeroesOfPymoli_Purchase_Data.csv)

## Requirements
The report requires a breakdown of the following:

* Player Count
* Purchasing Analysis - Total
* Gender Demographics
* Purchasing Analysis - Gender
* Age Demographics
* Top Spenders
* Most Popular Items
* Most Profitable Items


## Method
* Import the CSV file into a Jupyter notebook and extract results for the following:

**Player Count**
* Determine unique number of players for the game.

**Purchasing Analysis - Total**
* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

**Gender Demographics**
* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

**Purchasing Analysis - Gender** 

The below each broken by gender:
* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Gender

**Age Demographics**

The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)
* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Age Group

**Top Spenders**

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

**Most Popular Items**

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

**Most Profitable Items**

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

## Scripts
* [Jupyter Notebook](https://github.com/cecileung1208/Game-Purchasing-Data-Analysis/blob/master/Heroes%20of%20Pymoli/HerosOfPymoli.ipynb)
* [Final Output](https://github.com/cecileung1208/Game-Purchasing-Data-Analysis/blob/master/Heroes%20of%20Pymoli/HeroesOfPymoli%20-%20Final%20Output.docx)

## Results

**Gender Demographics**

The major participants who plays and buy the game are predominantly male players as they account almost 85% of the players and the total purchases.
* 84.03% of the 576 players are male.
* 82.68% of the total purchases are made by male players.

**Age Demographics**

The major participants of the game are in the 20-24 age range as they account for almost 50% of the purchases:
* 44.79% of the 576 players are in the age 20-24 category.
* 46.81% of the age 20-24 players are made by these players

**Most Profitable and Popular Items**

The most profitable and popular item is Final Critic as it has the highest purchase count and made the most profits.
* There is a total of 13 purchases made for this game.
* It made a total profit of $59.99.



