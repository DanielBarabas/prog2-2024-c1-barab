# 2026-02-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.08845  |       1e-06    |   0.419541 |
| barab-szabi-2        |     0.485072 |       0.455576 |   0.435191 |
| k-d_tree_polars      |     0.494778 |       0.407417 |   0.440145 |
| barab-szabi-1        |     0.497019 |       0.408026 |   0.448663 |
| Bori_Aron_solution-1 |     0.508669 |       0.562058 |   0.548646 |
| k-d_tree_pandas      |     8.79561  |       0.405648 |   0.631154 |
| k-d_tree_sklearn     |     3.01168  |       1.05634  |   1.07368  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487984 |       0.440721 |   0.438659 |
| k-d_tree_polars      |     0.489222 |       0.411043 |   0.438684 |
| barab-szabi-1        |     0.4889   |       0.409031 |   0.447093 |
| Bori_Aron_solution-1 |     0.479664 |       0.563835 |   0.555759 |
| k-d_tree_pandas      |     0.489153 |       0.394978 |   0.563799 |
| k-d_tree_sklearn     |     0.496907 |       0.984139 |   1.08639  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49518  |       0.454102 |   0.449183 |
| k-d_tree_polars      |     0.495708 |       0.432976 |   0.468678 |
| barab-szabi-1        |     0.485698 |       0.44035  |   0.469149 |
| Bori_Aron_solution-1 |     0.486333 |       0.60141  |   0.560133 |
| k-d_tree_pandas      |     0.487181 |       0.405808 |   0.599693 |
| k-d_tree_sklearn     |     0.492037 |       1.05933  |   1.09125  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500682 |       0.524941 |   0.479947 |
| Bori_Aron_solution-1 |     0.48374  |       0.785435 |   0.564312 |
| k-d_tree_polars      |     0.488565 |       0.5558   |   0.564584 |
| barab-szabi-1        |     0.487608 |       0.557639 |   0.568079 |
| k-d_tree_pandas      |     0.48648  |       0.51034  |   0.749269 |
| k-d_tree_sklearn     |     0.494986 |       1.26452  |   1.14505  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48686  |       0.743049 |   0.514306 |
| Bori_Aron_solution-1 |     0.483266 |       1.45913  |   0.598372 |
| k-d_tree_polars      |     0.484715 |       0.932854 |   0.915974 |
| barab-szabi-1        |     0.489212 |       0.925218 |   0.948377 |
| k-d_tree_pandas      |     0.489057 |       0.813824 |   1.17909  |
| k-d_tree_sklearn     |     0.495162 |       2.12246  |   1.22898  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486608 |        5.15054 |   0.749193 |
| Bori_Aron_solution-1 |     0.484537 |       11.3726  |   0.858847 |
| k-d_tree_sklearn     |     0.49516  |       16.8695  |   1.31882  |
| barab-szabi-1        |     0.493781 |        5.54189 |   6.55983  |
| k-d_tree_polars      |     0.488428 |        5.66186 |   6.59731  |
| k-d_tree_pandas      |     0.499069 |        4.47733 |   6.89951  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502883 |        77.7166 |    2.75561 |
| k-d_tree_sklearn     |     0.509327 |       239.555  |    4.25743 |
| Bori_Aron_solution-1 |     0.657979 |       153.764  |   17.6659  |