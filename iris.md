#      Analysis on Vector data
###    Scenario: meter readings of a car at each stop in KMs

## Data Preparation

```r
dist <- c( 65311, 65624, 65908, 66219, 66499, 66821, 67145, 67447)
```

## Insights from above data
### Question 1) no. of KM travelled before each stop
### Answer

```r
r <- diff(dist)
print(r)
```

```
## [1] 313 284 311 280 322 324 302
```
### Question 2) total number of KMs travelled
### Answer

```r
r <- diff(dist)
tot.dist <- sum(r)
print(tot.dist)
```

```
## [1] 2136
```
