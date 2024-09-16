# 2024-09-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610219 |       0.389913 |   0.384468 |
| barab-szabi-1        |     0.610042 |       0.394515 |   0.393242 |
| Bori_Aron_solution-1 |     4.65568  |       0.70978  |   0.468071 |
| k-d_tree_pandas      |     0.600862 |       0.378998 |   0.528643 |
| k-d_tree_polars      |     4.19594  |       0.632628 |   0.537076 |
| solution-1           |     7.57016  |       1e-06    |   0.688921 |
| k-d_tree_sklearn     |     3.1785   |       0.977943 |   0.951995 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.6198   |       0.404961 |   0.393372 |
| barab-szabi-2        |     0.614724 |       0.39971  |   0.39365  |
| k-d_tree_polars      |     0.611866 |       0.405598 |   0.399251 |
| k-d_tree_pandas      |     0.63725  |       0.381387 |   0.543503 |
| Bori_Aron_solution-1 |     0.607467 |       0.531644 |   0.582835 |
| k-d_tree_sklearn     |     0.624051 |       0.879693 |   0.992097 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615899 |       0.403631 |   0.400504 |
| k-d_tree_polars      |     0.629972 |       0.426637 |   0.4195   |
| barab-szabi-1        |     0.612215 |       0.425478 |   0.427042 |
| Bori_Aron_solution-1 |     0.609995 |       0.568197 |   0.525959 |
| k-d_tree_pandas      |     0.616436 |       0.405264 |   0.571525 |
| k-d_tree_sklearn     |     0.618456 |       0.933995 |   0.99209  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613733 |       0.465723 |   0.429507 |
| barab-szabi-1        |     0.617586 |       0.539207 |   0.529334 |
| k-d_tree_polars      |     0.635975 |       0.541244 |   0.530228 |
| Bori_Aron_solution-1 |     0.619068 |       0.770077 |   0.549692 |
| k-d_tree_pandas      |     0.63505  |       0.499854 |   0.724256 |
| k-d_tree_sklearn     |     0.638678 |       1.1559   |   1.04991  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609679 |       0.70584  |   0.460174 |
| Bori_Aron_solution-1 |     0.618377 |       1.37319  |   0.562907 |
| k-d_tree_polars      |     0.606434 |       0.84681  |   0.85035  |
| barab-szabi-1        |     0.609937 |       0.828733 |   0.891642 |
| k-d_tree_sklearn     |     0.617722 |       1.94674  |   1.13097  |
| k-d_tree_pandas      |     0.618035 |       0.743864 |   1.14087  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622357 |        5.26619 |   0.723579 |
| Bori_Aron_solution-1 |     0.601625 |       10.8625  |   0.83206  |
| k-d_tree_sklearn     |     0.620133 |       15.9566  |   1.2455   |
| barab-szabi-1        |     0.616868 |        4.8632  |   6.53912  |
| k-d_tree_polars      |     0.615144 |        4.87928 |   6.61064  |
| k-d_tree_pandas      |     0.612438 |        3.88849 |   6.96791  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747234 |        71.8444 |    3.0853  |
| k-d_tree_sklearn     |     0.998798 |       227.375  |    4.48568 |
| Bori_Aron_solution-1 |     0.60559  |       149.223  |   16.9483  |