# CS7180_SpecialTopicsInAI_Sum2019
# Ryan Martin

### Assignment 1 [99/100]
```
1. 10/10
2. 10/10 the code for dataframe creation could be simplified.
3. 9/10 aggfunc='count'instead of aggfunc='sum' since we are selecting the movie with most rating not highest rating.
4. 20/20 
5. 30/30
6. 20/20

[Comments: Well done and nice plots!]
```

### Assignment 2 [100/100]
```
1.1 (statistics) 10/10
1.2.1 (histograms) 15/15
1.2.2 (box plots) 15/15

2.1.1 (number of features) 5/5
2.1.1 (fill missing nominal) 5/5
2.1.1 (interpolate missing numeric) 5/5

2.2.1 (standardize) 10/10
2.2.2 (box plots) 10/10

2.3.1 (multal info) 10/10 
2.3.2 (top 5 features) 10/10 
2.3.3 (correlation sign) 5/5 Great work and discussions using linear regression. One question 
is to think about the negative correlation, where a negative coefficient of a feature may 
indicate a strong dependency of the class on the feature.

[Comments: Well done!]
```

### Assignment 3 [90/100]
```
1.1.1 (top 5 1-itemsets) 10/10
1.1.2 (top 5 2-itemsets) 10/10
1.1.3 (highest support for 1-itemsets) 5/5
1.1.4 (highest support for 2-itemsets) 5/5

1.2.1 (top 5 rules) 10/10
1.1.2 (top items) 10/10


2.1.1 (encoding) 15/20 Drop all continous columns including 'age', 'capital-gain', etc.  
2.1.2 (metric=confidence) 5/10  It is harder to follow in the discussion. 
			"the highest confidence of 1.2"??? Confidence is a probability so it is always smaller than 1!
2.1.3 (metric=lift) 10/10 Nice distribution plot!
2.1.4 (compare) 10/10 

For the discussions, I am not sure how you define if two sets are seemingly independent. To me,
"married men with Bachelors degrees are likely to make over 50k a year, ", where 
the antecedent and consequent are sort of dependent as a degree is likely to help a person earn more.
 
[Comments: Great work! It is helpful to work on some calcuations of confidence like in the quiz 1.]
```

### Assignment 4 [100/100]
```
1.1.1 (scatter matrix) 15/15 nice plot!
1.1.2 (k-means) 15/15 
1.1.3 (cross-tabulation) 20/20

1.2.1 (mutual information) 25/25
1.2.2 (dendrogram) 25/25

[Comments: Great work! ]
```

### Assignment 5 [109/100]
```
1.1.1 (largest temperature range) 5/5 
1.1.2 (most and least polluted) 5/5 
1.1.3 (average temperature) 5/5
1.1.4 (hottest summer and coldest winter) 5/5
1.1.5 (largest amount of missing data) 5/5

1.2.1 (line chart of temp vs date) 4/5 Is there a noticeable seasonal pattern?
1.2.2 (boxplot of temp grouped by month) 5/5
1.2.3 (scatter plot) 5/5
1.2.4 (plot of PM for all cities) 5/10 Range of y is not correct, why all PM's < 110?

1.3.1 (linear regression) 20/20 
1.3.2 (train and evaluate) 20/20
1.3.3 (predict other columns) 5/10 Temp is easier to predict than PM

BONUS 20/20
[Comments: Great work!]
```


### Quiz 1  [7.5/10]
```
1. 4/4
2. 2/2
3. 1.5/4 wrong values.

[Comments: Please reivew the definition/formular of confidence]
```

### Quiz 2  [5/10]
```
1. 2/3 descriptive?
2. 0/3 how does it misclassfiy when k is too small or too large?
3a. 1/2 because the output is numeric
3b. 2/2

[Comments: Please review KNN algorithm for Q2.]
```

### Midterm  [62/100]
```
1. 5/10 Based on your explanation, the answer should be MAR.
2. 3/10 The first principal component points vertically because it generates the greatest variance on the projection.
3. 10/10
4. 10/10
5. 2/10 incorrect clustering
6. 5/10 how to decide whether they are good or poor clusters based on silhouette coefficient?
7. 4/10 incorrect calculations
8. 5/10
When k = 1, no instance in right set will be predicted wrongly.
When k = 3, the point at (1, 0) will be predicted wrongly.

9. 10/10
10. 8/10 Do you need train/test split for the algorithm?

[Comments: Please review the algorithms/concepts for Q2, Q5/7.]
```

### Proposal  [95/100]
```
I like that for your project you are exploring this topic. While there are many similarities 
between sentiment analysis and classification, there are also some unique features about 
that particular set of data science techniques that you might find interesting to explore.

I was a bit confused when reading the first few sections of your proposal as it was hard 
for me to tell exactly what it is tat you are attempting to do. You mentioned that your app 
"will simply allow a user to access data from Twitter’s API and gain insight on the general 
public’s mood", but you also mentioned attempting to predict election results, correlating 
users' sentiment to the stock market, and also that, generally, "The problem I will be 
solving in my project is how to create the most accurate and feasible machine learning model 
for sentiment analysis". For your final poster/presentation, 
I would make sure to come up with a few very concise and clear sentences describing the 
purpose of the application you came up with and why it is useful/novel.

As I mentioned to you in class, there's a chance that the core-ML model conversion portion 
of your proposal is a tad overly ambitious, so I would treat that as a potential "bonus", 
which you can get to once everything else is in place. The interface also seems a bit broad. 
How exactly would you query data for an open ended hashtag provided by the user (e.g., flu) 
in real time and use it as input to your sentiment analysis model? If you have something 
in mind or if methods for doing that already exist (i'm not super familiar with that type 
of work / data), let us know. Otherwise I think it may be wise to restrict your search space 
manually in some way.

Looking forward to seeing what you come up with! Let us know if you need help prioritizing 
the different portions of your work to make sure you have something that you're happy with 
at the end. 
```

### Final  [80.5/100]
```
1. 10/10
2. 8.5/10
3. 10/10 misclassification rate = 0.3

4. 5/10 
p(credit risk = good| cj) != p(good|100) * p(good|low) and p(good|100) = 1 and p(good|low) = 1/3
p(credit risk = good| cj) = p(100|good) * p(low|good) *P(good) /P(cj)

5. 1/10 expected to include calculations for all four possible splits 
6. 6/10 stacking is better in the case
7. 10/10
8. 10/10
9. 10/10
10. 10/10

[Comments: Great work!]
```