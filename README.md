# Netflix-Streaming-Data-analysis
 - This case study provides a overview of recommendation system analysis of data which provides suggestions to the user based on the global rating data.

# Table of Content-:

- Preview
- Reason to Choose these Case study
- Pandas Methods which are used in these project
- Graph which are used
- Workdone
- Conclusion
- Result


# 1. Preview of File : https://drive.google.com/file/d/1etuGaOpFMmrkpDeAzIwDEKonpwKBGHs3/view?usp=sharing

# 2. Thoughts behind this case study : 
  - I chose this case study to analyze and visualize how & on what data the recommendation system of streaming service provider Netflix operates, & pull out fancy recommendation based on my own analysis of data.
 
# 3. Pandas Methods used :
  - .read_csv()
  - .head()
  - .info()
  - .isnull()
  - .sum()
  - .mean()
  - .median()
  - .drop(), .dropna()
  - .raname()
  - .set_index()
  - .value_counts()
  - .unique()
  - .nunique()
  - .nlargest()
  - .loc()
  - .plot()
  - .DataFrame()
  - .count()
  - .append()
  - .sort_values()
  - .groupby()
  - .get_group()
  - len()
    - shape

# 4. Numpy Methods used :
  - np.array()

# 5. Graphs Used 
  - Lineplot
  - Distplot (Histogram)
  - Bar plot
  - Count Plot
  - Pie Chart
  - Heatmap
  
# 6. Work Done :

  - Firstly I visualised the null values of columns, and accordingly filled null values of certificate column with NaN value as it had ratings for content & startYear column with mean year value by converting it to int datatype and dropped "episodes","endYear","plot" column which was no use to this analysis.
  - Also filled some columns with their mean values which had some contribution to this analysis. 
  - With nunique method I found out that isAdult column had only 0 in all the rows, so dropped it.
  - I set popular rank as index and renamed it as Sr. no. column.
  - As the dataset got ready for the analysis firstly I counted all types of content posted on netflix & visualised there proportion found out that there is one video game also posted on netflix.
  - Then grouped the content according to their start year for furthen analysis
  - After that I found out the top year for most content count per year and seggregated the sum as movies vs series.
  - Then listed out the ratings content recieved.
  -  Sorted the content according to langauges, contries that posted.
  - I used masking technique to know the information from columns with conditions.
  - At the end based on this analysis, I found out the top content to watch under numerous categories like country wise, genre wise, language wise, type wise etc.

# 7.  Results :

  - This dataset contains numerous **types** of contents including **Movies, Tv Series, Mini Series, Tv Episodes, Short Movies, Shorts (Short videos)** from which **Movies & TV Series** covers most of the content posted by **USA, UK, Japan, N. Korea, India** thusly **English, Japanese, Korean** language most.
  - This dataset has almost **10% content rated 18 & 18+**, where other **30%** is **7-16+**.
  - Most of the content is posted in recent 10 years but has average rating of 6.6-6.8 overall, this may be due to increase of content count.
  - As the content count is only in range of 100 - 200 or below than that for **years before 2012**, **rating** mean is bit **high**. It is due to top content from the old times is only posted on the netflix.
  - **2016** was **enriched** of **netflix content**, and also despite **Covid** pandemic situation **2020** was **2nd top** content posted year.
  - As people tend to turn to these kind of plateforms for entertainment top two genre categories are **Comedy & Drama**, with average runtime of **1 hr 30 to 2 hrs**.

# 8.  Conclusion :

 ### - If you're looking for content according to top genres of netflix:
   
   - for **Comedy** :
        - 1) "Middleditch & Schwartz" : An audience tale of love, music festivals
        - 2) "Seinfeld" 
        - 3) "Monty Python's Flying Circus" : The cartoon series that Python language is named after by it's owner
   
   
   - for **Drama** :
        - 1) "Move to Heaven" 
        - 2) "Nabillera"
        - 3) "House of Cards"
   
   
   - for **Action & Adventure**:
        - 1) "Avatar: The Last Airbender"	
        - 2) "Jujutsu Kaisen" : Anime
   
   
   - for **Top rated TV-Series**:
        - 1) "Ask the StoryBots"
        - 2) "Breaking Bad"
        - 3) "Stranger Things: Spotlight"
        - 4) "Word of Honor"
  
  
  - for **Top Movies**:
       - 1) "David Attenborough: A Life on Our Planet" - *Documentary*
       - 2) "The Lord of the Rings: The Return of the King"    
            - (Tip : If you love this movie, it's other parts are also in top rated list)
       - 3) "In Our Mothers' Gardens"
    
    
   - for **Top TV Series**:
        - 1) "Breaking Bad"
        - 2) "Avatar: The Last Airbender"
        - 3) "Rick and Morty"
        

   - for **Top Comedy Series**:
        - 1) "Friends" : Personal Favourite
        - 2) "Yeokdoyojeong Gim Bokju"
        - 3) "How I Met Your Mother"
        - 4) "Little Things"
        
        
   - for **Comedy & Romantic**:
        - 1) 'Venus on the Halfshell'
        - 2) "Love per Square Foot"
        - 3) "There's Something About Mary"
        
        
   - **Top Indian Content**
       - 1) Yeh Meri Family
       - 2) College Romance
       - 3) Sacred Games
       
       
- Well this list can go endless based on the genre of one's precedence & their mixes. Don't bother to surf through netflix by yourself, you may find something exciting that is not listed here.
