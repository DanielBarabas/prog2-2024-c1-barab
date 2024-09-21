# 2024-09-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.617256 |       0.405828 |   0.388973 |
| barab-szabi-2        |     0.619769 |       0.40314  |   0.39073  |
| k-d_tree_polars      |     0.621729 |       0.419173 |   0.414992 |
| Bori_Aron_solution-1 |     4.38324  |       0.669996 |   0.462015 |
| solution-1           |     7.67411  |       1e-06    |   0.497608 |
| k-d_tree_pandas      |     4.07622  |       0.440873 |   0.554632 |
| k-d_tree_sklearn     |     3.08786  |       1.04473  |   0.981908 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.625706 |       0.412242 |   0.398187 |
| barab-szabi-2        |     0.635296 |       0.414444 |   0.404622 |
| barab-szabi-1        |     0.631811 |       0.435914 |   0.410983 |
| Bori_Aron_solution-1 |     0.618638 |       0.535625 |   0.551323 |
| k-d_tree_pandas      |     0.623786 |       0.393735 |   0.559323 |
| k-d_tree_sklearn     |     0.642769 |       0.958455 |   1.02751  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631274 |       0.422619 |   0.40275  |
| k-d_tree_polars      |     0.632187 |       0.43743  |   0.426313 |
| barab-szabi-1        |     0.622096 |       0.439559 |   0.443735 |
| Bori_Aron_solution-1 |     0.6312   |       0.600446 |   0.544098 |
| k-d_tree_pandas      |     0.648444 |       0.411986 |   0.588521 |
| k-d_tree_sklearn     |     0.646269 |       0.969816 |   1.03059  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622846 |       0.472295 |   0.433006 |
| barab-szabi-1        |     0.630491 |       0.545887 |   0.533171 |
| k-d_tree_polars      |     0.637434 |       0.546111 |   0.534438 |
| Bori_Aron_solution-1 |     0.620887 |       0.755322 |   0.548323 |
| k-d_tree_pandas      |     0.622659 |       0.482663 |   0.73015  |
| k-d_tree_sklearn     |     0.635359 |       1.18491  |   1.08633  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632631 |       0.723742 |   0.475027 |
| Bori_Aron_solution-1 |     0.622215 |       1.43532  |   0.583339 |
| k-d_tree_polars      |     0.629254 |       0.883751 |   0.886116 |
| barab-szabi-1        |     0.632602 |       0.854843 |   0.924444 |
| k-d_tree_pandas      |     0.62626  |       0.754339 |   1.19122  |
| k-d_tree_sklearn     |     0.629831 |       2.06431  |   1.2133   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634606 |        5.51124 |   0.772298 |
| Bori_Aron_solution-1 |     0.621064 |       11.05    |   0.829458 |
| k-d_tree_sklearn     |     0.642459 |       17.1545  |   1.30832  |
| k-d_tree_polars      |     0.64214  |        4.85047 |   6.84095  |
| barab-szabi-1        |     0.636866 |        4.91547 |   7.03651  |
| k-d_tree_pandas      |     0.625337 |        3.86401 |   7.26613  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.715192 |        77.3105 |    3.30814 |
| k-d_tree_sklearn     |     0.842306 |       238.216  |    4.36212 |
| Bori_Aron_solution-1 |     0.623644 |       154.433  |   15.7725  |