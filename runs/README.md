# 2025-11-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634956 |       0.502124 |   0.428614 |
| k-d_tree_polars      |     0.525491 |       0.404845 |   0.430058 |
| barab-szabi-1        |     0.530368 |       0.411949 |   0.438831 |
| Bori_Aron_solution-1 |     0.522273 |       0.547529 |   0.550727 |
| solution-1           |     7.8929   |       1e-06    |   0.581443 |
| k-d_tree_pandas      |     8.92216  |       0.435954 |   0.68292  |
| k-d_tree_sklearn     |     3.11623  |       1.16633  |   1.07007  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529643 |       0.428362 |   0.436156 |
| k-d_tree_polars      |     0.529588 |       0.412734 |   0.436565 |
| barab-szabi-1        |     0.534047 |       0.41705  |   0.438483 |
| Bori_Aron_solution-1 |     0.523667 |       0.562077 |   0.553572 |
| k-d_tree_pandas      |     0.531309 |       0.401971 |   0.560617 |
| k-d_tree_sklearn     |     0.534987 |       0.978845 |   1.06625  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531256 |       0.452532 |   0.4406   |
| k-d_tree_polars      |     0.532877 |       0.437988 |   0.458678 |
| barab-szabi-1        |     0.52842  |       0.43951  |   0.46548  |
| Bori_Aron_solution-1 |     0.526198 |       0.599646 |   0.557871 |
| k-d_tree_pandas      |     0.535342 |       0.420517 |   0.606666 |
| k-d_tree_sklearn     |     0.533279 |       1.01871  |   1.09564  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531138 |       0.508776 |   0.471912 |
| Bori_Aron_solution-1 |     0.521467 |       0.794927 |   0.557591 |
| k-d_tree_polars      |     0.533128 |       0.564248 |   0.560126 |
| barab-szabi-1        |     0.525588 |       0.56007  |   0.569855 |
| k-d_tree_pandas      |     0.530574 |       0.503433 |   0.749151 |
| k-d_tree_sklearn     |     0.532314 |       1.25728  |   1.1484   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528121 |       0.750517 |   0.506125 |
| Bori_Aron_solution-1 |     0.521444 |       1.45094  |   0.584481 |
| k-d_tree_polars      |     0.534621 |       0.929668 |   0.911165 |
| barab-szabi-1        |     0.532472 |       0.932027 |   0.949042 |
| k-d_tree_pandas      |     0.528513 |       0.817298 |   1.17059  |
| k-d_tree_sklearn     |     0.538603 |       2.11356  |   1.2224   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529546 |        5.24887 |   0.759126 |
| Bori_Aron_solution-1 |     0.523467 |       11.4877  |   0.859483 |
| k-d_tree_sklearn     |     0.533888 |       17.2337  |   1.35031  |
| barab-szabi-1        |     0.550463 |        5.39074 |   6.62453  |
| k-d_tree_polars      |     0.547057 |        5.4143  |   6.62481  |
| k-d_tree_pandas      |     0.529069 |        4.44141 |   7.0476   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537664 |         83.06  |    2.8365  |
| k-d_tree_sklearn     |     0.552434 |        240.829 |    4.20503 |
| Bori_Aron_solution-1 |     0.665028 |        148.825 |   17.7859  |