
# Part I: Brainstorming

## Idea I: Fantasy Curling League

We are making a database that can be used to supplement a fantasy curling league. Currently, there are websites that claim to host a fantasy league, but they are very limited in statistics (only stating win/loss) and capabilities (poor trading functions). Our database will be much more in depth, comparing statistics such as domestic vs. international win percentage and standard deviation of scores, allowing league participants to be better informed and more engaged. As we accumulate more data, we can start to see which players are in high demand and provide that information back to the users. Additionally, since curling is a team sport, we can use our data to allow certain players to “boost” other players based on a calculated “chemistry” if they are drafted onto the same team.

It would have five tables: Competitor name and team, average score per round in international matches (constrained to be between 0-8, which are the minimum and maximum scores in a single round), average score per round in domestic matches (0-8), overall standard deviation of scores, and match win/loss (real time/dynamic).

Goal: Our goal is to provide easy-to-understand data that allows participants in fantasy curling leagues to make more informed decisions. With this in-depth data, participants can better predict competitor performance and more effectively develop teams and trade deals. With real time roster updates, it will be easy to determine weekly player additions and drops. Daily use of this product will mirror that of a fantasy football database. The database will be organized by competitor entities (each containing individual attributes) and will allow users to compose teams and “compete” based on a player’s statistics at a given time. The data included in the tables will give both old and new curling fans a complete picture of how reliable various players are to choose from. 

 

## Idea 2: Tracking Penn State 

We have heard a lot of people state generalities that aren’t necessarily backed up by data--a large majority of engineering majors are males, students with French and Francophone Studies majors struggle to find jobs, or that students with marketing majors have inflated GPAs. We want to develop a database that tracks enrollment and success amongst different majors, but also takes into account external factors such as gender, socioeconomic status, extracurricular involvement, etc. This will help us better understand the dynamic at our school and to identify potential issues in our academic programs.

Tables would include student ID (nine digit number), declared major, gender the student identifies as (male/female/other/prefer not to answer), number of clubs involved in at PSU (0-25), GPA, which is the dynamic variable (0-4.0). 

Our goals are to analyze the data at Penn State so that we can gain better insights into broad generalities. Additionally, we can start to look for patterns that can tell Penn State where they need to invest additional resources. For example, if we find that students in the IST major tend to have a higher GPA when they are involved in at least two clubs, Penn State can require professors of IST 110 to introduce students to different opportunities for involvement. We do not anticipate this product to be utilized daily; rather, we hope to gather data and present it to the Penn State administration so that they can make more informed efforts to maintain a high level of equality and academic success amongst all of the colleges at the University. 


## Chasing Starbucks

The Starbucks in the Paterno Library is one of the busiest campus locations in the country. It is incredibly difficult to manage due to thousands of customers coming through every day. Although stock is sometimes adjusted to meet demand, the store is constantly running out of ingredients. Thankfully, there are patterns in the spending habits of Paterno Starbucks patrons that can help management in preparing the store’s stock. We want to develop a database that tracks the amount of ingredients at each drink station (iced teas and refreshers, frappuccinos, espresso bar, and iced coffees). We will not be including brewed hot coffees or food items in our data in order to simplify for this project.

The five tables will include quantity of tea and refresher ingredients at opening versus closing and days where the store ran out, quantity of frappuccino station ingredients at opening versus closing and days where the store ran out, quantity of espresso bar ingredients at opening versus closing and days where the store ran out, quantity of iced coffee ingredients at opening versus closing and days where the store ran out,sales of each drink type and most popular drink (real time).

Our goal is to track spending and purchasing patterns so that this location can make adjustments to their management and stock as needed. These locations are difficult to manage due to the sheer volume of customers, so intelligent tracking of sales is a must. Ideally, this data would be looked over by store managers and used to determine how many of each ingredient needs to be repurchased with each order, as well as what drinks are selling the most and will need the most “wiggle room” for extra ingredients. Longer term tracking can be used to determine the seasonality of items so that the stores can prepare for different parts of the year. 


```python

```
