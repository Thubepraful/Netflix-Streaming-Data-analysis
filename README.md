# Netflix-Streaming-Data-analysis
- 

# Table of Content-:

- Preview
- Reason to Choose these Case study
- Pandas Methods which are used in these project
- Graph which are used
- Workdone
- Conclusion
- Result


# 1. Preview of File : https://drive.google.com/file/d/1FSj_aDyBofR1lKCtEptIE_jveOU0ZE31/view?usp=sharing\

# 2. Thoughts behind this case study : 
  - As we know that when it comes to T20 cricket format, it is the most exiting one of them all, IPL Tournament is a contest one should not miss. As being a fan of team which represent my city, it was go to dataset for pulling exciting insights & information.

# 3. Pandas Methods used :
  - .read_csv()
  - .head()
  - .info()
  - .isnull()
  - .sum()
  - .drop(), .dropna()
  - .value_counts()
  - .unique()
  - .loc()
  - .plot()
  - .DataFrame()
  - .count()
  - .append()
  - .idxmax()
  - .sort_values()
  - .groupby()
  - .get_group()
    - shape

# 4. Numpy Methods used :
  - np.array()

# 5. Graphs Used :
  - Bar plot
  - Count Plot
  - Pie Chart
  
# 6. Work Done :
  - By using dropna method I have dropped rows with the Nan values in the dataset, and columns that were of no use to this analysis with drop method.
  - By using value_counts I got name and the count of cities & matches it hosted, team and the toss or the matches it won, I've also used it in for plotting graphs.
  - By using idxmax I got the highest value of the columns, to find unique values & to neglect the copies, I've used unique method.
  - I used masking technique to know the information about tied matches.
  - I used groupby where i need the reference of some other columns.
  - I used countplot where the data is more and to visualize it properly.
  - I used pie plots to show proportional distribution of values.

# 7.  Results :
  - This **EDA** is mostly **Mumbai City** and it's team **Mumbai Indians** Centric as it has been most successful and one of the famous teams amoung IPL Teams

  - 1. In all seasons of IPL, **Mumbai City** has hosted the *most matches* with the fact that it has altogether 3 venues,*Wankhede Stadium* being the most frequent match holding venue with 57 matches, then *Dr DY Patil Sports Academy* & at last *Brabourne Stadium*.
  - 2. But if we consider a particular venue, "**M Chinnaswamy stadium**" of city "Banglore" has conducted most matches. 
  - 3. For **60%** of the times matches played at venues in **Mumbai**, teams elected to **FIELD** *first*.
  - 4. Also **Toss probability** & the *decision* to **field** on toss win has also gone *in favour* of the team plenty of times.
  - 5. If we consider this above conditions, again **Mumbai Indians** have won more than *half of all the matches* that took place in **mumbai**, which means they have firm *grip on their home ground & it's playing conditions*.
  - 6. If we look at the games of **Mumbai Indians**, in rivalry matches of "*Mumbai Indians" vs. "Chennai Super Kings*" team "**Mumbai Indians**" have won more times.
  - 7. **Chris Gayle** or the "*The Universe Boss*", has won the "**Player of the match**" most times, and Hitman "**Rohit Sharma**" has won it most times for **Mumbai Indians**.
  - 8. In **2013**, there were most matches of IPL were played, where **Mumbai Indians won** the season, **Chennai Super Kings** won a match without a loss of wicket, which was the **runner up** team for the season. 
  - 9. Untill now **Mumbai Indians** have won the most matches.

# 8.  Conclusion :

  - So if you are a fan of **Mumbai Indians Team**, there is more probability of you **celebrating the victory** of your favourite team, if the match is played at **"Wankhede Stadium"**, toss won by **Mumbai Indians** & they elect to **"Field" First**.

  - Also in Season 2013 with this terms, Team **"Mumbai Indians"** won the season.

  - So we can say that team **"Mumbai Indians"** has been the most **Successful team** in the IPL Cricket history.

  - If they follow this agenda, then they can end up in top 4 teams for IPL Playoffs every year.
