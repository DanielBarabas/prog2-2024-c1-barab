# 2026-04-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.43307  |       0.384025 |   0.414161 |
| barab-szabi-2        |     0.437418 |       0.418185 |   0.423109 |
| k-d_tree_polars      |     0.454313 |       0.396049 |   0.435267 |
| k-d_tree_pandas      |     0.425196 |       0.364185 |   0.522387 |
| Bori_Aron_solution-1 |     0.42096  |       0.531122 |   0.536952 |
| solution-1           |     7.51578  |       1e-06    |   0.756423 |
| k-d_tree_sklearn     |     9.72137  |       1.46389  |   1.14271  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.417859 |       0.394625 |   0.412124 |
| barab-szabi-2        |     0.435839 |       0.421636 |   0.419301 |
| k-d_tree_polars      |     0.429007 |       0.394643 |   0.422353 |
| k-d_tree_pandas      |     0.420203 |       0.367575 |   0.51907  |
| Bori_Aron_solution-1 |     0.418659 |       0.52882  |   0.525649 |
| k-d_tree_sklearn     |     0.431695 |       0.918911 |   1.0205   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.426292 |       0.415703 |   0.444411 |
| barab-szabi-2        |     0.430089 |       0.434608 |   0.449437 |
| k-d_tree_polars      |     0.431149 |       0.423697 |   0.464309 |
| Bori_Aron_solution-1 |     0.427014 |       0.583436 |   0.54275  |
| k-d_tree_pandas      |     0.432745 |       0.386609 |   0.569279 |
| k-d_tree_sklearn     |     0.422801 |       0.970733 |   1.03819  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453412 |       0.487584 |   0.451617 |
| Bori_Aron_solution-1 |     0.421552 |       0.72184  |   0.534827 |
| k-d_tree_polars      |     0.426632 |       0.552232 |   0.53503  |
| barab-szabi-1        |     0.451557 |       0.579462 |   0.556866 |
| k-d_tree_pandas      |     0.425728 |       0.472958 |   0.694733 |
| k-d_tree_sklearn     |     0.432479 |       1.21835  |   1.08309  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.427233 |       0.720561 |   0.536137 |
| Bori_Aron_solution-1 |     0.415387 |       1.338    |   0.568517 |
| k-d_tree_polars      |     0.431902 |       0.87053  |   0.863172 |
| barab-szabi-1        |     0.441892 |       0.877865 |   0.910175 |
| k-d_tree_pandas      |     0.436097 |       0.738638 |   1.07576  |
| k-d_tree_sklearn     |     0.435888 |       2.00451  |   1.11754  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.421961 |        5.09973 |   0.708432 |
| Bori_Aron_solution-1 |     0.430126 |       10.1834  |   0.865833 |
| k-d_tree_sklearn     |     0.43823  |       14.8575  |   1.2704   |
| k-d_tree_polars      |     0.422822 |        4.84686 |   6.26792  |
| barab-szabi-1        |     0.426162 |        4.95348 |   6.31867  |
| k-d_tree_pandas      |     0.440612 |        3.87758 |   6.81544  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.769733 |        69.1731 |    2.81207 |
| k-d_tree_sklearn     |     0.436917 |       180.878  |    4.01744 |
| Bori_Aron_solution-1 |     0.438439 |       140.756  |   30.2894  |