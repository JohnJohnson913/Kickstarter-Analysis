Kickstarting with Excel

## Overview of Project

Louise is coming close to crowd funding her new play and she needs to understand two things.  

1.  Louise wants to understand successful outcomes based on the funding goals established.
    Knowing this will allow her to most likely set a successful goal.

2.  She needs to understand plays have during the 12 months of the year.  
    Knowing this information will guide her decision of when to launch her new play.


### Purpose

The purpose is to the use the information set I have at my disposal to assess the most successful paths for both of Louise's objectives

## Analysis and Challenges

The analysis is completed in excel, using two seperate sheets to assess the best situation for both questions.  

To accomplish the first objective I used a pivot table isolating the releveant information, and then using a pivot chart
to best visualize when the new play should launch.

To accomplish the second objective, I used a countif statement such as " =COUNTIFS(Kickstarter_Challenge!D:D,"<1000",Kickstarter_Challenge!F:F,"failed",Kickstarter_Challenge!R:R,"plays") " function to 
count the successful, failed and canceled kickstarter campaign counts from the main data set.  
I then calculated percentage of successful, failed and canceled plays to develop an additional visual based in excel charts.

### Analysis of Outcomes Based on Launch Date

To accomplish the first objective I used a pivot table isolating the releveant information, and then using a pivot chart
to best visualize when the new play should launch.

### Analysis of Outcomes Based on Goals

To accomplish the second objective, I used a countif statement such as " =COUNTIFS(Kickstarter_Challenge!D:D,"<1000",Kickstarter_Challenge!F:F,"failed",Kickstarter_Challenge!R:R,"plays") " function to 
count the successful, failed and canceled kickstarter campaign counts from the main data set.  
I then calculated percentage of successful, failed and canceled plays to develop an additional visual based in excel charts.

https://github.com/JohnJohnson913/Kickstarter-Analysis/blob/0d6a94d71c91c0495fcbdb1ecbcc23cfa3e366d6/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered

Though the exercise was accomplished successfully, it would be mindful to pay close attention to the formulas, and ensure that all items are spelled correctly and that accurate syntax is used.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1.  The best month to launch the new play would be the month of May.  Though failed plays are relatively high, successful plays more than double plays that fail.  This will be the best time to launch
2.  It would not be adivsed to launch a new play in the month of December.  Plays launched in december nearly fail as often as they succeed.

- What can you conclude about the Outcomes based on Goals?

1.  The best goals to have would be plays that have goals set between less than $1,000 and $14,999 as well as $35,000 to $44,999.  Both ranges have a success rate greater than 50%, but a goal below %5,000 
gives the highest percentage with at least a 72.61% success rate.

- What are some limitations of this dataset?

The limitations I noticed are:

1.  The data only represents information from kickstarter.  Many projects have different types of funding, and would provide that same insight we were looking for but were not available in the data.
2.  The timeframe was for only 7 years.  This may seem significant, but for many of the years a recession was occuring.  The arts are often the first out the door for consumer discretionary spending.

- What are some other possible tables and/or graphs that we could create?

The other charts that could be helpful may be a radar chart for th outcomes based on goals.  Due to the fact the data has a start and stop point it too would clearly outline areas of potential success and failure.
For the Theater outcomes by Launch Date, a stacked OR clustered column chart is often easier to visualize this type of information.


