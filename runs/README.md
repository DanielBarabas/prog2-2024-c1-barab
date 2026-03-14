# 2026-03-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480367 |       0.438959 |   0.432501 |
| k-d_tree_polars      |     0.486281 |       0.403992 |   0.436626 |
| solution-1           |     8.00296  |       1e-06    |   0.482953 |
| k-d_tree_pandas      |     0.483065 |       0.390752 |   0.549236 |
| Bori_Aron_solution-1 |     0.500286 |       0.547158 |   0.561242 |
| barab-szabi-1        |     8.2099   |       0.478011 |   0.667519 |
| k-d_tree_sklearn     |     3.28885  |       1.14384  |   1.07298  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493092 |       0.443466 |   0.435708 |
| k-d_tree_polars      |     0.495986 |       0.414702 |   0.444683 |
| barab-szabi-1        |     0.490466 |       0.414474 |   0.445168 |
| Bori_Aron_solution-1 |     0.48618  |       0.55956  |   0.546054 |
| k-d_tree_pandas      |     0.492803 |       0.396795 |   0.562864 |
| k-d_tree_sklearn     |     0.501718 |       0.972735 |   1.08545  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49883  |       0.45232  |   0.455739 |
| k-d_tree_polars      |     0.492987 |       0.440739 |   0.46758  |
| barab-szabi-1        |     0.494283 |       0.441981 |   0.468576 |
| Bori_Aron_solution-1 |     0.487824 |       0.599602 |   0.55116  |
| k-d_tree_pandas      |     0.492099 |       0.413348 |   0.603231 |
| k-d_tree_sklearn     |     0.503081 |       1.02387  |   1.09813  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495844 |       0.506643 |   0.484109 |
| k-d_tree_polars      |     0.491387 |       0.567552 |   0.567195 |
| Bori_Aron_solution-1 |     0.489274 |       0.787673 |   0.574796 |
| barab-szabi-1        |     0.496762 |       0.566596 |   0.579524 |
| k-d_tree_pandas      |     0.493419 |       0.508261 |   0.740142 |
| k-d_tree_sklearn     |     0.496732 |       1.27521  |   1.14749  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495475 |       0.729818 |   0.518316 |
| Bori_Aron_solution-1 |     0.487287 |       1.46197  |   0.588445 |
| k-d_tree_polars      |     0.496119 |       0.938392 |   0.913983 |
| barab-szabi-1        |     0.490965 |       0.94852  |   0.944065 |
| k-d_tree_pandas      |     0.493335 |       0.833739 |   1.18239  |
| k-d_tree_sklearn     |     0.495427 |       2.12391  |   1.22037  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496321 |        4.95885 |   0.766917 |
| Bori_Aron_solution-1 |     0.489307 |       11.0997  |   0.827422 |
| k-d_tree_sklearn     |     0.502852 |       16.5004  |   1.32225  |
| barab-szabi-1        |     0.491622 |        5.69544 |   6.48219  |
| k-d_tree_polars      |     0.491751 |        5.60886 |   6.52814  |
| k-d_tree_pandas      |     0.495312 |        4.54424 |   6.96832  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492027 |        74.1792 |    2.76602 |
| k-d_tree_sklearn     |     0.89073  |       241.795  |    3.99862 |
| Bori_Aron_solution-1 |     0.495771 |       155.176  |   14.4022  |