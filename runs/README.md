# 2024-12-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.630497 |       0.422339 |   0.39265  |
| barab-szabi-2        |     0.626608 |       0.401336 |   0.400886 |
| barab-szabi-1        |     0.621347 |       0.409896 |   0.401734 |
| Bori_Aron_solution-1 |     0.617866 |       0.529144 |   0.53595  |
| solution-1           |     7.91491  |       1e-06    |   0.55531  |
| k-d_tree_pandas      |     0.637235 |       0.392883 |   0.566795 |
| k-d_tree_sklearn     |    10.7131   |       1.35877  |   1.0591   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64674  |       0.423166 |   0.40775  |
| barab-szabi-1        |     0.636479 |       0.432601 |   0.411055 |
| k-d_tree_polars      |     0.642065 |       0.44301  |   0.416371 |
| Bori_Aron_solution-1 |     0.633148 |       0.572323 |   0.552131 |
| k-d_tree_pandas      |     0.645932 |       0.408703 |   0.577612 |
| k-d_tree_sklearn     |     0.632865 |       0.945771 |   0.999609 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.701575 |       0.423275 |   0.429486 |
| k-d_tree_polars      |     0.648536 |       0.455526 |   0.439401 |
| barab-szabi-1        |     0.649031 |       0.457834 |   0.444783 |
| Bori_Aron_solution-1 |     0.638196 |       0.599145 |   0.569505 |
| k-d_tree_pandas      |     0.649876 |       0.426022 |   0.621708 |
| k-d_tree_sklearn     |     0.649479 |       1.00579  |   1.05629  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.642991 |       0.489944 |   0.452179 |
| k-d_tree_polars      |     0.66672  |       0.557886 |   0.54253  |
| barab-szabi-1        |     0.649027 |       0.566709 |   0.552737 |
| Bori_Aron_solution-1 |     0.646016 |       0.778807 |   0.576684 |
| k-d_tree_pandas      |     0.645923 |       0.506355 |   0.739543 |
| k-d_tree_sklearn     |     0.652142 |       1.27319  |   1.13527  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645105 |       0.763585 |   0.579962 |
| Bori_Aron_solution-1 |     0.633353 |       1.47214  |   0.612647 |
| k-d_tree_polars      |     0.646456 |       0.890806 |   0.925366 |
| barab-szabi-1        |     0.662316 |       0.887405 |   0.959096 |
| k-d_tree_sklearn     |     0.647061 |       2.14215  |   1.2066   |
| k-d_tree_pandas      |     0.665668 |       0.801108 |   1.24226  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6399   |        5.6869  |   0.748452 |
| Bori_Aron_solution-1 |     0.629765 |       11.121   |   0.823729 |
| k-d_tree_sklearn     |     0.672093 |       17.2621  |   1.29237  |
| barab-szabi-1        |     0.654263 |        4.96559 |   6.78199  |
| k-d_tree_polars      |     0.630931 |        4.92627 |   6.94024  |
| k-d_tree_pandas      |     0.633995 |        3.92539 |   7.62527  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.678512 |        77.2056 |    3.14532 |
| k-d_tree_sklearn     |     0.676345 |       238.955  |    4.26948 |
| Bori_Aron_solution-1 |     0.667996 |       161.364  |   17.3969  |