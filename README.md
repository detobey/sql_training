# sql_training
#### titanic.csv: Titanic disaster passenger dataset

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
