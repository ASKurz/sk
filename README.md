

## Package {sk}

This is the homepage for my package!

Here is some addition.

``` r
1 + 1
```

    [1] 2

Here is some LaTeX:

$$y_i = \beta_1x_i + \beta_0.$$

## Load {sk}

``` r
library(sk)
```

Here’s how to use `standardize()`.

``` r
rnorm(n = 1e4, mean = 8, sd = 2) |> 
  standardize() |> 
  mean() |> 
  round(digits = 8)
```

    [1] 0
# sk
