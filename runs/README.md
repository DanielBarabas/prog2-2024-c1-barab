# 2026-10-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.463306 |       0.432554 |   0.449652 |
| barab-szabi-2        |     0.469292 |       0.493097 |   0.472869 |
| solution-1           |     8.68473  |       1e-06    |   0.540059 |
| k-d_tree_pandas      |     0.483719 |       0.390516 |   0.568496 |
| Bori_Aron_solution-1 |     0.477059 |       0.564993 |   0.573705 |
| barab-szabi-1        |     9.25768  |       0.514037 |   0.65326  |
| k-d_tree_sklearn     |     3.29461  |       1.35546  |   1.08513  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476722 |       0.448503 |   0.437753 |
| barab-szabi-1        |     0.484693 |       0.437526 |   0.444643 |
| k-d_tree_polars      |     0.501859 |       0.447127 |   0.454332 |
| Bori_Aron_solution-1 |     0.476119 |       0.575677 |   0.561642 |
| k-d_tree_pandas      |     0.486741 |       0.403838 |   0.578824 |
| k-d_tree_sklearn     |     0.490064 |       1.02578  |   1.13554  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481166 |       0.454674 |   0.451871 |
| k-d_tree_polars      |     0.477464 |       0.471562 |   0.477884 |
| barab-szabi-1        |     0.500782 |       0.481385 |   0.494028 |
| Bori_Aron_solution-1 |     0.485039 |       0.633519 |   0.576093 |
| k-d_tree_pandas      |     0.487919 |       0.428607 |   0.637739 |
| k-d_tree_sklearn     |     0.484668 |       1.08186  |   1.13677  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497389 |       0.524682 |   0.480795 |
| barab-szabi-1        |     0.490702 |       0.576188 |   0.579381 |
| k-d_tree_polars      |     0.483492 |       0.592646 |   0.581077 |
| Bori_Aron_solution-1 |     0.4916   |       0.78746  |   0.596144 |
| k-d_tree_pandas      |     0.478242 |       0.518334 |   0.756244 |
| k-d_tree_sklearn     |     0.490767 |       1.34308  |   1.23704  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486797 |       0.747132 |   0.506015 |
| Bori_Aron_solution-1 |     0.484091 |       1.4643   |   0.597615 |
| k-d_tree_polars      |     0.497743 |       0.931943 |   0.930602 |
| barab-szabi-1        |     0.533215 |       0.95414  |   1.00054  |
| k-d_tree_pandas      |     0.503206 |       0.832313 |   1.22641  |
| k-d_tree_sklearn     |     0.482363 |       2.1516   |   1.25504  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476267 |        5.55899 |   0.771862 |
| Bori_Aron_solution-1 |     0.48027  |       11.1639  |   0.830111 |
| k-d_tree_sklearn     |     0.491106 |       17.7886  |   1.38582  |
| k-d_tree_polars      |     0.488244 |        5.34382 |   6.87592  |
| barab-szabi-1        |     0.482836 |        5.42241 |   7.05103  |
| k-d_tree_pandas      |     0.488063 |        4.33153 |   7.36257  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.48129  |        76.3639 |    2.87855 |
| k-d_tree_sklearn     |     0.656664 |       240.446  |    3.86018 |
| Bori_Aron_solution-1 |     0.493505 |       157.005  |   16.7712  |