
## Author: Qiuyao Liu
## I'm reviewing Yaxuan Yi's citi-bike multi week homework

### 1. Verify your Null and alternative hypothesis are formulated correctly:

#### I didn't see the null and alternative hypotheses you mentioned in the notebook. There are two histograms one presents the number of rides against the age, and the other one is presenting the gender against the number of rides. I guess you have two null hypothesises?
I read your code and command and I recommend to establish the hypothesis and formulas in this way below.
- null hypothesis is "the average travel time of bus route after 1990 is slower or the same as the route before 1990"
- alternative hypothesis is "the average travel time of new bus route is faster than the old route travel time"
#### And there is formulated hypothesis:
##### t0 = travel time of old bus
##### t1 = travel time of new bus
##### H_0 : t0 <= t1
##### H_1 : t0 > t1
##### I suggest to have another year choice here. why choose 1990? I think 1960 or 1970 would be a better choice since large group of people are born around 1950 to 1970.

### 2. Verify that the data supports the project:
#### the reducted data and histogram are good. If your hypothesis is what I mention above, presenting the data in scatter plot would also be a good choice for visualization.

### 3. Choose an appropriate test to test H0 given the type of data, and the question asked:
#### Z-test is the good choice here.
