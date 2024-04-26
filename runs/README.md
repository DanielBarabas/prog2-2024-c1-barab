# 2024-04-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.695671 |       0.339785 |   0.335062 |
| k-d_tree_polars      |     0.704957 |       0.400193 |   0.345312 |
| barab-szabi-1        |     8.15906  |       0.416317 |   0.349975 |
| solution-1           |     7.95195  |       1e-06    |   0.360852 |
| Bori_Aron_solution-1 |     0.703957 |       0.472931 |   0.475698 |
| k-d_tree_pandas      |     0.699261 |       0.391435 |   0.489957 |
| k-d_tree_sklearn     |     3.19466  |       0.89774  |   0.654493 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731767 |       0.358553 |   0.347339 |
| k-d_tree_polars      |     0.734219 |       0.40495  |   0.348889 |
| barab-szabi-1        |     0.742571 |       0.405556 |   0.349113 |
| Bori_Aron_solution-1 |     0.723838 |       0.47852  |   0.463912 |
| k-d_tree_pandas      |     0.743851 |       0.387998 |   0.482834 |
| k-d_tree_sklearn     |     0.733797 |       0.836506 |   0.659263 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734148 |       0.406511 |   0.36522  |
| k-d_tree_polars      |     0.734077 |       0.443313 |   0.373981 |
| barab-szabi-1        |     0.734509 |       0.431308 |   0.379595 |
| Bori_Aron_solution-1 |     0.714726 |       0.513505 |   0.478036 |
| k-d_tree_pandas      |     0.728939 |       0.403084 |   0.527508 |
| k-d_tree_sklearn     |     0.746443 |       0.896095 |   0.686067 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739752 |       0.429661 |   0.386071 |
| k-d_tree_polars      |     0.727034 |       0.543877 |   0.482423 |
| barab-szabi-1        |     0.737402 |       0.535715 |   0.482895 |
| Bori_Aron_solution-1 |     0.721304 |       0.705814 |   0.488987 |
| k-d_tree_pandas      |     0.737661 |       0.484425 |   0.665149 |
| k-d_tree_sklearn     |     0.739131 |       1.09781  |   0.743507 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72706  |       0.683536 |   0.424756 |
| Bori_Aron_solution-1 |     0.726102 |       1.35276  |   0.508561 |
| k-d_tree_polars      |     0.723385 |       0.842659 |   0.818445 |
| k-d_tree_sklearn     |     0.733672 |       1.91897  |   0.842073 |
| barab-szabi-1        |     0.73442  |       0.859343 |   0.86828  |
| k-d_tree_pandas      |     0.731426 |       0.752609 |   1.08863  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.734083 |       10.8876  |   0.794085 |
| barab-szabi-2        |     0.733293 |        5.38789 |   0.800038 |
| k-d_tree_sklearn     |     0.742003 |       15.9667  |   1.05417  |
| barab-szabi-1        |     0.731103 |        4.87156 |   6.6855   |
| k-d_tree_polars      |     0.736491 |        4.86148 |   6.71705  |
| k-d_tree_pandas      |     0.733284 |        3.8961  |   6.94433  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.886382 |        74.4228 |    4.17214 |
| k-d_tree_sklearn     |     0.797565 |       231.788  |    4.81815 |
| Bori_Aron_solution-1 |     0.747559 |       147.881  |   18.1098  |