# 2024-09-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.51262  |       1e-06    |   0.348042 |
| barab-szabi-1        |     0.59666  |       0.392401 |   0.383819 |
| k-d_tree_polars      |     0.601959 |       0.397703 |   0.38861  |
| barab-szabi-2        |     0.611748 |       0.38681  |   0.430202 |
| Bori_Aron_solution-1 |     5.09087  |       0.480206 |   0.45143  |
| k-d_tree_pandas      |     5.51225  |       0.392883 |   0.528496 |
| k-d_tree_sklearn     |     3.64677  |       0.902182 |   0.938381 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.616729 |       0.404668 |   0.387305 |
| k-d_tree_polars      |     0.612871 |       0.400668 |   0.390176 |
| barab-szabi-2        |     0.621079 |       0.404603 |   0.398306 |
| Bori_Aron_solution-1 |     0.608566 |       0.528085 |   0.522183 |
| k-d_tree_pandas      |     0.606255 |       0.3784   |   0.530834 |
| k-d_tree_sklearn     |     0.615253 |       0.887267 |   0.980541 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611397 |       0.399969 |   0.39533  |
| k-d_tree_polars      |     0.610718 |       0.438838 |   0.420168 |
| barab-szabi-1        |     0.616763 |       0.434291 |   0.421521 |
| Bori_Aron_solution-1 |     0.609708 |       0.561835 |   0.519802 |
| k-d_tree_pandas      |     0.610969 |       0.43742  |   0.584256 |
| k-d_tree_sklearn     |     0.608998 |       0.93085  |   0.979807 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609752 |       0.457949 |   0.424074 |
| k-d_tree_polars      |     0.61221  |       0.526719 |   0.511932 |
| Bori_Aron_solution-1 |     0.603418 |       0.735036 |   0.536937 |
| barab-szabi-1        |     0.613841 |       0.528472 |   0.538955 |
| k-d_tree_pandas      |     0.610979 |       0.471485 |   0.713841 |
| k-d_tree_sklearn     |     0.618662 |       1.1413   |   1.04408  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601884 |       0.694695 |   0.462448 |
| Bori_Aron_solution-1 |     0.607205 |       1.35955  |   0.57127  |
| k-d_tree_polars      |     0.611499 |       0.842235 |   0.855431 |
| barab-szabi-1        |     0.614153 |       0.847306 |   0.893262 |
| k-d_tree_sklearn     |     0.613613 |       1.94071  |   1.11479  |
| k-d_tree_pandas      |     0.60956  |       0.734477 |   1.14552  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61325  |        5.1556  |   0.716997 |
| Bori_Aron_solution-1 |     0.605041 |       10.4783  |   0.817569 |
| k-d_tree_sklearn     |     0.607988 |       15.771   |   1.24938  |
| k-d_tree_polars      |     0.614391 |        4.79724 |   6.48408  |
| barab-szabi-1        |     0.615543 |        4.80136 |   6.50266  |
| k-d_tree_pandas      |     0.617579 |        3.84018 |   6.93009  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737195 |        72.0426 |    3.00093 |
| k-d_tree_sklearn     |     0.928892 |       226.862  |    4.25126 |
| Bori_Aron_solution-1 |     0.602607 |       148.817  |   16.6537  |