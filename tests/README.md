Tests and Coverage
================
14 March, 2022 16:40:53

  - [Coverage](#coverage)
  - [Unit Tests](#unit-tests)

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                                                    | Coverage (%) |
| :-------------------------------------------------------- | :----------: |
| equatiomatic                                              |    95.80     |
| [R/shiny.R](../R/shiny.R)                                 |     0.00     |
| [R/print.R](../R/print.R)                                 |    24.00     |
| [R/distribution-wrapping.R](../R/distribution-wrapping.R) |    90.91     |
| [R/extract\_lhs.R](../R/extract_lhs.R)                    |    94.74     |
| [R/merMod.R](../R/merMod.R)                               |    95.25     |
| [R/extract\_eq.R](../R/extract_eq.R)                      |    96.41     |
| [R/utils.R](../R/utils.R)                                 |    97.87     |
| [R/extract\_rhs.R](../R/extract_rhs.R)                    |    99.31     |
| [R/create\_eq.R](../R/create_eq.R)                        |    99.51     |
| [R/helpers\_forecast.R](../R/helpers_forecast.R)          |    100.00    |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                                              |  n |  time | error | failed | skipped | warning | icon |
| :---------------------------------------------------------------- | -: | ----: | ----: | -----: | ------: | ------: | :--- |
| [test-clm.R](testthat/test-clm.R)                                 | 19 | 0.057 |     0 |      0 |       0 |       0 |      |
| [test-fontsize.R](testthat/test-fontsize.R)                       |  9 | 0.004 |     0 |      0 |       0 |       0 |      |
| [test-forecast-arima.R](testthat/test-forecast-arima.R)           |  4 | 0.004 |     0 |      0 |       0 |       0 |      |
| [test-glm.R](testthat/test-glm.R)                                 | 23 | 0.009 |     0 |      0 |       0 |       0 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R)                       |  9 | 0.003 |     0 |      0 |       0 |       0 |      |
| [test-lm.R](testthat/test-lm.R)                                   | 18 | 0.010 |     0 |      0 |       0 |       0 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R)                         | 41 | 0.012 |     0 |      0 |       0 |       0 |      |
| [test-polr.R](testthat/test-polr.R)                               | 13 | 0.004 |     0 |      0 |       0 |       0 |      |
| [test-print.R](testthat/test-print.R)                             |  4 | 0.002 |     0 |      0 |       0 |       0 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R)             | 19 | 0.007 |     0 |      0 |       0 |       2 | ⚠️   |
| [test-utils.R](testthat/test-utils.R)                             |  8 | 0.003 |     0 |      0 |       0 |       0 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R) | 10 | 0.004 |     0 |      0 |       0 |       0 |      |

<details open>

<summary> Show Detailed Test Results </summary>

| file                                                               | context | test                                                        | status  | n |  time | icon |
| :----------------------------------------------------------------- | :------ | :---------------------------------------------------------- | :------ | -: | ----: | :--- |
| [test-clm.R](testthat/test-clm.R#)                                 |         | colorizing works                                            | PASS    | 1 | 0.038 |      |
| [test-clm.R](testthat/test-clm.R#)                                 |         | Renaming Variables works                                    | PASS    | 2 | 0.012 |      |
| [test-clm.R](testthat/test-clm.R#)                                 |         | Math extraction works                                       | PASS    | 4 | 0.002 |      |
| [test-clm.R](testthat/test-clm.R#)                                 |         | Collapsing clm factors works                                | PASS    | 6 | 0.002 |      |
| [test-clm.R](testthat/test-clm.R#)                                 |         | Ordered models with clm work                                | PASS    | 5 | 0.002 |      |
| [test-clm.R](testthat/test-clm.R#)                                 |         | Unsupported CLMs create a message                           | PASS    | 1 | 0.001 |      |
| [test-fontsize.R](testthat/test-fontsize.R#)                       |         | font-size changes, lm                                       | PASS    | 3 | 0.001 |      |
| [test-fontsize.R](testthat/test-fontsize.R#)                       |         | font-size changes, lmer                                     | PASS    | 3 | 0.001 |      |
| [test-fontsize.R](testthat/test-fontsize.R#)                       |         | font-size changes, arima                                    | PASS    | 3 | 0.002 |      |
| [test-forecast-arima.R](testthat/test-forecast-arima.R#)           |         | Basic ARIMA model functions                                 | PASS    | 2 | 0.002 |      |
| [test-forecast-arima.R](testthat/test-forecast-arima.R#)           |         | Regression w/ ARIMA Errors functions                        | PASS    | 2 | 0.002 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | colorizing works                                            | PASS    | 4 | 0.002 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Renaming Variables works                                    | PASS    | 1 | 0.000 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Math extraction works                                       | PASS    | 2 | 0.001 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Collapsing glm factors works                                | PASS    | 4 | 0.001 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Logistic regression works                                   | PASS    | 1 | 0.000 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Probit regression works                                     | PASS    | 2 | 0.001 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Unsupported GLMs create a message                           | PASS    | 1 | 0.000 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Distribution-based equations work                           | PASS    | 3 | 0.002 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | Weights work                                                | PASS    | 1 | 0.001 |      |
| [test-glm.R](testthat/test-glm.R#)                                 |         | non-binomial regression works                               | PASS    | 4 | 0.001 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | Checking for random/fixed effects works                     | PASS    | 1 | 0.000 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | colorizing works                                            | PASS    | 2 | 0.000 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | Renaming Variables works                                    | PASS    | 1 | 0.000 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | Standard Poisson regression models work                     | PASS    | 2 | 0.001 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | Poisson regression models with an offset work               | PASS    | 2 | 0.001 |      |
| [test-glmerMod.R](testthat/test-glmerMod.R#)                       |         | Binomial Logistic Regression models work                    | PASS    | 1 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Overlapping names don’t result in an error                  | PASS    | 1 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Dropping intercept notation works                           | PASS    | 1 | 0.000 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | colorizing works                                            | PASS    | 1 | 0.000 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Renaming Variables works                                    | PASS    | 1 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Math extraction works                                       | PASS    | 3 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Collapsing lm factors works                                 | PASS    | 2 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Labeling works                                              | PASS    | 1 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Simple lm models work                                       | PASS    | 3 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Interactions work                                           | PASS    | 2 | 0.002 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Custom Greek works                                          | PASS    | 2 | 0.001 |      |
| [test-lm.R](testthat/test-lm.R#)                                   |         | Hat is escaped correctly                                    | PASS    | 1 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Checking for random/fixed effects works                     | PASS    | 1 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | colorizing works                                            | PASS    | 3 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Math extraction works                                       | PASS    | 4 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Implicit ID variables are handled                           | PASS    | 1 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Renaming Variables works                                    | PASS    | 1 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Really big models work                                      | PASS    | 1 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Categorical variable level parsing works (from issue \#140) | PASS    | 1 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Unconditional lmer models work                              | PASS    | 3 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Level 1 predictors work                                     | PASS    | 2 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Mean separate works as expected                             | PASS    | 2 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Wrapping works as expected                                  | PASS    | 1 | 0.000 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Unstructured variance-covariances work as expected          | PASS    | 5 | 0.002 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Group-level predictors work as expected                     | PASS    | 3 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Interactions work as expected                               | PASS    | 5 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Alternate random effect VCV structures work                 | PASS    | 3 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | Nested model syntax works                                   | PASS    | 3 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | use\_coef works                                             | PASS    | 1 | 0.001 |      |
| [test-lmerMod.R](testthat/test-lmerMod.R#)                         |         | return variances works                                      | PASS    | 1 | 0.001 |      |
| [test-polr.R](testthat/test-polr.R#)                               |         | colorizing works                                            | PASS    | 1 | 0.001 |      |
| [test-polr.R](testthat/test-polr.R#)                               |         | Renaming Variables works                                    | PASS    | 1 | 0.000 |      |
| [test-polr.R](testthat/test-polr.R#)                               |         | Math extraction works                                       | PASS    | 2 | 0.000 |      |
| [test-polr.R](testthat/test-polr.R#)                               |         | Collapsing polr factors works                               | PASS    | 4 | 0.001 |      |
| [test-polr.R](testthat/test-polr.R#)                               |         | Ordered logistic regression works                           | PASS    | 5 | 0.002 |      |
| [test-print.R](testthat/test-print.R#)                             |         | Equation is printed correctly                               | PASS    | 2 | 0.001 |      |
| [test-print.R](testthat/test-print.R#)                             |         | Equation is knit\_print-ed correctly                        | PASS    | 2 | 0.001 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R#)             |         | se\_subscripts argument works with numeric coefficients     | PASS    | 3 | 0.001 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R#)             |         | se\_subscripts argument works with wrapping                 | PASS    | 4 | 0.001 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R#)             |         | se\_subscripts argument works with Greek letter terms       | PASS    | 4 | 0.002 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R#)             |         | se\_subscripts argument works with transformed variables    | PASS    | 4 | 0.002 |      |
| [test-se-subscripts.R](testthat/test-se-subscripts.R#L178_L182)    |         | se\_subscripts works with factor variable                   | WARNING | 4 | 0.001 | ⚠️   |
| [test-utils.R](testthat/test-utils.R#)                             |         | Strict mapply\_\* functions work                            | PASS    | 8 | 0.003 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R#) |         | Coefficient digits work correctly                           | PASS    | 2 | 0.001 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R#) |         | Wrapping works correctly                                    | PASS    | 8 | 0.003 |      |

| Failed | Warning | Skipped |
| :----- | :------ | :------ |
| 🛑      | ⚠️      | 🔶       |

</details>

<details>

<summary> Session Info </summary>

| Field    | Value                             |                                                                                                                                                                                                                                                                         |
| :------- | :-------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Version  | R version 4.1.3 (2022-03-10)      |                                                                                                                                                                                                                                                                         |
| Platform | x86\_64-apple-darwin17.0 (64-bit) | <a href="https://github.com/datalorax/equatiomatic/commit/6e71b4707529a2e38d226f254a5022e976ed1094/checks" target="_blank"><span title="Built on Github Actions">![](https://github.com/metrumresearchgroup/covrpage/blob/actions/inst/logo/gh.png?raw=true)</span></a> |
| Running  | macOS Big Sur/Monterey 10.16      |                                                                                                                                                                                                                                                                         |
| Language | en\_US                            |                                                                                                                                                                                                                                                                         |
| Timezone | UTC                               |                                                                                                                                                                                                                                                                         |

| Package  | Version |
| :------- | :------ |
| testthat | 3.1.2   |
| covr     | 3.5.1   |
| covrpage | 0.1     |

</details>

<!--- Final Status : skipped/warning --->
