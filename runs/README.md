# 2026-09-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465775 |       0.457671 |   0.443975 |
| k-d_tree_polars      |     0.473258 |       0.434438 |   0.494508 |
| solution-1           |     8.08454  |       1e-06    |   0.552371 |
| k-d_tree_pandas      |     0.488825 |       0.413417 |   0.57106  |
| Bori_Aron_solution-1 |     0.460796 |       0.566213 |   0.576791 |
| barab-szabi-1        |     9.19024  |       0.52526  |   0.647727 |
| k-d_tree_sklearn     |     3.05061  |       1.44368  |   1.14429  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.475456 |       0.419917 |   0.455456 |
| barab-szabi-2        |     0.47513  |       0.452695 |   0.460156 |
| k-d_tree_polars      |     0.47523  |       0.431659 |   0.460663 |
| Bori_Aron_solution-1 |     0.478872 |       0.569298 |   0.552908 |
| k-d_tree_pandas      |     0.479863 |       0.401234 |   0.580699 |
| k-d_tree_sklearn     |     0.498587 |       1.02278  |   1.1122   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495574 |       0.489178 |   0.4873   |
| k-d_tree_polars      |     0.483204 |       0.46681  |   0.497902 |
| barab-szabi-1        |     0.49575  |       0.450183 |   0.50169  |
| Bori_Aron_solution-1 |     0.481724 |       0.61649  |   0.575768 |
| k-d_tree_pandas      |     0.482554 |       0.430985 |   0.631596 |
| k-d_tree_sklearn     |     0.492104 |       1.08173  |   1.19885  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504224 |       0.539528 |   0.501126 |
| k-d_tree_polars      |     0.500768 |       0.613199 |   0.593927 |
| barab-szabi-1        |     0.493249 |       0.619021 |   0.607202 |
| Bori_Aron_solution-1 |     0.510556 |       0.81763  |   0.661752 |
| k-d_tree_pandas      |     0.489084 |       0.52851  |   0.784616 |
| k-d_tree_sklearn     |     0.497409 |       1.35812  |   1.22351  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501117 |       0.763077 |   0.566322 |
| Bori_Aron_solution-1 |     0.50644  |       1.51555  |   0.613617 |
| k-d_tree_polars      |     0.50496  |       0.956601 |   0.977506 |
| barab-szabi-1        |     0.499156 |       0.944565 |   1.00544  |
| k-d_tree_pandas      |     0.500456 |       0.841195 |   1.22842  |
| k-d_tree_sklearn     |     0.517657 |       2.30151  |   1.32401  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49629  |        5.2331  |   0.766936 |
| Bori_Aron_solution-1 |     0.519855 |       11.0704  |   0.831329 |
| k-d_tree_sklearn     |     0.490434 |       17.6369  |   1.37991  |
| k-d_tree_polars      |     0.479139 |        5.35955 |   6.90811  |
| barab-szabi-1        |     0.515123 |        5.44943 |   7.15264  |
| k-d_tree_pandas      |     0.507934 |        4.40054 |   7.58481  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.853193 |        73.6374 |    2.91523 |
| k-d_tree_sklearn     |     0.613502 |       243.724  |    3.8696  |
| Bori_Aron_solution-1 |     0.474158 |       154.206  |   15.2743  |