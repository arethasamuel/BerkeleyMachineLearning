# BerkeleyMachineLearning

Required Assignment 5.1: Will the Customer Accept the Coupon?

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
