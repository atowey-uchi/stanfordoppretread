# Classification of Racial Disparities in Traffic Stops

<b>"A large-scale analysis of racial disparities in police stops across the United States" (2020)</b> uses data from the Stanford Open Policing Project to assess racial disparities in police interactions with the public. They compiled and analyzed a dataset detailing over 60 million state patrol stops conducted in 20 U.S. states.
https://5harad.com/papers/traffic-stops.pdf

In their analysis, Pierson, et al. has <b>five main conclusions</b>:

1. <b>Among stopped drivers—and after controlling for age, gender, time, and location—
[B]lacks and Hispanics are more likely to be ticketed than white drivers.</b>
2. <b>Among stopped drivers—and after controlling for age, gender, time, and location—
[B]lacks and Hispanics are more likely to be <b>searched</b> than white drivers.</b>
3. Among stopped drivers—and after controlling for age, gender, time, and location—
[B]lacks and Hispanics are more likely to be arrested than white drivers.
4. In the case of search decisions, we explicitly test for discrimination by examining both
the rate at which drivers are searched and the likelihood searches turn up contraband. We find
evidence that the bar for searching black and Hispanic drivers is lower than for searching whites.
5. Finally, we find that legalizing recreational marijuana in Washington and Colorado reduced the
total number of searches and misdemeanors for all race groups, though a race gap still persists.

I seek to recreate their results, focusing specifically on Illinois. Given data constaints, I am unable to test conclusions 3 through 5, as the dataset does not include arrests or contraband information, and the dataset does not cover 2020, which is when Illinois legalized marijuana.

The original authors of the paper used logistic regression. For my analysis of conclusions 1 and 2, I recreate their logistic regression results and compare my logistic regression model to two other classification models: Linear SVC and SGD Classifier.
