# 2024-05-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     6.04954  |       0.435644 |   0.334259 |
| barab-szabi-1        |     0.770209 |       0.392047 |   0.341113 |
| k-d_tree_polars      |     0.771674 |       0.391206 |   0.369653 |
| Bori_Aron_solution-1 |     5.49079  |       0.401134 |   0.399439 |
| k-d_tree_pandas      |     0.775352 |       0.375567 |   0.467491 |
| solution-1           |     8.80121  |       1e-06    |   0.63547  |
| k-d_tree_sklearn     |     3.60844  |       1.06538  |   0.651366 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.772066 |       0.344973 |   0.333995 |
| barab-szabi-1        |     0.771735 |       0.401033 |   0.351368 |
| k-d_tree_polars      |     0.77702  |       0.403414 |   0.364144 |
| Bori_Aron_solution-1 |     0.760292 |       0.474476 |   0.463438 |
| k-d_tree_pandas      |     0.771815 |       0.380387 |   0.47831  |
| k-d_tree_sklearn     |     0.781165 |       0.828741 |   0.678282 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.771215 |       0.359198 |   0.359702 |
| k-d_tree_polars      |     0.78393  |       0.424662 |   0.376518 |
| barab-szabi-1        |     0.775407 |       0.42491  |   0.378376 |
| Bori_Aron_solution-1 |     0.766636 |       0.51413  |   0.467598 |
| k-d_tree_pandas      |     0.766573 |       0.395879 |   0.525755 |
| k-d_tree_sklearn     |     0.779075 |       0.877764 |   0.680609 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796296 |       0.430415 |   0.387025 |
| k-d_tree_polars      |     0.768976 |       0.534192 |   0.477166 |
| Bori_Aron_solution-1 |     0.7628   |       0.695881 |   0.479092 |
| barab-szabi-1        |     0.776397 |       0.532918 |   0.486399 |
| k-d_tree_pandas      |     0.772991 |       0.482666 |   0.65643  |
| k-d_tree_sklearn     |     0.777936 |       1.096    |   0.748911 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.772854 |       0.670592 |   0.423841 |
| Bori_Aron_solution-1 |     0.762225 |       1.34038  |   0.504148 |
| k-d_tree_polars      |     0.777662 |       0.863442 |   0.824027 |
| k-d_tree_sklearn     |     0.77879  |       1.89962  |   0.839453 |
| barab-szabi-1        |     0.7727   |       0.865087 |   0.853755 |
| k-d_tree_pandas      |     0.774107 |       0.774108 |   1.08079  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.770079 |        5.0946  |   0.719384 |
| Bori_Aron_solution-1 |     0.762346 |       10.4758  |   0.76106  |
| k-d_tree_sklearn     |     0.787307 |       15.9282  |   1.06362  |
| barab-szabi-1        |     0.78536  |        4.94212 |   6.34417  |
| k-d_tree_polars      |     0.794165 |        4.95993 |   6.35845  |
| k-d_tree_pandas      |     0.793644 |        4.02864 |   6.71952  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.994984 |        71.7225 |    3.85522 |
| k-d_tree_sklearn     |     0.871902 |       225.859  |    4.73109 |
| Bori_Aron_solution-1 |     0.775277 |       148.019  |   16.9497  |