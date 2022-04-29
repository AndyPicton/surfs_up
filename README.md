# surfs_up
## Overview of the analysis
W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. I used SQLite, SQLAlchemy, and Flask to build a SQL database. I also wrote and executed Python code in a Jupyter notebook to create weather graphs.

## Results
 - Overall June has higher temperatures, which is to be expected. The average and high are both similar to Decembers.
 - December was warm enough the whole month for surfing and ice cream, the lowest it got was 56 degrees.
 - Both months weather stayed pretty consistent with a standard deviation of 3.26 and 3.75 respectively.
 
![image](https://user-images.githubusercontent.com/99369565/166078047-c964dee7-3ef0-4b25-82c5-c705cd4684aa.png)

![image](https://user-images.githubusercontent.com/99369565/166078169-d7f7c6e0-7463-48d5-a21d-ea13697cec65.png)


## Summary
Looking at the weather data for June and December in Oahu, Hawaii, I can conclude that it is an excellent city to open a surf and ice shop. With highs of 85 in June and 83 in December, during the high period, we will have plenty of business to keep us busy and open year round.

Although weather temperature is a great indicator for business, we will still need to account for rain. To gather more information about overall weather I would write queries based on precipitation. 
