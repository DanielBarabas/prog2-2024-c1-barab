# 2024-08-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.71474  |       1e-06    |   0.364619 |
| barab-szabi-2        |     8.35115  |       0.448133 |   0.378517 |
| k-d_tree_polars      |     0.592848 |       0.38491  |   0.386077 |
| barab-szabi-1        |     0.594957 |       0.39072  |   0.397002 |
| Bori_Aron_solution-1 |     0.598722 |       0.51865  |   0.514105 |
| k-d_tree_pandas      |     0.5928   |       0.403753 |   0.516    |
| k-d_tree_sklearn     |     3.19268  |       0.930463 |   0.692502 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599539 |       0.38627  |   0.382115 |
| barab-szabi-1        |     0.602852 |       0.396777 |   0.389452 |
| k-d_tree_polars      |     0.599851 |       0.400355 |   0.39043  |
| Bori_Aron_solution-1 |     0.594028 |       0.525737 |   0.517729 |
| k-d_tree_pandas      |     0.606825 |       0.37891  |   0.569533 |
| k-d_tree_sklearn     |     0.607423 |       0.878174 |   0.712042 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602181 |       0.401999 |   0.395837 |
| k-d_tree_polars      |     0.636108 |       0.420273 |   0.41581  |
| barab-szabi-1        |     0.600291 |       0.421128 |   0.426499 |
| Bori_Aron_solution-1 |     0.590008 |       0.559494 |   0.518302 |
| k-d_tree_pandas      |     0.600818 |       0.39574  |   0.570522 |
| k-d_tree_sklearn     |     0.607237 |       0.918529 |   0.765716 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597127 |       0.461978 |   0.422576 |
| k-d_tree_polars      |     0.601694 |       0.528086 |   0.513952 |
| barab-szabi-1        |     0.601513 |       0.530391 |   0.524494 |
| Bori_Aron_solution-1 |     0.595482 |       0.739168 |   0.533305 |
| k-d_tree_pandas      |     0.600549 |       0.475374 |   0.705868 |
| k-d_tree_sklearn     |     0.61007  |       1.15096  |   0.773815 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603257 |       0.702439 |   0.464595 |
| Bori_Aron_solution-1 |     0.602552 |       1.37012  |   0.558171 |
| k-d_tree_polars      |     0.600145 |       0.845024 |   0.849058 |
| k-d_tree_sklearn     |     0.607461 |       1.96662  |   0.877645 |
| barab-szabi-1        |     0.603223 |       0.845722 |   0.88558  |
| k-d_tree_pandas      |     0.601226 |       0.744844 |   1.12316  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605469 |        5.22252 |   0.734626 |
| Bori_Aron_solution-1 |     0.594537 |       10.5937  |   0.816835 |
| k-d_tree_sklearn     |     0.608508 |       15.5401  |   0.988449 |
| k-d_tree_polars      |     0.609938 |        4.87511 |   6.28502  |
| barab-szabi-1        |     0.605436 |        4.76094 |   6.34527  |
| k-d_tree_pandas      |     0.61445  |        3.87145 |   6.7252   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604076 |        75.3901 |    3.32393 |
| k-d_tree_sklearn     |     0.747099 |       248.838  |    4.35539 |
| Bori_Aron_solution-1 |     0.922894 |       146.096  |   18.4735  |