# Ride Sharing Data Analysis for PyBer using Matplotlib
## Overview
Chart and analyze PyBer ride-sharing data based on the city types of the PyBer platform and uncover the core differences to encourage more consistent operation across each market. 

## Results
### City Summary Analysis
![city_summary_df.png](/Analysis/city_summary_df.png)
- It appears that urban **riders** take more advantage of PyBer’s services than suburban or rural riders. This is likely because car upkeep, parking, and traffic are difficult for individuals to manage in those areas. They also have a higher population density, making them the perfect locations for services that minimize traffic on the road and enable residents to offset the costs of owning a car by assisting those who do not or cannot and charging a fee for travel.
- However, likely due to the reasons I stated above, there seems to be an oversaturation of **drivers** in the urban areas, leading to lower fares for customers and somewhat lower returns for PyBer drivers. 
- Despite driver saturation, the **total fares** collected within the urban cities is over twice as high as those collected in Suburban areas and over nine times higher than that collected in the rural areas. 
- The **average fare per ride** appears to be relatively close for all three city types (within ~$10). However, this suggests that pricing is similarly modeled for each city type, and certain factors (distance from pick-up and drop-off, time spent on a ride) might be improperly weighted in price calculations.
- Drivers in the Rural and Suburban areas have fewer opportunities for fares, but they are probably traveling longer distances between pick-up and drop-off. Hence, the **average fare per driver** is higher outside urban areas.

### Jan-April 2019 Weekly Total Fares
![PyBer_fare_summary.png](/Analysis/PyBer_fare_summary.png)

## Summary
- Incentivize driver sign-up/applications in the suburban and rural centers, enabling drivers to make more money and balance fare prices across the markets.  As PyBer becomes more popular, the need for vast pools of drivers will increase. In addition, suburban or rural residents will see that they can affordably use the service to travel any distance they wish. 
- Initiate a test roll-out of **peak pricing** in the urban areas. This would inflate the consumer price based on many factors (i.e., holidays, weather conditions, time of day, pre-scheduled vs. not, shared ride (with strangers) vs. solo ride, destination, etc.). This implementation could encourage riders to have larger groups before calling a PyBer ride, sharing rides with others, and should increase the amount of money made by both urban PyBer drivers and the company during those times deemed ‘peak.’
- Target advertising campaigns toward consumers outside of the urban areas, perhaps offering discounted admission/tickets to urban destinations/attractions *if* they travel to the city using PyBer. This would a) bring suburban and rural drivers into the urban centers offering them the chance to operate in the city, if they choose, and b) bring far-flung riders into the city to take further advantage of PyBer services by staying a while within the more densely populated cities. 
