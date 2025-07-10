# 2025-07-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.572351 |       0.418271 |   0.432291 |
| k-d_tree_polars      |     0.569247 |       0.432697 |   0.434762 |
| barab-szabi-2        |     0.633022 |       0.452952 |   0.441791 |
| solution-1           |     7.70481  |       1e-06    |   0.489671 |
| Bori_Aron_solution-1 |     0.561465 |       0.563613 |   0.56023  |
| k-d_tree_pandas      |     0.570884 |       0.396186 |   0.566584 |
| k-d_tree_sklearn     |    10.2915   |       1.42104  |   1.11233  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593277 |       0.429082 |   0.432408 |
| k-d_tree_polars      |     0.572124 |       0.421382 |   0.436308 |
| barab-szabi-1        |     0.573326 |       0.423848 |   0.443166 |
| Bori_Aron_solution-1 |     0.567029 |       0.578259 |   0.568335 |
| k-d_tree_pandas      |     0.580661 |       0.401699 |   0.582592 |
| k-d_tree_sklearn     |     0.579275 |       1.03294  |   1.11027  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580857 |       0.467571 |   0.45262  |
| barab-szabi-1        |     0.567541 |       0.473095 |   0.475972 |
| k-d_tree_polars      |     0.563271 |       0.452827 |   0.476815 |
| Bori_Aron_solution-1 |     0.577948 |       0.636884 |   0.587293 |
| k-d_tree_pandas      |     0.578149 |       0.433653 |   0.615017 |
| k-d_tree_sklearn     |     0.575529 |       1.05194  |   1.14268  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599977 |       0.53574  |   0.495453 |
| barab-szabi-1        |     0.585917 |       0.582867 |   0.591488 |
| k-d_tree_polars      |     0.582847 |       0.597912 |   0.601642 |
| Bori_Aron_solution-1 |     0.578715 |       0.811955 |   0.657155 |
| k-d_tree_pandas      |     0.611444 |       0.505908 |   0.788122 |
| k-d_tree_sklearn     |     0.597648 |       1.35326  |   1.22518  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584117 |       0.785466 |   0.555146 |
| Bori_Aron_solution-1 |     0.574062 |       1.47562  |   0.617437 |
| k-d_tree_polars      |     0.585537 |       0.917067 |   0.983702 |
| barab-szabi-1        |     0.590953 |       0.937028 |   1.00914  |
| k-d_tree_pandas      |     0.592059 |       0.782737 |   1.23455  |
| k-d_tree_sklearn     |     0.589039 |       2.31509  |   1.30181  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565543 |        5.66513 |   0.775337 |
| Bori_Aron_solution-1 |     0.56699  |       11.1482  |   0.869765 |
| k-d_tree_sklearn     |     0.585173 |       17.6822  |   1.4036   |
| k-d_tree_polars      |     0.591883 |        5.05657 |   7.07624  |
| barab-szabi-1        |     0.595607 |        5.06538 |   7.21388  |
| k-d_tree_pandas      |     0.586247 |        3.94249 |   7.53086  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588882 |        77.7743 |    2.88506 |
| k-d_tree_sklearn     |     0.573335 |       245.833  |    4.05691 |
| Bori_Aron_solution-1 |     0.57544  |       152.041  |   16.4716  |