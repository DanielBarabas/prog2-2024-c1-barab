# 2025-01-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.57627  |       1e-06    |   0.361537 |
| k-d_tree_polars      |     0.578839 |       0.40831  |   0.403272 |
| barab-szabi-1        |     0.593095 |       0.405949 |   0.403277 |
| barab-szabi-2        |     8.17452  |       0.48622  |   0.404293 |
| Bori_Aron_solution-1 |     0.583138 |       0.531987 |   0.533028 |
| k-d_tree_pandas      |     0.585506 |       0.393418 |   0.548477 |
| k-d_tree_sklearn     |     3.23203  |       0.979231 |   1.02793  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.58627  |       0.4095   |   0.406082 |
| barab-szabi-1        |     0.586385 |       0.412959 |   0.40866  |
| barab-szabi-2        |     0.584831 |       0.441208 |   0.410786 |
| Bori_Aron_solution-1 |     0.586252 |       0.562373 |   0.535085 |
| k-d_tree_pandas      |     0.586244 |       0.394588 |   0.546416 |
| k-d_tree_sklearn     |     0.593331 |       0.940585 |   1.01829  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589006 |       0.415104 |   0.412295 |
| k-d_tree_polars      |     0.589713 |       0.442168 |   0.432774 |
| barab-szabi-1        |     0.596884 |       0.448984 |   0.448977 |
| Bori_Aron_solution-1 |     0.579853 |       0.590915 |   0.534639 |
| k-d_tree_pandas      |     0.590075 |       0.40328  |   0.592823 |
| k-d_tree_sklearn     |     0.58685  |       0.992199 |   1.043    |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586177 |       0.483803 |   0.444427 |
| k-d_tree_polars      |     0.587077 |       0.541794 |   0.529229 |
| barab-szabi-1        |     0.588064 |       0.535758 |   0.542313 |
| Bori_Aron_solution-1 |     0.58017  |       0.753944 |   0.556802 |
| k-d_tree_pandas      |     0.58716  |       0.486048 |   0.720275 |
| k-d_tree_sklearn     |     0.592378 |       1.21383  |   1.10512  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585202 |       0.722656 |   0.4851   |
| Bori_Aron_solution-1 |     0.581708 |       1.38902  |   0.583285 |
| k-d_tree_polars      |     0.591336 |       0.86085  |   0.883062 |
| barab-szabi-1        |     0.594827 |       0.87234  |   0.938677 |
| k-d_tree_pandas      |     0.583498 |       0.745861 |   1.17185  |
| k-d_tree_sklearn     |     0.588522 |       2.03345  |   1.19754  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584344 |        5.38261 |   0.738327 |
| Bori_Aron_solution-1 |     0.58353  |       10.6288  |   0.874164 |
| k-d_tree_sklearn     |     0.591162 |       16.134   |   1.29796  |
| k-d_tree_polars      |     0.586569 |        4.89868 |   6.5251   |
| barab-szabi-1        |     0.594688 |        4.90836 |   6.63418  |
| k-d_tree_pandas      |     0.588212 |        3.75407 |   6.93668  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589425 |        74.5344 |    3.05143 |
| k-d_tree_sklearn     |     0.613743 |       226.106  |    4.4124  |
| Bori_Aron_solution-1 |     0.684387 |       143.717  |   19.949   |