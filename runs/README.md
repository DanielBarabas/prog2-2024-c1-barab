# 2024-10-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7236   |       1e-06    |   0.383344 |
| barab-szabi-2        |     0.637371 |       0.400236 |   0.391231 |
| barab-szabi-1        |     0.623662 |       0.409503 |   0.394276 |
| k-d_tree_polars      |     0.66464  |       0.412546 |   0.404142 |
| Bori_Aron_solution-1 |     0.621356 |       0.541662 |   0.534403 |
| k-d_tree_pandas      |     0.625066 |       0.411792 |   0.543789 |
| k-d_tree_sklearn     |    10.4146   |       1.118    |   1.03561  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.67578  |       0.399025 |   0.392879 |
| barab-szabi-1        |     0.629694 |       0.415825 |   0.399769 |
| k-d_tree_polars      |     0.64454  |       0.423752 |   0.413677 |
| Bori_Aron_solution-1 |     0.6316   |       0.549632 |   0.544957 |
| k-d_tree_pandas      |     0.639332 |       0.447938 |   0.552304 |
| k-d_tree_sklearn     |     0.639529 |       0.91285  |   0.999529 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634349 |       0.404231 |   0.410031 |
| barab-szabi-1        |     0.632891 |       0.439363 |   0.435404 |
| k-d_tree_polars      |     0.63565  |       0.450755 |   0.441218 |
| Bori_Aron_solution-1 |     0.628118 |       0.595197 |   0.555833 |
| k-d_tree_pandas      |     0.637658 |       0.423251 |   0.605467 |
| k-d_tree_sklearn     |     0.637752 |       0.973058 |   1.05824  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648998 |       0.490967 |   0.439679 |
| k-d_tree_polars      |     0.641523 |       0.556803 |   0.541448 |
| barab-szabi-1        |     0.639876 |       0.563802 |   0.552015 |
| Bori_Aron_solution-1 |     0.644731 |       0.771805 |   0.564125 |
| k-d_tree_pandas      |     0.634321 |       0.515778 |   0.742328 |
| k-d_tree_sklearn     |     0.624005 |       1.21095  |   1.10483  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643637 |       0.744817 |   0.508952 |
| Bori_Aron_solution-1 |     0.635895 |       1.47722  |   0.608426 |
| k-d_tree_polars      |     0.66713  |       0.901881 |   0.914454 |
| barab-szabi-1        |     0.633153 |       0.888372 |   0.944237 |
| k-d_tree_pandas      |     0.64725  |       0.774951 |   1.20524  |
| k-d_tree_sklearn     |     0.661489 |       2.13963  |   1.24609  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632085 |        6.47767 |   0.865735 |
| Bori_Aron_solution-1 |     0.616654 |       11.4906  |   0.878302 |
| k-d_tree_sklearn     |     0.644599 |       18.74    |   1.34966  |
| k-d_tree_polars      |     0.647317 |        4.98102 |   7.18501  |
| barab-szabi-1        |     0.648071 |        4.99311 |   7.19599  |
| k-d_tree_pandas      |     0.637325 |        3.95449 |   7.64961  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634992 |        77.8535 |    3.38261 |
| k-d_tree_sklearn     |     0.635615 |       244.288  |    4.39311 |
| Bori_Aron_solution-1 |     0.646262 |       153.667  |   17.0081  |