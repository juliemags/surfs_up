# surfs_up

# Overview
This project is focused on researching the climate of Hawaii to determine the practicality of operating the Surf and Ice Cream Shop and be profitable throughout the year. We assume that the Surf and Ice Cream shop will perform better (business is more sustainable) if the weather is better (higher temps, lower rainfall). To determine the sustainability, we used a variety of programs to filter through a large amount of data focused around Oahu, HI. We used SQLAlchemy, Python, and Pandas to pull the temperatures during the month of June and December to measure weather during the summer and winter months. We measure temperature in Degrees Fahrenheit. 

# Results
![June Results](Resources/June_Temps.png)
### June
After 1700 measurements, we can see that the average temperature in June is 74.94 degrees with a range of 73-77 degrees for the middle 50% of data points. The maximum temperature is 85 degrees and the minimum temperature was 64 degrees. 

### December
After 1517 measurements, we can see that the average temperature in December is 71.04 degrees with a range of 69-74 degrees for the middle 50% of data points. The maximum temperature is 83 degrees and the minimum temperature was 56 degrees. 

### Comparison
- Number of Measurements: There is a relatively similar number of measurements between June and December, with only 183 less data points in December than June
- Average Temperatures: The average temperatures are only about 3.90 degrees different, with June having a higher average than December. 
- Standard Deviations: June had a standard deviation of 3.257, while December had a standard deviation of 3.746. This means that December varies in temperature more than June. June's temperatures are more conistently closer to the mean than December's temperatures. 
- Ranges: For the middle 50% of data points, June's data range was 73-77 degrees (Range of 4 degrees). December's middle 50% of data points had a range of 69-74 degrees (Range of 5 degrees). This is consistent with the larger standard deviaiton that December measured. 
- Maximum Temperature: June and December had very similar maximum temperatures, with June measuring 85 degrees and December measuring 83.
- Minimum Temperature: The minimum temperatures between June and December were very different, with June measuring a much higher minimum temperature (64) than December (56). 


# Summary
- Average Temperatures: The average temperature is higher in June than December, which is not a surprise to me. In the United States, Winter is during the months of roughly October to March (containing December), so we expect temperatures to be colder than Summer. 
- Standard Deviation and Ranges: December having a larger range and standard deviation is very interesting to this study, as it has a more volatile climate. This makes it more difficult to make a true call on the sustainability of business in this month. 
- Maximum and Minimum temperatures: I was surprised to see that December and June had relatively similar Maximum temperatures. I was not surprised to see December have a lower minimum temperature. 

In my history as a consumer, I know I have purchased ice cream when temperatures were as low as 64 degrees. I cannot say the same for 56 degrees (most people are wearing jackets in that cast). In my opinion, I cannot see any evidence that implies an absolute certainty to the sustainability of the business in December. June has more consistently high temperatures, and the water would be warmer in June, so surfing and ice cream seem to be viable businesses in the month of June. In order to support these claims, we would want to view more data on the subject. In this case, we pulled in data points relating to rainfall in the months of June and December. 

### Rainfall
- Average Rainfall: December saw a higher average rainfall with .217, compared to June (.136)
- Standard Deviation: December had a higher standard deviation of 0.541, compared to June (0.336)
- Middle 50% Range: Both months had very similar middle 50% data point ranges, with December measuring 0 to 0.15, and June ranging 0 to 0.12. 
- Maximum Rainfall: December saw a much higher maximum precipitation of 6.42, 1.99 higher than June (4.43)
- Minimum Rainfall: Both months shared the same minimum of 0

Based on these precipitation statistics, December sees higher amounts of rainfall on average compared to June. This adds support to the claims that December is not a viable month for Surf and Ice Cream business. 

Beyond temperatures and rainfall, this study would be more comprehensive and give more straightforward guidance to the business if metrics around tourism and population were measured. I would also be interested to know if the majority of consumers were permanent Oahu residents, or if they were tourists from other areas of Hawaii or around the world. If the majority of business comes from tourism, it would be beneficial to measure the tourism rates throughout the year to determine on a weekly or monthly basis what times of year are the most sustainable for business. 
