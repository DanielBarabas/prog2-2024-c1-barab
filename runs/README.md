# 2024-05-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.54268  |       0.36685  |   0.331338 |
| barab-szabi-1        |     0.788336 |       0.399373 |   0.342178 |
| k-d_tree_polars      |     0.791915 |       0.398017 |   0.353702 |
| Bori_Aron_solution-1 |     4.51     |       0.403974 |   0.410348 |
| solution-1           |     7.77555  |       1e-06    |   0.425972 |
| k-d_tree_pandas      |     0.789169 |       0.402003 |   0.476918 |
| k-d_tree_sklearn     |     3.2882   |       0.988392 |   0.680214 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792372 |       0.344266 |   0.343279 |
| k-d_tree_polars      |     0.795204 |       0.405809 |   0.349948 |
| barab-szabi-1        |     0.789557 |       0.408586 |   0.351448 |
| Bori_Aron_solution-1 |     0.777859 |       0.484392 |   0.470441 |
| k-d_tree_pandas      |     0.793744 |       0.395753 |   0.485841 |
| k-d_tree_sklearn     |     0.803353 |       0.847272 |   0.677186 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.787152 |       0.360415 |   0.356607 |
| k-d_tree_polars      |     0.787718 |       0.43541  |   0.374145 |
| barab-szabi-1        |     0.802651 |       0.432096 |   0.405889 |
| Bori_Aron_solution-1 |     0.771363 |       0.519317 |   0.473695 |
| k-d_tree_pandas      |     0.796795 |       0.400742 |   0.528414 |
| k-d_tree_sklearn     |     0.796431 |       0.906768 |   0.702856 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783437 |       0.42309  |   0.390496 |
| k-d_tree_polars      |     0.790653 |       0.545351 |   0.47208  |
| barab-szabi-1        |     0.787076 |       0.541095 |   0.483305 |
| Bori_Aron_solution-1 |     0.779505 |       0.706857 |   0.487437 |
| k-d_tree_pandas      |     0.79282  |       0.489666 |   0.664871 |
| k-d_tree_sklearn     |     0.800279 |       1.13338  |   0.772821 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785851 |       0.678714 |   0.426823 |
| Bori_Aron_solution-1 |     0.780161 |       1.34833  |   0.511527 |
| k-d_tree_polars      |     0.787639 |       0.86459  |   0.834599 |
| barab-szabi-1        |     0.784439 |       0.867268 |   0.86752  |
| k-d_tree_sklearn     |     0.801978 |       1.97198  |   0.873638 |
| k-d_tree_pandas      |     0.795037 |       0.76158  |   1.09545  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783766 |        5.20984 |   0.7402   |
| Bori_Aron_solution-1 |     0.772104 |       10.6616  |   0.771448 |
| k-d_tree_sklearn     |     0.799987 |       15.8948  |   1.03311  |
| k-d_tree_polars      |     0.798539 |        4.94085 |   6.45615  |
| barab-szabi-1        |     0.795337 |        4.98879 |   6.55926  |
| k-d_tree_pandas      |     0.797854 |        3.99727 |   6.79188  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.972268 |        71.8266 |    4.11548 |
| k-d_tree_sklearn     |     0.875591 |       227.004  |    4.58099 |
| Bori_Aron_solution-1 |     0.777543 |       149.925  |   18.4241  |