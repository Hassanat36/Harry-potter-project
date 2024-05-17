# Harry Potter Movie Series Analysis

![harry potter faces](https://github.com/Hassanat36/Harry-potter-project/assets/138366531/4a3bbe44-a07e-4a14-99fe-e83de22ba7b9)



## Table of Contents
- [Introduction](#introduction)
- [Skills Demonstrated](#skills-demonstrated)
- [Data Sourcing](#data-sourcing)
- [Data Transformation](#data-transformation)
- [Tools](#tools)
- [Analysis and Insights](#analysis-and-insights)
- [Conclusion](#conclusion)
- [Limitations](#limitations)
- [ MIT License](#mit-license)




## Introduction

Welcome to the Harry Potter Movie Series Analysis! This project delves into the enchanting world of the beloved Harry Potter film saga, aiming to uncover insights, trends, and interesting facts about this iconic cinematic journey. The Harry Potter movie series, adapted from the equally beloved book series by J.K. Rowling, has captured the hearts of millions worldwide. This analysis is not just about rekindling the magic of the films but also about using data-driven approaches to explore various aspects of the series. From character appearances to box office performance, our journey aims to bring a fresh perspective to the wizarding world.


## Skills Demonstrated

-	Extract Transform and Load (ETL).
-	Data Analysis Expression (DAX).
- Data Visualization.

   ## Data Sourcing

   Data was from kagle [click here](https://www.kaggle.com/datasets/maricinnamon/harry-potter-movies-dataset)

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
  
![Report](Harry Potter Movie Series Analysis)

![harryporter project with background_page-0001](https://github.com/Hassanat36/Harry-potter-project/assets/138366531/0bbe544d-18d8-419e-b1f5-62f93d8342f7)


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

## MIT License

Copyright (c) 2021 Louis Chauvet

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

  



  
