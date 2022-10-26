ri# ***Surfs Up : Working with SQLite, SQLAlchemy and Flask***

## Project Overview

### Overview:

An entrepreneur of a Surf and Shake shop asked us to aid him in his business proposal that will be presented to potential investors. In this business plan, he is expected to give a full analysis of data for the island of Oahu, Hawaii which will be the location of the shop. We are helping them prepare their business plan by presenting a report that includes detailed weather data of the island, such as temperature and precipitation, along with some statistical anlaysis of these two categories to showcase that the island would be the best location this invesment could be at.


### Purpose:

The purpose of this report is to analyze the weather data for the location of Oahu, filtering our data to be able to report back only the statistical analysis for the months of June and December. The purpose behind this filtering is to show the investor that the Surf and Shake shop will be able to sustain itself year-round and minimize any monetary losses. To expedite our report, we are asked to use SQLite and SQLALchemy functions to filter our data and report back our statistics as a Data Frame.


## Results

After using functions of sqlalchemy and pandas, we were able to filter out our data for the months of June and December. In total, we retrieve a *1,700* temperatures for the month of June and *1,517* temperatures for the mont of December. The following are the statistics for both months:

June:

![jun_temp](https://user-images.githubusercontent.com/111034667/197952771-16903980-4edb-4f63-bef0-329045247ebb.png)

December:

![dec_temp](https://user-images.githubusercontent.com/111034667/197953974-fd2a637c-4010-4417-a30b-28106af4b5cb.png)

 After observing the tables above, we can conclude the following three points:
 
- Although both months contained similar temperatures overall, the temperatures of June were higher than the temperatures of Decembre. The mean temperature of June was 74.94 degrees Fahrenheit with a standard deviation of 3.25, while the mean temperature of December was 71.04 degrees Fahrenheit with a standard deviation of 3.75.

- Overall, June temperatures varied less than December temperatures. This can be observed if we compare the minimum and maximum values to their means; June's minimum and maximum temperature were rougly 10.06-10.94 degrees away from the mean , while December's minimum and maximum temperature were roughly 11.96-11.04 degrees away from the mean. Nonetheless, there is a high probabillity that both datasets contain outliers.

- based on the statistics found above, it is highly likely that the shop will experience a higher amount of customers during the month of June than Decemeber since its temperature are higher.

## Summary

The upcoming Surf and Shake shop has a high probabily of sustaining itself year round based on the statistics found above. The entrepreneur now has an analysis remport that supports his claim that this business will be succesful, and with the help of investors this establishment will be successful. The temperatures for both months showcased that the island contains a climate that is ideal for this type of business, and the probability of monetary losses due to climate will be small. To further support this claim, we have included two additional queries that deal with precipitation. It is ideal to consider looking into the precipitation of both months to see what is the probability that the warm temperaturesd will be affected by rain,snow, hail amongh other forms of water release. If the numbers of precipitation are small, then the chances of the amount of customers declining within the month due to weather will be limited.
