# 2025-10-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.599897 |       0.439159 |   0.470857 |
| barab-szabi-1        |     0.583452 |       0.456605 |   0.47229  |
| barab-szabi-2        |     0.861467 |       0.644017 |   0.493728 |
| solution-1           |     8.52195  |       1e-06    |   0.500582 |
| Bori_Aron_solution-1 |     0.602245 |       0.609939 |   0.631807 |
| k-d_tree_pandas      |     9.80733  |       0.453208 |   0.813498 |
| k-d_tree_sklearn     |     3.299    |       1.27395  |   1.19306  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586309 |       0.484473 |   0.480058 |
| k-d_tree_polars      |     0.58832  |       0.47137  |   0.481464 |
| barab-szabi-1        |     0.594547 |       0.457276 |   0.489821 |
| Bori_Aron_solution-1 |     0.581658 |       0.614026 |   0.624649 |
| k-d_tree_pandas      |     0.618728 |       0.438602 |   0.628704 |
| k-d_tree_sklearn     |     0.59178  |       1.10274  |   1.18792  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585531 |       0.486241 |   0.484205 |
| k-d_tree_polars      |     0.589905 |       0.485075 |   0.505976 |
| barab-szabi-1        |     0.59919  |       0.487446 |   0.507631 |
| Bori_Aron_solution-1 |     0.591007 |       0.669996 |   0.616228 |
| k-d_tree_pandas      |     0.596951 |       0.451519 |   0.684225 |
| k-d_tree_sklearn     |     0.590933 |       1.17667  |   1.20768  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594292 |       0.557006 |   0.503763 |
| barab-szabi-1        |     0.584278 |       0.611752 |   0.60383  |
| k-d_tree_polars      |     0.582889 |       0.594065 |   0.607858 |
| Bori_Aron_solution-1 |     0.575922 |       0.877938 |   0.631738 |
| k-d_tree_pandas      |     0.608724 |       0.543515 |   0.817185 |
| k-d_tree_sklearn     |     0.58376  |       1.37814  |   1.27316  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602826 |       0.830512 |   0.632149 |
| Bori_Aron_solution-1 |     0.586548 |       1.56851  |   0.655175 |
| k-d_tree_polars      |     0.581667 |       0.984536 |   1.02739  |
| barab-szabi-1        |     0.615073 |       0.940245 |   1.03068  |
| k-d_tree_pandas      |     0.591826 |       0.869442 |   1.27032  |
| k-d_tree_sklearn     |     0.595109 |       2.41542  |   1.3852   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577147 |        5.81576 |   0.79917  |
| Bori_Aron_solution-1 |     0.601346 |       11.9494  |   0.896615 |
| k-d_tree_sklearn     |     0.594302 |       18.9247  |   1.50946  |
| k-d_tree_polars      |     0.597394 |        5.60479 |   7.34495  |
| barab-szabi-1        |     0.599634 |        5.57181 |   7.40546  |
| k-d_tree_pandas      |     0.607428 |        4.58978 |   7.68093  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591535 |        79.2024 |    2.89677 |
| k-d_tree_sklearn     |     0.604478 |       255.331  |    4.56079 |
| Bori_Aron_solution-1 |     0.801684 |       154.053  |   18.6338  |