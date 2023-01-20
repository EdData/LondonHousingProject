# LondonHousingProject
This project is a Data Exploration Project using MySQL, to analyse data regarding the London Housing Market from the Years 2001 - 2018

The output of this project contains 4 different Views, which show the queries I executed in MySQL and further analysis underneath.

-- ------------------------------------------------------------------------------------------------------------------------

View 1: [View_Comparison_Salary_Price_TSold.csv](https://github.com/EdData/LondonHousingProject/files/10467931/View_Comparison_Salary_Price_TSold.csv)

<img width="1187" alt="V_Comparison_Salary_Price_TSold" src="https://user-images.githubusercontent.com/119752965/213745645-b41c3b42-b0f3-466f-86fc-cb5da25210b8.png">

-- From this data, looking at the year 2002. The change in the number of houses being sold (T_Sold_Change column) from the previous year did increase,
-- but did not have the highest change percentage wise compared to the other years, that would be year ending 2006. 

-- This gradual increase shows that in the years 2001-2002 the housing market was in a healthy state.
-- The average salary change from the previous year (Salary_Change column) was not drastic but still shows constant growth.
-- A strong economy growing at a steady pace would boost investors confidence and thus increase demand for the London housing market.

-- This leads to explain why the year ending 2002 had the greatest change in the average price of houses (AVG_Price_Change column).
-- Furthermore, an increase in demand from more people investing in the homes led to a rise in the average price of houses
-- (177.69%) increase in 2002 from previous year).

-- Looking at the year ending 2003, the average price change of homes compared to the previous year was still quite high (112.65%).
-- Which caused the number of houses sold to decrease (88.39%) as the market started to level out (Demand decreasing).

-- Looking at the T_Sold_Change column shows a pattern, where the number fluxuates up above 100% and down to 80/90% in the next.
-- Therefore, the change in the total sold has a direct correlation to the average price change from the years 2003-2007.
-- Until 2008, where there is a great drop to only 48.87% of houses sold compared to the previous year.
-- This is when there was a recession in the UK.

-- ------------------------------------------------------------------------------------------------------------------------

View 2: [View_JobRatios_HousingPrice.csv](https://github.com/EdData/LondonHousingProject/files/10467930/View_JobRatios_HousingPrice.csv)

<img width="1026" alt="V_JobRatios_HousingPrice" src="https://user-images.githubusercontent.com/119752965/213745751-c9e47527-0a8a-4e62-b1c8-2a39a98b2daf.png">

-- Price-to-Income

-- At the year end of 2001, the Price-to-Income ratio is relatively lower than the other years (4.531),
-- Therefore, at the start of 2002 the housing market was still quite affordable and prices were on the rise.

-- Which could help explain why there was a large increase in the number of houses sold in 2002.
-- As houses in London would have been seen as a good investment.

-- From the years 2014 onwards, the price to income ratio is a lot higher than the previous years.
-- Showing that average price of houses is going up relative to average salary, as demand begins to increase again.
-- This shows that people are demanding more money for their houses in London.

-- Homeownership-Rate

-- The Homeownership-Rate shows that the housing market was most successful in 2001/2002, 2004, and also 2006.
-- The earlier years would have been more due to a lower Price-to-Income ratio, as affordable housing meant for a good investment.

-- As stated previously, there was a fluxuation in the housing market before the financial crisis in 2008.
-- Looking at the Homeownership-Rate this enforces our previous point, which states that the demand will level out over the years.

-- When there are years of high homeownership, this number is likely to drop the following year as there will be less negotiation room for buyers.
-- As demand increases from the previous year the prices will rise making homes less affordable.

-- Year ending 2013/2014 the Homeownership_rate starts to increase a lot higher than what was seen in 2008.
-- As stated in the previous point the price-to-income ratio was also increasing amongst these years (8.0004 in 2014)
-- We can conclude that, as prices are increasing relative to wage and houses are being sold at an increasing rate.
-- This shows the London housing market was starting to recover from the 2008 financial crisis in these years.

-- ------------------------------------------------------------------------------------------------------------------------

View 3: [View_Population_HousingAvailability_Price.csv](https://github.com/EdData/LondonHousingProject/files/10467927/View_Population_HousingAvailability_Price.csv)

<img width="1087" alt="V_Population_HousingAvailability_HousingPrice" src="https://user-images.githubusercontent.com/119752965/213745774-d9dcb978-1004-4238-9dd0-28beac47f222.png">

-- Looking at the years from 2001-2018. 
-- Not including what we discovered to be the years where England was recovering from the recession (2008-2013).

-- We can see that the rise in the price-to-income ratio from 2014 onwards has a correlation to the housing availability.
-- As stated previously Population-TotalHousing-Ratio greater than 1 means that there is an overcrowding in an area.

-- Which helps us understand why prices were increasing at such a high rate amongst these years. 
-- Increased demand from lack of housing.

-- It also helps us to understand why people were still so eager to buy at these high prices, 
-- because the housing availability was low.

-- ------------------------------------------------------------------------------------------------------------------------

View 4: [View_PriceToIncome_HomeownershipRate.csv](https://github.com/EdData/LondonHousingProject/files/10467924/View_PriceToIncome_HomeownershipRate.csv)

<img width="1051" alt="View_PriceToIncome_HomeownershipRate" src="https://user-images.githubusercontent.com/119752965/213745794-84026a25-5278-42d0-8b1b-be7f6acb7794.png">

-- From this data we can see that the Job-Density decreased as there was an increase in the Job-Area ratio.
-- This is expected, as when there are more jobs available in an area then more people will be working.

-- The years of 2008-2013 will be included in this analysis, 
-- as it will be proactive to see how the financial crisis also affected the job market in these years.

-- The Job-Density ratio was at its highest the first few years after the recession in 2008.
-- This would be due to pepole being laid off, as companies will have to make budget cuts.

-- Increases over the years in the Job-Area ratio also shows to lead to an increase in the Price-to-Income ratio.
-- This could be due to the fact that an increase in the number of jobs in an area may also increase the popularity of an area,
-- people may want to live closer to work out of convenience or within a thriving economy.

-- Which allows us to understand further why the housing prices were increasing at such a rate in the later years.
-- The higher Job-Area ratio in the later years coincides with the higher AVG_Price of houses from 2014 onwards.

-- ------------------------------------------------------------------------------------------------------------------------

