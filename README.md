# ANA500-Week-3
Decision Tree classifier.

Using CHIS 2020 survery as data source.  Relied heavily on data dictionary provided by CHIS.

H_0:  There is no statistically significant association between depression and poverty levels after controlling for general health, and current smoking habits 
H_A:  There is a statistically significant association between depression and poverty levels after controlling for general health, and current smoking habits 


DEPRESSION = CHIS2020DATASET(POVERTY, GENERAL HEALTH, SMOKING)

DEPRESSION: Dependent variable. Coded in CHIS as AJ32. Survey question: Feeling depressed in the past 30 days?

Coding: 

    1 = all the time
    2 = most of the time
    3 = some of the time
    4 = a little of the time
    5 = not at all
POVERTY: Coded as POVLL in CHIS. Calculated from respondants annual income and converted to reflect federal poverty levels (PFL).

Coding:

    1 = 0-99% FPL
    2 = 100 to 199% FPL
    3 = 200 to 299% FPL
    4 = 300% FPL and above
GEN_HEALTH: Coded in CHIS as AB1. Tracks respondants self reported general health condition.

Coding:  

    1 = excellent
    2 = very good
    3 = good
    4 = fair
    5 = poor
SMOKING: Coded in CHIS as SMOKING. Tracks respondants self reported smoking habits. If resondant indicated not smoking >= 100 cigarettes in lifetime then categorized as "never smoked regularly."

Coding

    1 = currently smokes
    2 = quit smoking
    3 = never smoked regularly
