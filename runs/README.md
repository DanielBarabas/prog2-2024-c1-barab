# 2026-06-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63401  |       1e-06    |   0.422604 |
| barab-szabi-2        |     8.2166   |       0.786946 |   0.4346   |
| barab-szabi-1        |     0.459137 |       0.401293 |   0.437182 |
| k-d_tree_polars      |     0.476045 |       0.401244 |   0.441192 |
| Bori_Aron_solution-1 |     0.453164 |       0.538752 |   0.539336 |
| k-d_tree_pandas      |     0.467993 |       0.381711 |   0.546968 |
| k-d_tree_sklearn     |     3.23752  |       1.22534  |   1.07235  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466733 |       0.436903 |   0.443572 |
| k-d_tree_polars      |     0.478272 |       0.413396 |   0.443838 |
| barab-szabi-1        |     0.467754 |       0.409207 |   0.448897 |
| Bori_Aron_solution-1 |     0.464827 |       0.555003 |   0.547276 |
| k-d_tree_pandas      |     0.475539 |       0.388043 |   0.563101 |
| k-d_tree_sklearn     |     0.471486 |       0.983015 |   1.06678  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472292 |       0.457097 |   0.463298 |
| k-d_tree_polars      |     0.474669 |       0.438215 |   0.470256 |
| barab-szabi-1        |     0.471206 |       0.442175 |   0.472847 |
| Bori_Aron_solution-1 |     0.465416 |       0.593718 |   0.546267 |
| k-d_tree_pandas      |     0.466745 |       0.412307 |   0.601647 |
| k-d_tree_sklearn     |     0.472163 |       1.02484  |   1.09763  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468713 |       0.508329 |   0.482066 |
| Bori_Aron_solution-1 |     0.463373 |       0.776366 |   0.555802 |
| k-d_tree_polars      |     0.467373 |       0.560383 |   0.567249 |
| barab-szabi-1        |     0.476537 |       0.556529 |   0.587407 |
| k-d_tree_pandas      |     0.469796 |       0.497204 |   0.731515 |
| k-d_tree_sklearn     |     0.469743 |       1.25211  |   1.14476  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468938 |       0.722365 |   0.511311 |
| Bori_Aron_solution-1 |     0.474096 |       1.44066  |   0.581873 |
| k-d_tree_polars      |     0.470045 |       0.930358 |   0.929126 |
| barab-szabi-1        |     0.469308 |       0.932821 |   0.975003 |
| k-d_tree_pandas      |     0.472626 |       0.788331 |   1.18319  |
| k-d_tree_sklearn     |     0.478747 |       2.11919  |   1.21349  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470829 |        5.32179 |   0.766456 |
| Bori_Aron_solution-1 |     0.46339  |       11.0608  |   0.875893 |
| k-d_tree_sklearn     |     0.473269 |       17.1674  |   1.33417  |
| k-d_tree_polars      |     0.466483 |        5.42107 |   6.6839   |
| barab-szabi-1        |     0.488807 |        5.34042 |   6.69251  |
| k-d_tree_pandas      |     0.477428 |        4.49285 |   7.26015  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475934 |         72.937 |    2.87733 |
| k-d_tree_sklearn     |     0.778316 |        244.944 |    4.13854 |
| Bori_Aron_solution-1 |     0.496273 |        147.747 |   26.705   |