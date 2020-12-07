# pandas-challenge
In this challenge we are analyzing data from a video game's optional item sales. We will be looking into the data as a whole, as well as breaking the data down to analyze various cuts.

## Analysis takeaways
There are 576 total players and most of the players identified as male (84%). There are 66% of the players between the ages of 15 and 24. Those in the (20-24) age bracket average purchases that are $0.09 more than the (15-19) age bracket. The most popular item (by 3 purchases) is "Oathbreaker, Last Hope of the Breaking Storm".

## Results
*The results are also printed with the Jupyter notebook, but there is some formatting error occurring in GitHub. The notebook in GitHub can be viewed via nbviewer on Jupyter's website: https://nbviewer.jupyter.org/* 

**Total Players:**

![Total Players Dataframe](https://github.com/LongPatrol/pandas-challenge/blob/main/Total_Players_dataframe.png)

**Total Purchasing Analysis:**

![Total Purchasing Analysis](https://github.com/LongPatrol/pandas-challenge/blob/main/Total_Purchase_analysis_dataframe.png)

**Players by Gender:**

![Players by Gender](https://github.com/LongPatrol/pandas-challenge/blob/main/Players_by_Gender.png)

**Purchasing Analysis by Gender:**

![Purchasing Analysis by Gender](https://github.com/LongPatrol/pandas-challenge/blob/main/Purchase_analysis_gender.png)

**Players by Age Bracket:**

![Players by Age Bracket](https://github.com/LongPatrol/pandas-challenge/blob/main/Players_Age_bracket.png)

**Purchasing Analysis by Age Bracket:**

![Purchasing Analysis by Age Bracket](https://github.com/LongPatrol/pandas-challenge/blob/main/Purchase_analysis_age_bracket.png)

**Top 5 Spenders:**

*"SN" here standing for "Screen Name"*

![Top Spenders](https://github.com/LongPatrol/pandas-challenge/blob/main/Top_5_spenders.png)

**Popular items (by purchase count):**

![Popularity by count](https://github.com/LongPatrol/pandas-challenge/blob/main/Top_5_items_by_count.png)

**Top items (by revenue generated):**

![Most Profitable Items](https://github.com/LongPatrol/pandas-challenge/blob/main/Top_5_items_by_profit.png)

## Coding References
**Dataframes**
>pandas. (2020, November 28). *pandas.DataFrame*. pandas. https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html

**Distinct counts**
>Akshaya, E. (2020, November 28). *How to Count Distinct Values of a Pandas Dataframe Column?*. GeeksforGeeks. https://www.geeksforgeeks.org/how-to-count-distinct-values-of-a-pandas-dataframe-column/

**Adding column to a dataframe**
>Tyagi, C. (2020, November 28). *Adding new column to existing DataFrame in Pandas*. GeeksforGeeks. https://www.geeksforgeeks.org/adding-new-column-to-existing-dataframe-in-pandas/

**Dropping a column**
>pandas. (2020, November 28). *pandas.DataFrame.drop*. pandas. https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop.html

**Dropping duplicate records**
>pandas. (2020, November 28). *pandas.DataFrame.drop_duplicates*. pandas. https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop_duplicates.html

**Renaming a column**
>EdChum. (2020, November 28). *Rename specific column(s) in pandas*. Stack Overflow. https://stackoverflow.com/questions/19758364/rename-specific-columns-in-pandas

**Percentage formatting**
>kapeli.com. (2020, November 28). *Python Format Strings*. kapeli.com. https://kapeli.com/cheat_sheets/Python_Format_Strings.docset/Contents/Resources/Documents/index

**Fixing sorting bugs**
>MaxU. (2020, November 29). *Why does my Pandas DataFrame not display new order using \`sort_values\`?*. Stack Overflow. https://stackoverflow.com/questions/42613581/why-does-my-pandas-dataframe-not-display-new-order-using-sort-values

**Un-index a column**
>behzad.nouri. (2020, December 6). *How to convert index of a pandas dataframe into a column?*. Stack Overflow. https://stackoverflow.com/questions/20461165/how-to-convert-index-of-a-pandas-dataframe-into-a-column

**Formatting issues in GitHub**
>Zucker, J. (2020, December 6). *Use display() not print() to display a dataframe in a jupyter notebook!*. GitHub. https://github.com/swcarpentry/python-novice-gapminder/issues/342
>> *I tried the suggestion from this post to get the DataFrames to display correctly in GitHub, but it didn't work.*

>Akhmetzhanov, A. (2020, December 6). *Pandas DataFrame not printing correctly*. GitHub. https://github.com/jupyter/notebook/issues/4357
