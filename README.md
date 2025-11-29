# Restaurant Ratings Analysis

## Introduction
This dataset contains information about restaurants in Mexico. In 2012, a customer survey was carried out to collate information about various restaurants, their characteristics, cuisines, ratings, information about their consumers, consumer demographics, and their consumer preferences in Mexico.  

## Key Metrics / Problem Definition
1.	What can you learn from the highest-rated restaurants? Do consumer preferences have an effect on ratings?  
2.	 What are the consumer demographics? Does this indicate a bias in the data sample?  
3.	 Are there any demand & supply gaps that you can exploit in the market?  
4.	 If you were to invest in a restaurant, which characteristics would you be looking for?  

## Key Performance Indicator (KPI)
1.	Total Restaurants  
2.	Total Consumers  
3.	Average Overall Rating  
4.	Average Food Rating  
5.	Average Service Rating  

## Skills / Demonstrated Concepts
i.	Data Cleaning and Transformation  
ii.	Data Modelling  
iii.	DAX Measures  
iv.	Data Visualization  
v.	SQL  
vi.	Power Query  

 ## Visualization & Analysis

 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-29%20104452.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-29%20104647.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-26%20235202.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-26%20235236.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-26%20235302.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-26%20235324.png)  
 ![](https://github.com/Amarachi180/Restaurant-Ratings-Analysis/blob/main/Screenshot%202025-11-26%20235347.png)  

 ## Analysis
**1.	What can you learn from the highest-rated restaurants? Do consumer preferences have an effect on ratings?**  

The Top 5 overall rated restaurants are a total of seven restaurants, with some of the restaurants' average ratings tied. These restaurants are all located in closed areas and have no franchise. Some of these Top 5 overall rated restaurants provide no alcohol service, and some also provide wine and beer as alcohol service. Amongst these restaurants, more offer lower pricing and practice a no-smoking policy in their restaurants. Morelos and San Luis Potosi are the common states where these restaurants are located.
Three of the top 5 overall-rated restaurants are also among the top 5 restaurants' food ratings, and five restaurants from the top 5 overall ratings also appear among the top 5 restaurant service ratings.
Most customers are dining at restaurants that do not match their preferred cuisine. While average ratings (overall, food, and service) between Matched and Unmatched are similar, the low number of Matched cases (6.68%) suggests limited evidence to conclude that consumers’ preference has no effect. 
Out of the total restaurants analyzed, only 95 restaurants have cuisine information available, which accounts for 71.3% of all restaurants. Therefore, the analysis addressing consumer preferences and their effect on restaurant ratings is limited to this subset of restaurants. As a result, insights related to consumer preference alignment are drawn only from restaurants with known cuisine types, ensuring the validity of the matching process.

**2.	What are the consumer demographics? Does this indicate a bias in the data sample?**  

There is a clear demographic bias in the data sample. Over 70.71% of consumers are young adults (18–25), 89.86% are single, and 81.88% are students, with no children and mostly medium or low budgets. 
These findings strongly suggest that the data collection was centered around a narrow demographic — likely students or young professionals — and lacks diversity in age, marital status, income, and life stage. As such, the insights derived from this dataset should not be generalized to a wider consumer population.  

**3.	 Are there any demand & supply gaps that you can exploit in the market?**  

Supply and demand volumes aren't captured in the dataset, so exploiting demand & supply gaps in the market can’t be done.  

**4.	If you were to invest in a restaurant, which characteristics would you be looking for?**  
**Restaurant proportionality against restaurant characteristics:**  

About 88.46% of the restaurants in the dataset are located in closed areas, suggesting this setup is more common and possibly preferred. Only 11.54% are open-air restaurants, indicating a smaller market presence. About 83.08% of restaurants are not franchise-operated, and the remaining 16.92% are. Among the four cities in Mexico, 64.62% of restaurants are in Saint Luis Potosi, followed by Ciudad Victoria (17.69%), Cuernavaca (16.15%), and Jiutepec (1.54%), showing that Saint Luis Potosi is heavily restaurant-oriented. Saint Luis Potosi, as a state, is also dominated by restaurants, with 64.62%. About 52% of restaurants in Mexico have medium pricing levels, followed by low-level prices (46.15%) and high-level prices (19.23%). 66.92% of restaurants do not serve alcohol, followed by wine and beer service (26.15%), and full bars (6.29%), indicating most do not provide alcohol options. 73.08% of restaurants maintain a no-smoking policy, while 18.46% offer smoking sections, 6.92% allow smoking inside the restaurant without a designated area, and 1.54% permit smoking in their bars. This shows that most restaurants strictly prohibit smoking in enclosed areas. 50% of restaurants do not offer parking privileges, followed by 35.38% that have parking spots, 12.31% that offer public parking, and 2.31% with valet services. 25% of restaurants, out of 73% that provide cuisine options, serve Mexican cuisine.  

**Restaurants’ category average performance focusing on the overall average rating:**  
Restaurants in Cuernavaca have higher overall ratings than other restaurants in their respective cities. Morelos State holds the highest average overall rating for restaurant performance. Restaurants that offer full bar services, valet parking, permit smoking, are franchise-operated, have higher prices, and are located in enclosed areas tend to have higher overall ratings.  

**You can interact with the live visualization here:**
[HERE](https://app.powerbi.com/view?r=eyJrIjoiYmEyMGExMjAtNTJiNC00MzVlLWIxMjQtMTVlY2Q0YTc4YzY2IiwidCI6ImEzMWM5OWQ2LTA3MzAtNGNmMy04ZjI2LWJiYmI0YzA3YWYyMSJ9)

## Conclusion and Recommendation  
### Conclusion  
The analysis reveals strong patterns in restaurant characteristics, consumer behavior, and ratings. Highly rated restaurants tend to be located in closed areas, are often non-franchise, and maintain no-smoking and low-price policies. However, restaurants with premium features like valet parking, full bar service, and higher prices also tend to receive better average ratings. There is a clear demographic bias in the data, dominated by young, single students with medium to low budgets, which limits how widely the findings can be generalized. Additionally, due to a lack of supply and demand data, direct market gap analysis was not possible.  

### Recommendation  
1.	Invest in restaurants located in closed areas as they are both popular and often higher rated.  
2.	Target mid to high price tiers where higher service quality and ratings appear, especially in areas like Cuernavaca and Morelos.  
3.	Consider offering alcohol options and valet parking, as these features are associated with higher customer satisfaction.  
4.	Future surveys should collect more diverse and balanced demographic data and include demand-supply metrics to enable deeper market opportunity analysis.  
