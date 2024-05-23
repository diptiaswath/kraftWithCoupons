In the context of the Berkeley HAAS Professional Certificate in Artificial Intelligence and Machine Learning course, this repository explores an analysis centered on data-driven insights for a Problem outlined below.

**Problem Statement - Will a Customer Accept the Coupon?**

**Context**

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaraunt? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

**Goal**

The goal of this project is to use what I have learned  about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

**Problem Analysis and Summary**

This repo hosts the analysis and summary in the below detailed directory structure.

1. [data folder] Dataset from UCI Machine Learning repository 
2. [parent directory] Jupyter Notebook that analysis data set provided with plots and conclusions made on customer acceptance of varied coupon types 
3. [report folder] Summary that highlight differences between customers who did and did not accept the coupons 


****Data Description****

The attributes of this data set include:

****User attributes****

Gender: male, female

Age: below 21, 21 to 25, 26 to 30, etc.

Marital Status: single, married partner, unmarried partner, or widowed

Number of children: 0, 1, or more than 1

Education: high school, bachelors degree, associates degree, or graduate degree

Occupation: architecture & engineering, business & financial, etc.

Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.

Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

Number of times that he/she eats at a restaurant with average expense less than $20 per person: 0, less than 1, 1 to 3, 4 to 8, greater than 8

Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8


****Contextual attributes****

Driving destination: home, work, or no urgent destination

Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with 
time of driving. The user can see whether the venue is in the same direction as the destination.

Weather: sunny, rainy, or snowy

Temperature: 30F, 55F, or 80F

Time: 10AM, 2PM, or 6PM

Passenger: alone, partner, kid(s), or friend(s)

****Coupon attributes****

Time before it expires: 2 hours or one day


