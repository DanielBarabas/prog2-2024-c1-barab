# 2026-01-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46891  |       0.505913 |   0.398493 |
| barab-szabi-1        |     0.477847 |       0.382852 |   0.406971 |
| k-d_tree_polars      |     0.47368  |       0.369874 |   0.438977 |
| solution-1           |     7.23179  |       1e-06    |   0.482018 |
| Bori_Aron_solution-1 |     0.474733 |       0.499278 |   0.50344  |
| k-d_tree_pandas      |     8.25269  |       0.388784 |   0.826835 |
| k-d_tree_sklearn     |     2.8062   |       1.00324  |   0.968096 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47615  |       0.40645  |   0.410224 |
| k-d_tree_polars      |     0.478408 |       0.384767 |   0.41376  |
| barab-szabi-1        |     0.480713 |       0.382032 |   0.415785 |
| Bori_Aron_solution-1 |     0.470876 |       0.514559 |   0.515732 |
| k-d_tree_pandas      |     0.475734 |       0.374614 |   0.523984 |
| k-d_tree_sklearn     |     0.482313 |       0.89203  |   0.984014 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487267 |       0.424623 |   0.419164 |
| k-d_tree_polars      |     0.482723 |       0.418054 |   0.431238 |
| barab-szabi-1        |     0.494417 |       0.413316 |   0.443004 |
| Bori_Aron_solution-1 |     0.471089 |       0.576963 |   0.51643  |
| k-d_tree_pandas      |     0.476404 |       0.390092 |   0.561219 |
| k-d_tree_sklearn     |     0.488553 |       0.953286 |   0.985088 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474731 |       0.481503 |   0.449862 |
| k-d_tree_polars      |     0.477982 |       0.532005 |   0.518864 |
| Bori_Aron_solution-1 |     0.471066 |       0.715147 |   0.528566 |
| barab-szabi-1        |     0.476121 |       0.529752 |   0.532412 |
| k-d_tree_pandas      |     0.4775   |       0.458586 |   0.672184 |
| k-d_tree_sklearn     |     0.483033 |       1.14009  |   1.03836  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478456 |       0.695499 |   0.498464 |
| Bori_Aron_solution-1 |     0.46661  |       1.29719  |   0.554677 |
| k-d_tree_polars      |     0.471318 |       0.837703 |   0.818841 |
| barab-szabi-1        |     0.478135 |       0.833441 |   0.850998 |
| k-d_tree_pandas      |     0.47289  |       0.72116  |   1.06788  |
| k-d_tree_sklearn     |     0.481614 |       1.91278  |   1.10047  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480143 |        4.69113 |   0.690431 |
| Bori_Aron_solution-1 |     0.469665 |        9.96883 |   0.914535 |
| k-d_tree_sklearn     |     0.4849   |       14.4214  |   1.24037  |
| barab-szabi-1        |     0.472595 |        4.91    |   6.12802  |
| k-d_tree_polars      |     0.483739 |        4.89694 |   6.15642  |
| k-d_tree_pandas      |     0.475243 |        3.79674 |   6.44514  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48387  |         87.71  |    3.0754  |
| k-d_tree_sklearn     |     0.524962 |        173.714 |    4.30487 |
| Bori_Aron_solution-1 |     0.57111  |        138.748 |   17.5087  |