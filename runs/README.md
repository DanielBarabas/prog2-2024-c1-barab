# 2025-01-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.22479  |       0.580121 |   0.409132 |
| k-d_tree_polars      |     0.588016 |       0.415437 |   0.420197 |
| barab-szabi-1        |     0.638809 |       0.417066 |   0.427067 |
| solution-1           |     7.9864   |       1e-06    |   0.485131 |
| k-d_tree_pandas      |     0.605273 |       0.411163 |   0.572326 |
| Bori_Aron_solution-1 |     0.598921 |       0.573696 |   0.577125 |
| k-d_tree_sklearn     |     3.31608  |       1.14156  |   1.08104  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.618894 |       0.44146  |   0.424917 |
| barab-szabi-2        |     0.603404 |       0.429002 |   0.428999 |
| k-d_tree_polars      |     0.616634 |       0.440669 |   0.447811 |
| Bori_Aron_solution-1 |     0.605751 |       0.581227 |   0.564079 |
| k-d_tree_pandas      |     0.607521 |       0.41596  |   0.568754 |
| k-d_tree_sklearn     |     0.628921 |       1.01446  |   1.11444  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.673079 |       0.454294 |   0.452207 |
| barab-szabi-1        |     0.610017 |       0.455912 |   0.453633 |
| barab-szabi-2        |     0.612221 |       0.437551 |   0.456428 |
| Bori_Aron_solution-1 |     0.608134 |       0.633824 |   0.572326 |
| k-d_tree_pandas      |     0.616338 |       0.445522 |   0.626755 |
| k-d_tree_sklearn     |     0.612836 |       1.08275  |   1.12685  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618446 |       0.492506 |   0.476577 |
| k-d_tree_polars      |     0.606541 |       0.559003 |   0.542438 |
| barab-szabi-1        |     0.608755 |       0.576185 |   0.568068 |
| Bori_Aron_solution-1 |     0.620756 |       0.765342 |   0.576307 |
| k-d_tree_pandas      |     0.615388 |       0.498801 |   0.747683 |
| k-d_tree_sklearn     |     0.619311 |       1.26635  |   1.20031  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614215 |       0.761628 |   0.515321 |
| Bori_Aron_solution-1 |     0.616161 |       1.43293  |   0.609816 |
| k-d_tree_polars      |     0.610105 |       0.910631 |   0.943597 |
| barab-szabi-1        |     0.599818 |       0.898638 |   0.976323 |
| k-d_tree_pandas      |     0.616282 |       0.762619 |   1.23196  |
| k-d_tree_sklearn     |     0.611575 |       2.15565  |   1.27402  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608432 |        5.58598 |   0.784357 |
| Bori_Aron_solution-1 |     0.596442 |       11.1309  |   0.907044 |
| k-d_tree_sklearn     |     0.625767 |       17.154   |   1.38272  |
| k-d_tree_polars      |     0.603604 |        5.01721 |   6.85615  |
| barab-szabi-1        |     0.609923 |        5.02607 |   6.94802  |
| k-d_tree_pandas      |     0.620404 |        3.83848 |   7.30839  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614234 |        77.3458 |    3.07373 |
| k-d_tree_sklearn     |     0.620513 |       234.626  |    4.48378 |
| Bori_Aron_solution-1 |     0.65404  |       153.647  |   16.4158  |