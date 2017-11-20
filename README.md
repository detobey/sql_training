# SQL Training: Analyzing the Titanic disaster
This project introduces concepts of insight discovery to data analysts by answering questions using the supplied data set.

#### Introductory Questions
1. How many people were in 1st, 2nd, and 3rd class?
2. How many people died? Express this as a percent calculated by query.
3. What percentage of the dead were identified?
4. How many 1st, 2nd, and 3rd class passengers survived? Express answer as sum calculated by query.
5. How many men, women, and children survived?
6. What was the average fare by class?

#### Intermediate
7. Is there a relationship between deck level and survival? Your answer should include an r-value analysis.
8. Were women and children really prioritized ("women and children first!") for lifeboats? Use as much data as possible to support your answer.
9. Quantify the relationship, if any, between class and survival.
10. Identify the lifeboats not filled to capacity. Within that subset, what are the common attributes of those lifeboat passengers?

#### Advanced
11. Identify the passenger-types that have the highest and lowest chances of survival. Your results should be presented as predictive models supported by data.

## titanic.csv: Titanic disaster passenger dataset
Between April 14 and 15 1912, over 1500 people lost their lives in the most famous maritime disaster of the time. Popularized in print, book, and film, the sinking of the Titanic generated siginficant controversey for the role wealth played in survival and triggered new legislation around evacuation and disaster planning on ships. This data set contains a full passenger list, numeric representation of their relationships, and their survival status.

Dimension | Type | Description
--------- | ---- | -----------
id|int|Dataset passenger id
pclass|int|Ticket class, considered a proxy for socio-economic class*
survived|int|Did the passenger survive?**
name|varchar|Passenger name: Last, Honorific First Middle
sex|varchar|Sex: male, female
age|float|Age in years, <1 year represented as decimal
sibsp|int|# of siblings and/or spouses aboard the Titanic
parch|int|# of parents and/or children aboard the Titanic***
ticket|int|Titanic ticket number, there can be multiple passengers on a sigle ticket
fare|float|How much passenger paid for ticket, GBP
cabin|varchar|Cabin number
embarked|varchar|Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton
boat|varhcar|Lifeboat number; collapsible boats were letttered****
body|int|Body identification number
homedest|varchar|Home or destination; where the passenger indicated they were ultiamtely travelling or returning to

<sub>
* 1st class were on upper decks, 2nd class on middle decks, 3rd class on lower decks<br>
** 0 = No, 1 = Yes<br>
*** A child travelling with a nanny would be parch=0<br>
**** https://en.wikipedia.org/wiki/Lifeboats_of_the_RMS_Titanic<br>
</sub>
