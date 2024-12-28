# 2024-12-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616084 |       0.385976 |   0.38059  |
| k-d_tree_polars      |     0.611778 |       0.396934 |   0.386942 |
| barab-szabi-1        |     0.611823 |       0.440804 |   0.387987 |
| solution-1           |     7.69929  |       1e-06    |   0.4929   |
| Bori_Aron_solution-1 |     0.606793 |       0.517995 |   0.518293 |
| k-d_tree_pandas      |     0.633522 |       0.377359 |   0.519332 |
| k-d_tree_sklearn     |    10.5054   |       1.24562  |   0.972643 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614177 |       0.392186 |   0.380952 |
| barab-szabi-1        |     0.622211 |       0.408676 |   0.392627 |
| k-d_tree_polars      |     0.604901 |       0.400974 |   0.399459 |
| Bori_Aron_solution-1 |     0.611936 |       0.523177 |   0.515575 |
| k-d_tree_pandas      |     0.624862 |       0.391885 |   0.534711 |
| k-d_tree_sklearn     |     0.621167 |       0.882745 |   0.959006 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603503 |       0.410232 |   0.396083 |
| k-d_tree_polars      |     0.616832 |       0.438325 |   0.414385 |
| barab-szabi-1        |     0.611969 |       0.424043 |   0.426198 |
| Bori_Aron_solution-1 |     0.614145 |       0.577552 |   0.522705 |
| k-d_tree_pandas      |     0.612633 |       0.39902  |   0.568708 |
| k-d_tree_sklearn     |     0.61701  |       0.92481  |   0.978739 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612073 |       0.46576  |   0.431584 |
| k-d_tree_polars      |     0.610861 |       0.539376 |   0.513114 |
| barab-szabi-1        |     0.608166 |       0.53309  |   0.530084 |
| Bori_Aron_solution-1 |     0.606629 |       0.740904 |   0.53732  |
| k-d_tree_pandas      |     0.610094 |       0.479809 |   0.70863  |
| k-d_tree_sklearn     |     0.621083 |       1.17731  |   1.04194  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617537 |       0.726729 |   0.461688 |
| Bori_Aron_solution-1 |     0.600427 |       1.38134  |   0.553541 |
| k-d_tree_polars      |     0.615184 |       0.895235 |   0.87241  |
| barab-szabi-1        |     0.613177 |       0.861801 |   0.905463 |
| k-d_tree_sklearn     |     0.615718 |       2.00043  |   1.14284  |
| k-d_tree_pandas      |     0.604362 |       0.736196 |   1.14948  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608334 |        5.28945 |   0.72137  |
| Bori_Aron_solution-1 |     0.603693 |       10.6369  |   0.811734 |
| k-d_tree_sklearn     |     0.621751 |       15.8936  |   1.25263  |
| k-d_tree_polars      |     0.610396 |        4.84654 |   6.47001  |
| barab-szabi-1        |     0.614545 |        4.88143 |   6.53807  |
| k-d_tree_pandas      |     0.614684 |        3.88077 |   6.86881  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.642717 |        70.7661 |    2.83076 |
| k-d_tree_sklearn     |     0.6141   |       224.928  |    4.22712 |
| Bori_Aron_solution-1 |     0.628423 |       148.82   |   18.6745  |