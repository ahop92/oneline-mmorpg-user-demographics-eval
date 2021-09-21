# Online MMORPG User Demographics Evaluation


## Background 

One script was developed to evaluate different profit data from a software/gaming company. The raw data was housed by CSV excel files. The goal was to develop a python/jupyter scripts that manipulates the pandas and numpy libraries to evaluate the data and offer a high level analysis.

### Heroes of Pymoli Code Functionality

Each section of code pulls from the raw data and creates dataframes to store the subsets of information and to avoid overwriting original raw data. The whole script is sectioned according to the type of analysis requested (gender demographics, age demographics, purchasing according to age, etc.). Generally, the script relies on merging the subsets of data around shared columns or indicies to create the final summary tables in each output. In the case of the age data, bins were manipulated to group the users by age bracket. Lastly, in general the output information was formatted according to the option request found in the instructions. 

### Results 

The following high level analyses were completed with their associated results: 

1. Player Count: Total number of players engaged with the program is 576.

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/totalplayers.PNG)

2. Total Purchasing Analysis (no delimiting factors or demographics): Overall, Heroes of Pymoli has made a total revenue of $2,379.77 from 780 in game purhcases with items at an average price of $3.05. 

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/purchasing.PNG)

3. Gender Demographics: regarding gender demopgraphics, cis-gender males contribute 84.03% of the total gamer base with cis-gender females totaling 14.06% and non-disclosed genders totaling 1.91%. Should the parent company want to diversify this, it is recommended that characters and items are developed that better connect with non-cis-male players. Additionally, when allowing someone to specify their gender, it is recommended that other distinctions such as "trans, gender non-conforming, non-binary, etc." are included in demographic collection forms.

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/gender.PNG)

4. Purhcasing Analysis by Gender: since the cis-male sub-group comprises the vast majority of the gaming population within Heroes of Pymoli its contributions to the overall revenue of the program are higher as well with total purhcase value being $1,967.64.

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/purchasebygender.PNG)

5. Age Demographics: a breakdown of population by age shows that the majority of players for Heros of Pymoli are between the ages of 15 and 24 with the sub-group of 20-24 containing the majority of participants at 44.79% 

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/age.PNG)

6. Purchasing Analysis by Age: Accordingly, the same population of gamers mentioned in the age demographics section also comprises the majority of revenue made from in game purchases as well (age group 20-24 with $1,114.06 total revenue and 15-19 with $412.89 total revenue)

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/purchasebyage.PNG)

7. Top Spenders (by Screenname): the 5 top spenders across the whole population are depicted below with their associated total purhcase value. It is recommended to incentivize future purchases by rewarding players in this category with in game rewards.

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/topspenders.PNG)

8. Most Popular Items: The top 5 purchased items are depicted below with their associated prices and total purhcase value.  

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/toppurchases.PNG)

9. Most Profitable Items: The top 5 most profitable items are depicted below with their associated prices and total purhcase value. Please note the difference from the previous table. It is recommended to somehow incentivize the purchase of the items below (perhaps with more marketing or a promotion of some kind with in game bonuses) since they stand to make the most profit for the game. 

![image](https://raw.github.com/ahop92/oneline-mmorpg-user-demographics-eval/main/images/mostprofitable.PNG)


