# Fifa19_EDA Data Exploration

## Dataset

* Fifa19 is a soccer video game and this data is about players in it.

* 18 columns , 18,207 rows

* Dataset link : https://www.kaggle.com/winterbreeze/fifa19eda

* Slideshow link : https://onedrive.live.com/?authkey=%21ALGw6b9QejbDdQA&id=EEDE57B642F6D62E%211550&cid=EEDE57B642F6D62E
***Note : You have to download the slideshow file to open it successfully.

Columns :
* ID                          * Name    
* Age                         * Nationality    
* Overall                     * Potential    
* Club                        * Value    
* Wage                        * Preferred Foot    
* International Reputation    * Skill Moves    
* Position                    * Joined    
* Contract Valid Until        * Height    
* Weight                      * Release Clause

## Summary of Findings

In the exploration, I found that there were :

- About 75% of players' values are under 2100.

- Player ages distribution is right skewed.

- Player heights, weights, potential_power almost normally distributed.

- Positive relationship between player value & potential power.
  Notice the exponential growth in player value by increasing potential power.

- Positive correlation between international_reputation and potential player power.

- Negative relationship between skill_moves & weight. 
  Notice most heavy weight players aren't skillfull.
  Most skilled players' weights are almost between 140-160.

- Negative correlation between age & potential_power.
  
- Players with high international_reputation are concentrated in ages(25-35) & powers above 80.

## Key Insights for Presentation

- I focused on finding patterns about most columns (After dropping non-interesting columns).

- Most insights are above in "findings" & U can see them in the slides fragments.