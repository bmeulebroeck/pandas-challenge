# pandas-challenge
Week 4 homework using pandas and Python

# Heroes of Pymoli
I chose the Heroes of Pymoli exercise after reading the descriptions. It caught my interest more than the school data. My notebook for submission is "HeroesOfPymoli_PurchasingDataInsights.ipynb"

# Three Observable Trends from the exercise:
1. The player population in this dataset is mostly male (84.03%)
2. Males account for the majority of purchases ($1,967.64 out of $2,379.77 total). However Females spend more per person than males ($4.47 vs. $4.07)
3. Nearly 77% of the players in this set are between the ages of 15-29, and they account for 76% of the purchase value.

# Starting Out
Building the initial data frame and finding the total unique players was very straight-forward and I was able to generate that pretty quickly. For the 'Purchasing Analysis (Total)' I referred back to the class activities and was able to pull out enough examples to get me started, then just worked on fine-tuning.

The gender section gave me a few trip ups as I started to calculate the number per gender. I ended up sorting by using a method I found on geeksforgeeks.com to sort by SN then drop duplicates. Not the prettiest but it got me what I needed to proceed.

# Groupby sections
Using groupby to calculate for the different measurments by gender (Total purchases, avg purchase, total spend, etc.) was where I learned the most about using groupby and the proper syntax to get what I was looking for. I used this section as the template for the rest of the report's calculation sections.

# Age brackets - Binning
This section was fairly straightforward for me. The part that I needed to research was using the .loc method to get the bins in the order that I wanted them to appear.

# Mapping
I tackled all the mapping and formatting at the very end after I had my data. With a little google-fu to get the syntax all lined up, and referring to the class activities, I was able to get everything looking the way I wanted.
