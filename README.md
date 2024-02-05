# Harry Potter Movie Series Analysis

## Table of Contents
- [Introduction](#introduction)
- [Skills Demonstrated](#skills-demonstrated)
- [Data Sourcing](#data-sourcing)
- [Data Transformation](#data-transformation)
- [Tools](#tools)
- [Analysis and Insights](#analysis-and-insights)
- [Conclusion](#conclusion)
- [Limitations](#limitations)


![parentalleaves image](https://github.com/Hassanat36/Maven_powerbi_project/assets/138366531/9283bb74-af13-43fb-a028-8ebccd34fd77)


## Introduction

My journey into the world of parental leave policies, driven by data and brought to life with Power BI Desktop, has unveiled critical findings that illuminate the current landscape. Drawing from a comprehensive survey of 1,601 companies spanning 186 industries, I've transformed this data into a captivating visual narrative.


## Skills Demonstrated

-	Extract Transform and Load (ETL).
-	Data Analysis Expression (DAX).
- Data Visualization.

   ## Data Sourcing

   Data was gotten from Kaggle. [Click here](https://www.kaggle.com/datasets/shilongzhuang/things-we-do-for-family-some-bald-guy) 

   ## Data Transformation
 1. I imported my dataset to Power Query by using the format connector in PowerBI.
 2. I created new measures
    - Total Runtime = SUM(Movies[Runtime])
    - Total place = SUM(Places[Place ID])
    - count place = COUNT(Places[Place Category])

   ## Tools
- Excel for data cleaning
- PowerBI for creating analysis

 ## Analysis and Insights
  
![Report](Maven Parental Leave Reports)

![u0Wt27N - Imgur](https://github.com/Hassanat36/Maven_powerbi_project/assets/138366531/af3ca580-893f-425f-be41-7cc000a6530a)

### Key Insights
1. Count of Movie Dialogue: The count of movie dialogue is 7444, indicating the total number of dialogues across the entire Harry Potter movie series.
2. Count of Movie Chapters and Total Movie Series: The dataset includes 234 movie chapters, and the Harry Potter movie series consists of a total of 8 movies.
3. Total Spell Use: The combined spell usage across all movies is 1891, representing the total number of spells used throughout the series.
4. Longest Movie with Dialogue: Among all the movies, "Harry Potter and the Deathly Hallows – Part 1" is the longest movie in terms of dialogue. It implies that this particular movie has the most extensive dialogue scenes.
5. Movie with Highest Running Time: "Harry Potter and the Chamber of Secrets" has the highest running time among all the movies in the series. This indicates that it is the longest movie in terms of total duration.
6. Most Dialogue by Character: The character name "Harry Potter" has the most dialogue across all the movies. This implies that the character of Harry Potter has a significant presence in the dialogues throughout the series.
7. Popular Movie Location: "Hogwarts" is the most popular location frequently used in the Harry Potter movie series. It suggests that Hogwarts plays a central role in the storyline and serves as a key setting for many scenes.
8. Top 5 Spells Used: The top 5 most frequently used spells in the movies are:
- Unlocking Charm
- Vera Verto
- Wand-Extinguishing Charm
- Wand-Lighting Charm
- Water-Making Spell

 
## Conclusion:

In conclusion, the analysis paints a vivid picture of the Harry Potter movie series, highlighting not only its fantastical elements but also the intricate storytelling and character dynamics. The richness of the Wizarding World is evident in the dialogue, spell usage, and the iconic locations such as Hogwarts. As we delve into the intricacies of each movie, it becomes apparent why this series has left an indelible mark on popular culture.
The longest movie, highest running time, and the prominence of characters like Harry Potter contribute to the immersive nature of the series. The choice of spells and the magical world's most iconic location, Hogwarts, add layers to the narrative that have resonated with audiences worldwide.

## Limitations:

Despite the insights gained from the analysis, it's important to acknowledge certain limitations:

- Data Scope: The analysis is limited to the available dataset. Additional data sources, including behind-the-scenes information, interviews, or fan discussions, could provide a more comprehensive understanding.
- Contextual Nuances: The analysis focuses on quantitative aspects, and while it sheds light on patterns, it might not capture the contextual nuances of certain scenes or character motivations.


  



  
