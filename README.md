# Kickstarting with Excel

## Overview of Project:
- A visualization of how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges:

- I perform my analysis by going through the dataset and creating by creating a pivot table for **Outcomes based on luanch dates** and using that data to create a line chart to give a better visualization of which months yield a successful or failed result based on the luanch date. I also performed an analysis on the dataset to create a line chart that displays the **Outcomes based on goals** to see how campaign perform based on their goals. The only challenge that I encountered was, when I was making the line chart for **Outcomes based on goals** I mistakenly compared the pledged column to the goal set. My orginal formula was   '=COUNTIFS(kickstarter!E:E,"<=1000",kickstarter!F:F,"successful",kickstarter!R:R,"plays")' & by the end I knew the results were not what I was looking for. I changed my formula to '=COUNTIFS(kickstarter!D:D,"<=1000",kickstarter!F:F,"successful",kickstarter!R:R,"plays")' to get me the results I was looking for which was to compare the goal to the outcome result, not number.

Here's what the line chart looked liked with the wrong formula: <img width="1440" alt="Screen Shot 2021-08-02 at 4 42 11 PM" src="https://user-images.githubusercontent.com/86446656/127936388-d3374b75-50da-4854-abda-bcd9775a12e3.png">

## Results

- The two conclusions that I can drew about the **Outcomes based on Launch Date** was that the best performing campiagns had launch dates that where in the spring months. Another conclusion that I drew was that the worst time for campaigns to launch were in the fall and winter months.

- What I concluded about the Outcomes based on Goals was that patrons are more likely to give to campaings with a goal or $9,999 or less and that most campaings with high goals were not met; in fact a few high goal campaigns were not even donated to.

- Some limitations of this dataset are that are some columns need to be reformatted in order to understand and that there is a limited amount of information that can be collected form the data set. I would like to know the profile of the patrons or donaters to see if a certain demographic where more likely to give vs another and why.

- Some other possible tables and/or graphs that we could create is maybe a pie chart to display all campaigns and how they compare to one another in terms of what genre, location or other factor made it possible to influences desirable outsomes.
