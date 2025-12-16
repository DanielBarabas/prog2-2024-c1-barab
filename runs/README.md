# 2025-12-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525305 |       0.535692 |   0.440651 |
| barab-szabi-1        |     0.539446 |       0.41875  |   0.45195  |
| k-d_tree_polars      |     0.550517 |       0.420116 |   0.456961 |
| Bori_Aron_solution-1 |     0.542036 |       0.563543 |   0.569502 |
| solution-1           |     8.66092  |       1e-06    |   0.592516 |
| k-d_tree_pandas      |     9.34574  |       0.475908 |   0.69431  |
| k-d_tree_sklearn     |     3.19509  |       1.1542   |   1.08991  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545878 |       0.442937 |   0.443022 |
| barab-szabi-1        |     0.54283  |       0.426705 |   0.445733 |
| k-d_tree_polars      |     0.539231 |       0.418324 |   0.454496 |
| Bori_Aron_solution-1 |     0.537569 |       0.606207 |   0.580538 |
| k-d_tree_pandas      |     0.545521 |       0.407102 |   0.591786 |
| k-d_tree_sklearn     |     0.543832 |       0.984285 |   1.0866   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.537564 |       0.443674 |   0.469436 |
| barab-szabi-1        |     0.5345   |       0.448129 |   0.473883 |
| barab-szabi-2        |     0.568356 |       0.462108 |   0.475036 |
| Bori_Aron_solution-1 |     0.528674 |       0.6196   |   0.572968 |
| k-d_tree_pandas      |     0.549598 |       0.431457 |   0.623306 |
| k-d_tree_sklearn     |     0.565873 |       1.07191  |   1.12882  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538742 |       0.556136 |   0.507799 |
| Bori_Aron_solution-1 |     0.570908 |       0.845948 |   0.600722 |
| k-d_tree_polars      |     0.558865 |       0.590681 |   0.604568 |
| barab-szabi-1        |     0.566616 |       0.599656 |   0.620157 |
| k-d_tree_pandas      |     0.531645 |       0.520261 |   0.756948 |
| k-d_tree_sklearn     |     0.56631  |       1.35977  |   1.23813  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557763 |       0.777401 |   0.558292 |
| Bori_Aron_solution-1 |     0.558875 |       1.53572  |   0.641107 |
| k-d_tree_polars      |     0.564198 |       0.949313 |   0.964224 |
| barab-szabi-1        |     0.559795 |       0.944653 |   1.00409  |
| k-d_tree_pandas      |     0.562708 |       0.850915 |   1.24313  |
| k-d_tree_sklearn     |     0.567641 |       2.31909  |   1.34819  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556893 |        5.61364 |   0.806816 |
| Bori_Aron_solution-1 |     0.578901 |       11.8133  |   0.879034 |
| k-d_tree_sklearn     |     0.57835  |       18.4542  |   1.4386   |
| k-d_tree_polars      |     0.56622  |        5.47505 |   7.16677  |
| barab-szabi-1        |     0.581221 |        5.52637 |   7.19312  |
| k-d_tree_pandas      |     0.571883 |        4.50597 |   7.54441  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559738 |        82.0506 |    2.87065 |
| k-d_tree_sklearn     |     0.573213 |       248.671  |    4.30942 |
| Bori_Aron_solution-1 |     0.664586 |       155.791  |   18.2489  |