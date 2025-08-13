# 2025-08-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566724 |       0.46777  |   0.45899  |
| solution-1           |     7.76179  |       1e-06    |   0.465286 |
| k-d_tree_polars      |     0.575667 |       0.441025 |   0.478516 |
| barab-szabi-1        |     0.551903 |       0.438606 |   0.525238 |
| Bori_Aron_solution-1 |     0.572635 |       0.617062 |   0.621718 |
| k-d_tree_pandas      |     8.24339  |       0.447644 |   0.765426 |
| k-d_tree_sklearn     |     3.55959  |       1.21141  |   1.17793  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.592577 |       0.440576 |   0.455145 |
| barab-szabi-2        |     0.58652  |       0.465585 |   0.463023 |
| k-d_tree_polars      |     0.587286 |       0.44311  |   0.468885 |
| k-d_tree_pandas      |     0.575054 |       0.421404 |   0.608474 |
| Bori_Aron_solution-1 |     0.580868 |       0.642974 |   0.61475  |
| k-d_tree_sklearn     |     0.569622 |       1.05785  |   1.19284  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565363 |       0.463737 |   0.475802 |
| k-d_tree_polars      |     0.605778 |       0.487728 |   0.497405 |
| barab-szabi-1        |     0.575832 |       0.481568 |   0.505311 |
| Bori_Aron_solution-1 |     0.568304 |       0.641222 |   0.597455 |
| k-d_tree_pandas      |     0.59125  |       0.453687 |   0.645359 |
| k-d_tree_sklearn     |     0.595114 |       1.12735  |   1.20852  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580477 |       0.562584 |   0.499635 |
| k-d_tree_polars      |     0.579889 |       0.588631 |   0.585869 |
| barab-szabi-1        |     0.581031 |       0.58217  |   0.628181 |
| Bori_Aron_solution-1 |     0.58861  |       0.836685 |   0.643816 |
| k-d_tree_pandas      |     0.577606 |       0.561645 |   0.795958 |
| k-d_tree_sklearn     |     0.571178 |       1.3671   |   1.25015  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579481 |       0.790965 |   0.530513 |
| Bori_Aron_solution-1 |     0.563401 |       1.44548  |   0.608434 |
| k-d_tree_polars      |     0.567695 |       0.91635  |   0.936422 |
| barab-szabi-1        |     0.568393 |       0.933256 |   1.03396  |
| k-d_tree_pandas      |     0.597725 |       0.794318 |   1.25617  |
| k-d_tree_sklearn     |     0.56632  |       2.14715  |   1.28948  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549117 |        5.4568  |   0.77284  |
| Bori_Aron_solution-1 |     0.583791 |       11.304   |   0.927628 |
| k-d_tree_sklearn     |     0.553274 |       17.4543  |   1.35764  |
| barab-szabi-1        |     0.581957 |        5.09086 |   6.72797  |
| k-d_tree_polars      |     0.556906 |        5.085   |   7.16706  |
| k-d_tree_pandas      |     0.558362 |        4.00012 |   7.16711  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591424 |        73.5296 |    2.77513 |
| k-d_tree_sklearn     |     0.581641 |       238.084  |    4.32688 |
| Bori_Aron_solution-1 |     0.629365 |       147.977  |   18.2564  |