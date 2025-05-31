# 2025-05-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571366 |       0.410845 |   0.413597 |
| k-d_tree_polars      |     0.564799 |       0.424289 |   0.44431  |
| k-d_tree_pandas      |     0.545472 |       0.389386 |   0.542691 |
| Bori_Aron_solution-1 |     0.533136 |       0.536319 |   0.585707 |
| solution-1           |     7.5104   |       1e-06    |   0.629134 |
| barab-szabi-1        |     7.76546  |       0.543459 |   0.796076 |
| k-d_tree_sklearn     |     3.23007  |       1.27161  |   1.03181  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.553082 |       0.40634  |   0.424544 |
| barab-szabi-2        |     0.552501 |       0.418963 |   0.428143 |
| barab-szabi-1        |     0.548061 |       0.410917 |   0.432395 |
| Bori_Aron_solution-1 |     0.541735 |       0.582302 |   0.558276 |
| k-d_tree_pandas      |     0.551973 |       0.386744 |   0.565232 |
| k-d_tree_sklearn     |     0.564019 |       0.974348 |   1.06535  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.544672 |       0.437868 |   0.451875 |
| barab-szabi-2        |     0.562997 |       0.439288 |   0.453603 |
| k-d_tree_polars      |     0.554728 |       0.430653 |   0.454768 |
| Bori_Aron_solution-1 |     0.560604 |       0.59628  |   0.553566 |
| k-d_tree_pandas      |     0.557273 |       0.413961 |   0.608394 |
| k-d_tree_sklearn     |     0.558872 |       1.03653  |   1.05975  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555171 |       0.507762 |   0.461591 |
| Bori_Aron_solution-1 |     0.552387 |       0.765717 |   0.558633 |
| k-d_tree_polars      |     0.575943 |       0.568859 |   0.563497 |
| barab-szabi-1        |     0.562126 |       0.582167 |   0.592228 |
| k-d_tree_pandas      |     0.554819 |       0.486453 |   0.740614 |
| k-d_tree_sklearn     |     0.557891 |       1.24574  |   1.14356  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548722 |       0.739262 |   0.513247 |
| Bori_Aron_solution-1 |     0.542952 |       1.42264  |   0.601699 |
| k-d_tree_polars      |     0.550141 |       0.889845 |   0.899129 |
| barab-szabi-1        |     0.559917 |       0.872897 |   0.939587 |
| k-d_tree_pandas      |     0.551863 |       0.759465 |   1.17036  |
| k-d_tree_sklearn     |     0.561418 |       2.11685  |   1.22393  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551028 |        5.31287 |   0.713661 |
| Bori_Aron_solution-1 |     0.56143  |       10.7594  |   0.91522  |
| k-d_tree_sklearn     |     0.561281 |       16.4438  |   1.39905  |
| k-d_tree_polars      |     0.552579 |        4.97292 |   6.74445  |
| barab-szabi-1        |     0.566013 |        5.00243 |   6.81446  |
| k-d_tree_pandas      |     0.565767 |        3.96922 |   7.09237  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623194 |        71.2753 |    2.69754 |
| k-d_tree_sklearn     |     0.817811 |       231.158  |    4.36114 |
| Bori_Aron_solution-1 |     0.555525 |       152.677  |   16.3821  |