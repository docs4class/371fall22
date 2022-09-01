# Anscombe's Quartet

You may be asking now, why bother visualizing data if I have all these numbers that will tell me what I need to know about my data? You are correct in saying that statistical data is very useful, and in many cases essential, however visualization is equally as important. Anscombe's Quartet is a statistical phenomenon where four sets of data have very similar statistical properties, but very are completely different when graphed. Let's take a look at the data:


```
#>    x1 x2 x3 x4    y1   y2    y3    y4
#> 1  10 10 10  8  8.04 9.14  7.46  6.58
#> 2   8  8  8  8  6.95 8.14  6.77  5.76
#> 3  13 13 13  8  7.58 8.74 12.74  7.71
#> 4   9  9  9  8  8.81 8.77  7.11  8.84
#> 5  11 11 11  8  8.33 9.26  7.81  8.47
#> 6  14 14 14  8  9.96 8.10  8.84  7.04
#> 7   6  6  6  8  7.24 6.13  6.08  5.25
#> 8   4  4  4 19  4.26 3.10  5.39 12.50
#> 9  12 12 12  8 10.84 9.13  8.15  5.56
#> 10  7  7  7  8  4.82 7.26  6.42  7.91
#> 11  5  5  5  8  5.68 4.74  5.73  6.89
```


```
#>                    x1        x2        x3        x4
#> nobs        11.000000 11.000000 11.000000 11.000000
#> NAs          0.000000  0.000000  0.000000  0.000000
#> Minimum      4.000000  4.000000  4.000000  8.000000
#> Maximum     14.000000 14.000000 14.000000 19.000000
#> 1. Quartile  6.500000  6.500000  6.500000  8.000000
#> 3. Quartile 11.500000 11.500000 11.500000  8.000000
#> Mean         9.000000  9.000000  9.000000  9.000000
#> Median       9.000000  9.000000  9.000000  8.000000
#> Sum         99.000000 99.000000 99.000000 99.000000
#> SE Mean      1.000000  1.000000  1.000000  1.000000
#> LCL Mean     6.771861  6.771861  6.771861  6.771861
#> UCL Mean    11.228139 11.228139 11.228139 11.228139
#> Variance    11.000000 11.000000 11.000000 11.000000
#> Stdev        3.316625  3.316625  3.316625  3.316625
#> Skewness     0.000000  0.000000  0.000000  2.466911
#> Kurtosis    -1.528926 -1.528926 -1.528926  4.520661
#>                    y1        y2        y3        y4
#> nobs        11.000000 11.000000 11.000000 11.000000
#> NAs          0.000000  0.000000  0.000000  0.000000
#> Minimum      4.260000  3.100000  5.390000  5.250000
#> Maximum     10.840000  9.260000 12.740000 12.500000
#> 1. Quartile  6.315000  6.695000  6.250000  6.170000
#> 3. Quartile  8.570000  8.950000  7.980000  8.190000
#> Mean         7.500909  7.500909  7.500000  7.500909
#> Median       7.580000  8.140000  7.110000  7.040000
#> Sum         82.510000 82.510000 82.500000 82.510000
#> SE Mean      0.612541  0.612568  0.612196  0.612242
#> LCL Mean     6.136083  6.136024  6.135943  6.136748
#> UCL Mean     8.865735  8.865795  8.864057  8.865070
#> Variance     4.127269  4.127629  4.122620  4.123249
#> Stdev        2.031568  2.031657  2.030424  2.030579
#> Skewness    -0.048374 -0.978693  1.380120  1.120774
#> Kurtosis    -1.199123 -0.514319  1.240044  0.628751
```

As you can see from the table, the summary statistics for the four tables look very similar, however let's graph these and see what kind of visualizations we get.



![](88-anscombe_files/figure-epub3/unnamed-chunk-4-1.png)<!-- -->

Pretty rad right? So yes, statistical data is vital, however it should not be the only thing you look at, sometimes a visualization can help you understand the data more! Later in this book, and in the upper level data analytics courses, we will cover visualizations more and how they can be useful.
