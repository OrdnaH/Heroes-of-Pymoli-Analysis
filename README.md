# Video Game Analysis

## Summary (with nbviewer link to my code)

The data dive continues!

Use your knowledge of Pandas to parse through thousands of records in order to draw conclusions about the data. This activity demonstrates your ability to utilize Pandas and identify trends of a dataset that couldn't be completed efficiently without programming. At the end of your [code](https://nbviewer.jupyter.org/github/OrdnaH/Heroes-of-Pymoli-Analysis/blob/master/Video_Game_Analysis.ipynb) (snippet below), include a written description of three observable trends based on the data analysis.

![Code_Snippet](Images/Code_Snippet.png)

## Heroes of Pymoli

![Fantasy](Images/Fantasy.jpg)

Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value


## Considerations

* This is challenging for a number of reasons. For starters, it will require you to analyze thousands of records. Hacking through the data to look for obvious trends in Excel is just not a feasible option. The size of the data may seem daunting, but pandas will allow you to efficiently parse through it.

* Begin by answering the basic questions: "How do I import the data?" "How do I convert the data into a DataFrame?" "How do I build the table?" Don't get intimidated by the number of tasks. Many of them are repetitive in nature with just a few tweaks. Be persistent and creative!