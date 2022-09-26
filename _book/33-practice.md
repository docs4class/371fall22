# Practice

## `starwars` Excercises

Please use the `starwars` dataset from the `dplyr` package to answer the following questions:

1. How may humans are in this dataset?
2. How many characters are taller than 89 cm?
3. How many characters are taller than 37 inches?
4. How many characters are taller than 37 inches and weigh more than 55 pounds?
6. How many characters are not human or droid?
6. How many characters are not human or droid and are taller than 47 inches?
1. Which species has the most individuals included in this data set?
2. Which species has the tallest individuals on average?
3. What is the tallest individual for each species?
4. Calculate the BMI for each individual and determine which individual has the highest BMI.  Use the formula `bmi = mass/((height/100)^2)` to calculate bmi.
5. Which homeworld has the most individuals included in this data set?
6. Which homeworld has the tallest individuals on average?
7. What is the tallest individual for each eye color?

## `iris` Excercises

Please use the `iris` dataset from base R to answer the following questions:

1. How many "virginica" have a petal width of 2.3 or greater in this dataset?


```
#>    n
#> 1 14
```

2. What is the average petal width for each species?


```
#> # A tibble: 3 × 2
#>   Species    avg.petal.width
#>   <fct>                <dbl>
#> 1 setosa               0.246
#> 2 versicolor           1.33 
#> 3 virginica            2.03
```

3. How many observations of each species have a petal width of 2.3 or greater in this dataset?


```
#> # A tibble: 1 × 2
#>   Species       n
#>   <fct>     <int>
#> 1 virginica    14
```


4. How many observations of each species have a petal width of 0.5 or greater in this dataset?



```
#> # A tibble: 3 × 2
#>   Species        n
#>   <fct>      <int>
#> 1 setosa         2
#> 2 versicolor    50
#> 3 virginica     50
```

