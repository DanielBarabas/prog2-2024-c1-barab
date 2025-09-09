# 2025-09-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |    12.0555   |       0.990603 |   0.435965 |
| barab-szabi-1        |     0.546381 |       0.420339 |   0.439318 |
| k-d_tree_polars      |     0.543262 |       0.424512 |   0.44241  |
| k-d_tree_pandas      |     0.582504 |       0.397245 |   0.566986 |
| Bori_Aron_solution-1 |     0.538084 |       0.568462 |   0.568045 |
| solution-1           |     8.02444  |       1e-06    |   0.715629 |
| k-d_tree_sklearn     |     3.20055  |       1.32106  |   1.13273  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557098 |       0.494689 |   0.433576 |
| barab-szabi-1        |     0.559035 |       0.425001 |   0.449491 |
| k-d_tree_polars      |     0.560738 |       0.424932 |   0.451645 |
| Bori_Aron_solution-1 |     0.544745 |       0.567742 |   0.562479 |
| k-d_tree_pandas      |     0.55248  |       0.397292 |   0.583957 |
| k-d_tree_sklearn     |     0.567601 |       1.01542  |   1.10673  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559576 |       0.456038 |   0.45201  |
| k-d_tree_polars      |     1.0108   |       0.450491 |   0.466518 |
| barab-szabi-1        |     0.554426 |       0.445444 |   0.468613 |
| Bori_Aron_solution-1 |     0.549535 |       0.609852 |   0.564594 |
| k-d_tree_pandas      |     0.558873 |       0.42145  |   0.615163 |
| k-d_tree_sklearn     |     0.563272 |       1.05821  |   1.12851  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559691 |       0.518896 |   0.479863 |
| k-d_tree_polars      |     0.557095 |       0.56136  |   0.565796 |
| barab-szabi-1        |     0.55994  |       0.561225 |   0.58357  |
| Bori_Aron_solution-1 |     0.548352 |       0.803119 |   0.593142 |
| k-d_tree_pandas      |     0.551953 |       0.498847 |   0.761972 |
| k-d_tree_sklearn     |     0.559344 |       1.28666  |   1.17483  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560786 |       0.787109 |   0.513686 |
| Bori_Aron_solution-1 |     0.550375 |       1.44174  |   0.597964 |
| k-d_tree_polars      |     0.557048 |       0.902972 |   0.945935 |
| barab-szabi-1        |     0.560961 |       0.906391 |   0.972056 |
| k-d_tree_pandas      |     0.549953 |       0.766828 |   1.23186  |
| k-d_tree_sklearn     |     0.55007  |       2.13376  |   1.28302  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561489 |        5.72764 |   0.778562 |
| Bori_Aron_solution-1 |     0.548335 |       11.0308  |   0.886359 |
| k-d_tree_sklearn     |     0.55691  |       17.0797  |   1.34758  |
| k-d_tree_polars      |     0.549851 |        4.98424 |   6.96187  |
| barab-szabi-1        |     0.567413 |        5.01509 |   7.07252  |
| k-d_tree_pandas      |     0.554325 |        3.92576 |   7.40728  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55066  |        78.4402 |    2.97195 |
| k-d_tree_sklearn     |     0.781456 |       247.186  |    4.14522 |
| Bori_Aron_solution-1 |     0.553786 |       148.329  |   17.458   |