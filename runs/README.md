# 2025-03-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556223 |       0.40031  |   0.409331 |
| barab-szabi-2        |     0.569843 |       0.420535 |   0.413237 |
| barab-szabi-1        |     0.546175 |       0.422227 |   0.471296 |
| solution-1           |     7.73901  |       1e-06    |   0.529605 |
| Bori_Aron_solution-1 |     0.541044 |       0.540473 |   0.538952 |
| k-d_tree_pandas      |     7.92671  |       0.420523 |   0.711335 |
| k-d_tree_sklearn     |     3.01517  |       1.10813  |   1.03535  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565694 |       0.408213 |   0.402366 |
| k-d_tree_polars      |     0.607196 |       0.404785 |   0.411541 |
| barab-szabi-1        |     0.560102 |       0.403794 |   0.414132 |
| Bori_Aron_solution-1 |     0.555404 |       0.548405 |   0.539096 |
| k-d_tree_pandas      |     0.566509 |       0.393589 |   0.550651 |
| k-d_tree_sklearn     |     0.56933  |       0.954764 |   1.01858  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562745 |       0.420281 |   0.417236 |
| k-d_tree_polars      |     0.561995 |       0.431391 |   0.439488 |
| barab-szabi-1        |     0.560333 |       0.42952  |   0.449145 |
| Bori_Aron_solution-1 |     0.55603  |       0.580089 |   0.540941 |
| k-d_tree_pandas      |     0.567246 |       0.404014 |   0.592033 |
| k-d_tree_sklearn     |     0.569257 |       0.992265 |   1.04732  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567559 |       0.483813 |   0.446303 |
| k-d_tree_polars      |     0.565556 |       0.534714 |   0.534128 |
| barab-szabi-1        |     0.566497 |       0.53672  |   0.544424 |
| Bori_Aron_solution-1 |     0.553864 |       0.756255 |   0.555151 |
| k-d_tree_pandas      |     0.566027 |       0.475724 |   0.74883  |
| k-d_tree_sklearn     |     0.563944 |       1.22787  |   1.11952  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568193 |       0.721251 |   0.478077 |
| Bori_Aron_solution-1 |     0.566324 |       1.37793  |   0.609912 |
| k-d_tree_polars      |     0.570339 |       0.87521  |   0.88716  |
| barab-szabi-1        |     0.577836 |       0.863409 |   0.930716 |
| k-d_tree_pandas      |     0.568594 |       0.746234 |   1.16661  |
| k-d_tree_sklearn     |     0.567509 |       2.11202  |   1.22002  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568994 |        5.30698 |   0.704686 |
| Bori_Aron_solution-1 |     0.558806 |       10.5391  |   0.88188  |
| k-d_tree_sklearn     |     0.572131 |       16.159   |   1.31814  |
| barab-szabi-1        |     0.566311 |        4.82669 |   6.51395  |
| k-d_tree_polars      |     0.565263 |        4.94041 |   6.51929  |
| k-d_tree_pandas      |     0.568593 |        3.81078 |   6.94982  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.982654 |         75.606 |    3.44799 |
| k-d_tree_sklearn     |     0.712103 |        226.036 |    4.3292  |
| Bori_Aron_solution-1 |     0.560829 |        153.591 |   16.8898  |