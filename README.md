# Challenge_02_VBA_of_WallStreet
This is the Challenge for Module 2
# VBA of Wall Street

## **Overview of Project**
Based on the data that the file green_stocks has, there can be seen a number of stocks that want to be analyzed, and their respective data.

### This project includes:
- All Stocks Analysis
- Stock Volumes
- The Return for every stock in the file
- A written analysis of the results


### **Purpose**
Visualize data to analize in order to get the most accurate stock to invest. In this case, the full stock needed to be analyzed in order to find the best one to invert in, and see the return to start making a decision if its better to invest in just one or more.

## Analysis and Challenges
So there can be a better understanding, first there is a need to know which value corresponds to which stock name, and that is why there is a need to code a variable that acts  as a string that carries all the names of the stocks.

This analysis must give the Total volume of every stock and for that it must consider, for every day registered, the volume sold for that particular stock name. That way it will be easier to analyze the amount they sold during the first open day and the last one.

Once every Stock name and total volume is in place, there must be a result in which can be observed the return that every stock had, in order to know which one would be a risk and which one can create a profit.


### **Analysis of Stocks**
Once everything is settled with the code, it can be observed that in 2017 the stock with better profit was DQ while the one with loss was TERP. In 2018, the one with the best profit was RUN, followed by ENPH, while the other stocks were at loss. Between 2017 and 2018 it can be said that is probable that RUN will get a better profit for next year, since ENPH was in 2017 with a return of 129.5 % and in 2018 it only increased 81.9%, meaning that next year probably its profit will decrase. While RUN started with a profit in 2017 of 5.5%, in 2018 it increased to 84%. It's probable that RUN would keep on rising until certain point and then it will crash, for now, there is a need to observe the maximum and minimum points. There is a need of more yearly information in order to determine when will be a possible increase or decrease in the stock market in order to make a better desicion, however, with the data that is presented there can be a possible prediction that will get to a possible good result.

 ![2017](https://github.com/LennethNova/Challenge_02_VBA_of_WallStreet/blob/main/Resources/2017_stocks.PNG)
 
 ![2018](https://github.com/LennethNova/Challenge_02_VBA_of_WallStreet/blob/main/Resources/2018_stocks.PNG)

### Challenges and Difficulties Encountered
The first thing that can be a challenge is to do an Overthinking and don't fully understand what every part that is asking. Also, the tickerIndex part was a little confussing at the beginning because, even with the obvious name, there was  *lack of knowledge* in regard of a variable could work also as an Index. Until the end of the code it was clear that the tickerIndex was working as the index of my ticker and that needed to be added to other parts. As a first time in programming, it was not so clear why. Fortunately, logic and some review of the materials helped understand that part and proceed with the rest of the challenge.

## Results

- What are the advantages or disadvantages of refactoring code?
The principal advantage is that the code is almost done with, and gives a base to work with. The principal disadvantage is that if it's not well commented it can lead to confusion.


- How do these pros and cons apply to refactoring the original VBA script?
The code was easy to follow at the beginning, but since there was not a comment that was almost "for dummies" regarding the tickerIndex and how it sholud be used, it was a little confusing since until almost the end there was obvious that it will control not only the index for my ticker but almost every part.

- Additionally the elapsed time compared with the Module acctivities was reduced in time and also made the data analysis faster and without possible crashes.

 ![2017 Time Elapsed](https://github.com/LennethNova/Challenge_02_VBA_of_WallStreet/blob/main/Resources/VBA_Challenge_2017.png)
 
 ![2018 Time Elapsed](https://github.com/LennethNova/Challenge_02_VBA_of_WallStreet/blob/main/Resources/VBA_Challenge_2018.png)
