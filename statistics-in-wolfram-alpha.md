[Home](https://luc-hens.github.io/)

# Using WolframAlpha as a statistical calculator

Author: Luc Hens. 

Version: 20 December 2021

The WolframAlpha web page ([link](http://wolframalpha.com)) is the front end of a knowledge engine that (among many other things) is a powerful and user-friendly statistical calculator. On a smartphone or tablet use the [mobile version](http://m.wolframalpha.com) or the WolframAlpha app (&euro;3.49, iOS and Android), or the Wolfram Statistics Course Assistant app (&euro;2.29, iOS and Android).

| concept                                       |  WolframAlpha code                     |
|-----------------------------------------------|----------------------------------------|
| mean of a list                                | `mean {2, 2, 4, 5, 7}`                 | 
| median of a list                              | `median {2, 2, 4, 5, 7}`               |
| standard deviation of a population (&sigma;)  | `population standard deviation {2, 2, 4, 5, 7}` |
| standard deviation of a sample (*s* )         | `sample standard deviation {2, 2, 4, 5, 7}`
| probability density of the normal distribution | `standard normal distribution`        | 
| area under the normal curve between two values |  `P[-infinity < x < 1]`               |
| area under the Student *t* curve between two values | `P[-infinity < x < 1] for x ~ Student's t distribution with 12 degrees of freedom ` |
| area under the Chi-square curve between two values  | `P[3 < x < infinity]  for x ~ chisquare distribution with 12 degrees of freedom `   | 
| area under the F curve between two values    | `P[3 < x < infinity]  for x ~ F distribution with  n = 5 and m = 2 ` |
|    (*n* = degrees of freedom in numerator; *m* = degrees of freedom in denominator) |  |
| binomial distribution: probability of two successes in three trials with a probability of succes of 1/6 (*k* = 2, *n* = 3, *p* = 1/6) | `probability of 2 successes in 3 trials with p=1/6 ` | 
| roll a die                                   | `roll a die`                            |              
| ..........or                                 | `RandomChoice[{1,2,3,4,5,6}]`           |
| roll two dice                                | `roll 2 six-sided dice`                 | 
| flip a coin                                  | `flip a coin`                           |
| ..........or:                                | `RandomChoice[{'heads','tails'}]`       | 
| flip two coins                               | `flip 2 coins`                          |
| confidence interval for a population proportion (or percentage) | `confidence interval for a population proportion` | 
| confidence interval for a population mean    | `confidence interval for a population mean` |
|  `(only for large random samples)`           |                                         |
| hypothesis test for a population fraction    | `one proportion hypothesis test`        |
| hypothesis test for a population mean        | `one mean hypothesis test`              |
| hypothesis test for two population fractions | `two proportions hypothesis test`       |
| hypothesis test for two population means     | `two means hypothesis test`             |
| sample size                                  | `sample size`                           |

More examples of how to use WolframAlpha for statistical calculations [here](http://www.wolframalpha.com/examples/Statistics.html).

