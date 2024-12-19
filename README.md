# BerkeleyMachineLearning

Required Assignment 5.1: Will the Customer Accept the Coupon?

![Link to my notebook](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/Module5.ipynb)

brief report that highlights the differences between customers who did and did not accept the coupons.

Summary of Findings

I conducted a basic analysis of the coupon acceptance data and found the following insights:

The overall coupon acceptance rate is 56.84%.

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/totalcouponacceptance.png)

The top occupations with the highest coupon acceptance rates are:
Healthcare Support: 69.83%
Construction and Extraction: 68.83%
Healthcare Practitioners and Technical: 67.6%

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/occupation.png)

The most frequently accepted coupons were for **coffee** and **least expensive restaurants**. Additionally, these coupons were most commonly redeemed around **2 PM in the afternoon**.
![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/time.png)

Next, I analyzed the drivers most likely to accept bar coupons. Overall, the acceptance rate for bar coupons was **41%**. Drivers who visit bars more than three times a month were significantly more likely to accept the coupons compared to those who visit less frequently:  

- **Acceptance Rate for Less than 3 Visits per Month**: 37.07%  
- **Acceptance Rate for More than 3 Visits per Month**: 76.88%

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/frequency.png)

I then compared the acceptance rate of bar coupons between two groups: drivers who visit bars more than once a month and are over 25 years old versus all other drivers. The findings are as follows:

Acceptance Rate for Drivers with More than 1 Visit and Over 25 Years Old: 69.52%
Acceptance Rate for All Other Drivers: 33.50%

I further analyzed the acceptance rate of bar coupons among drivers who visit bars more than once a month, had passengers other than children, and worked in occupations other than farming, fishing, or forestry. The results are:

Acceptance Rate for Drivers Meeting These Criteria: 71.32%
Acceptance Rate for All Other Drivers: 29.60%

Next, I visualized the occupational data of the drivers to determine if specific occupations were more likely to influence the use of bar coupons. This analysis aimed to identify trends in coupon acceptance based on occupational groups.

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/occupation2.png)

Next i compared  the acceptance rates between those drivers who:
go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
go to bars more than once a month and are under the age of 30 OR
go to cheap restaurants more than 4 times a month and income is less than 50K.

This Group's acceptance rate was 56.96%

### Insights on Bar Coupon Acceptance

Drivers who accept bar coupons exhibit several common characteristics:

1. **Frequency of Bar Visits**:  
   - Regular bar-goers (visiting more than three times a month) are significantly more likely to accept bar coupons compared to those who visit bars less frequently.

2. **Age and Bar Visits**:  
   - Drivers aged 25 and older who visit bars more than once a month demonstrate a higher likelihood of using bar coupons.

3. **Passengers and Occupation**:  
   - Drivers with passengers other than children and occupations outside farming, fishing, or forestry are more inclined to use bar coupons.  
   - Occupations such as **Architecture and Engineering**, **Production**, and **Healthcare Support** show a particularly strong correlation with bar coupon acceptance.

4. **Additional Influencing Factors**:  
   - **High Bar Visit Frequency**: Drivers who visit bars more than once a month, combined with the absence of children as passengers or being under 30 years old, are more likely to accept bar coupons.  
   - **Inexpensive Restaurant Visits**: Frequent visits to inexpensive restaurants (4+ times per month) paired with lower income levels (<$50,000) also increase the likelihood of bar coupon usage.

---

### Hypothesis:  
Drivers who accept bar coupons tend to be regular bar patrons, often accompanied by companions other than children, and are more likely to work in professions outside farming, fishing, or forestry. Occupations such as **Architecture and Engineering**, **Production**, and **Healthcare Support** are particularly associated with higher coupon acceptance. Young bar-goers who visit bars frequently are also more inclined to use these coupons. Additionally, patrons with lower incomes who frequently visit inexpensive restaurants are more likely to accept bar coupons.  

This combination of lifestyle, demographics, and occupation suggests a clear profile of drivers who are most responsive to bar coupon offers.

--- 
**Analysis of Users that accepted Coffee Coupons**
Next, I analyzed the data for coffee coupons and found that the overall acceptance rate was **49.92%**.

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/coffee.png)

I then compared the acceptance rates for coffee coupons between two groups:  

- **Drivers who visited a coffee house 3 or fewer times a month**.  
- **Drivers who visited a coffee house more than 3 times a month**.  

The analysis revealed the following acceptance rates for coffee coupons:

Drivers with fewer than 3 coffee house visits per month: 44.96% acceptance rate.
Drivers with more than 3 coffee house visits per month: 67.50% acceptance rate.


Next, I compared the acceptance rates for coffee coupons between the following groups:

Drivers who visit a coffee house more than once a month and are younger than 40 years old, versus all other drivers.

The analysis showed the following acceptance rates for coffee coupons:

Drivers with more than 1 coffee house visit per month and under 40 years old: 66.71% acceptance rate.
All other drivers: 40.45% acceptance rate.

The analysis of coffee coupon acceptance based on age revealed the following:

Drivers younger than 40 years old: 51.27% acceptance rate.
Drivers 40 years old and above: 46.33% acceptance rate.
This indicates that younger drivers are slightly more likely to accept coffee coupons compared to older drivers.

I also created a visualization showing the count of coffee coupon acceptances segmented by the age of drivers. This plot helps to identify trends and patterns in coupon acceptance across different age groups. Below is the count.  Notice the younger drivers have a higher acceptance rates.

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/coffeecountage.png)

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/coffeecouponagerate.png)

I also created a graph to visualize coffee coupon acceptances across various occupations. This analysis highlights which occupational groups are more likely to accept coffee coupons.

![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/coffeecountoccupation.png)


Here's an analysis with the acceptance rate of each occupation. 
![alt text](https://github.com/arethasamuel/BerkeleyMachineLearning/blob/main/images/coffeerateoccupation.png)

Based on the analysis of the coffee coupons data, drivers who accepted the Coffee House coupons appear to be younger (under 40), with students and those in healthcare industries showing a particularly higher acceptance rate. 

While frequent coffee house visits (more than 3 times a month) correlate with higher acceptance, the age factor also affects the acceptance rate.  

In other words, youth, regardless of how often they visit coffee houses, age is one predictor of coupon acceptance, followed by occupation.  Building & Grounds cleaning maintenance, Students, Healthcare workers, and Transportation are among the top 5 professions to use the coffee coupons.

Age Influence: Students, who typically fall into younger age groups, may have lifestyles that align with higher coffee consumption. This likely contributes to younger drivers being more inclined to accept coffee coupons.

Occupation Influence: Occupations that demand higher levels of alertness or long working hours—such as healthcare workers, drivers, or those in technical roles—could naturally correlate with a higher acceptance rate for coffee coupons. These individuals may view coffee as a necessity to stay focused and energized.
