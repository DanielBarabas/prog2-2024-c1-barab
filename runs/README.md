# 2025-10-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.80077  |       1e-06    |   0.382159 |
| k-d_tree_polars      |     0.552588 |       0.404301 |   0.432807 |
| barab-szabi-2        |     0.55698  |       0.453551 |   0.435063 |
| barab-szabi-1        |     0.556075 |       0.42913  |   0.437441 |
| Bori_Aron_solution-1 |     0.540546 |       0.547669 |   0.548496 |
| k-d_tree_pandas      |     8.45081  |       0.433713 |   0.661145 |
| k-d_tree_sklearn     |     3.07431  |       1.03384  |   1.07204  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546897 |       0.426712 |   0.428117 |
| barab-szabi-1        |     0.549887 |       0.415782 |   0.434403 |
| k-d_tree_polars      |     0.552419 |       0.413636 |   0.434408 |
| Bori_Aron_solution-1 |     0.544406 |       0.556537 |   0.555899 |
| k-d_tree_pandas      |     0.5459   |       0.393515 |   0.561411 |
| k-d_tree_sklearn     |     0.552726 |       0.998672 |   1.0695   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577604 |       0.44243  |   0.447619 |
| barab-szabi-1        |     0.550052 |       0.438772 |   0.461888 |
| k-d_tree_polars      |     0.546946 |       0.443537 |   0.540811 |
| Bori_Aron_solution-1 |     0.545001 |       0.618772 |   0.559408 |
| k-d_tree_pandas      |     0.543583 |       0.411669 |   0.60028  |
| k-d_tree_sklearn     |     0.549718 |       1.0422   |   1.09836  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557113 |       0.507256 |   0.473368 |
| k-d_tree_polars      |     0.553747 |       0.568201 |   0.564063 |
| Bori_Aron_solution-1 |     0.541722 |       0.802995 |   0.574705 |
| barab-szabi-1        |     0.548956 |       0.58526  |   0.575026 |
| k-d_tree_pandas      |     0.551419 |       0.511138 |   0.736145 |
| k-d_tree_sklearn     |     0.551888 |       1.27401  |   1.14252  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550528 |       0.762098 |   0.502424 |
| Bori_Aron_solution-1 |     0.541437 |       1.51789  |   0.610054 |
| k-d_tree_polars      |     0.546264 |       0.966147 |   0.926312 |
| barab-szabi-1        |     0.547405 |       0.956939 |   0.999157 |
| k-d_tree_pandas      |     0.563814 |       0.821481 |   1.18711  |
| k-d_tree_sklearn     |     0.550928 |       2.22829  |   1.23038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5468   |        5.45748 |   0.764921 |
| Bori_Aron_solution-1 |     0.560548 |       11.9598  |   0.870901 |
| k-d_tree_sklearn     |     0.555434 |       17.212   |   1.34762  |
| barab-szabi-1        |     0.560819 |        5.69862 |   6.87247  |
| k-d_tree_polars      |     0.563935 |        5.76698 |   6.95332  |
| k-d_tree_pandas      |     0.556465 |        4.63235 |   7.17418  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557357 |        75.7695 |    2.83044 |
| k-d_tree_sklearn     |     0.579324 |       244.628  |    4.29646 |
| Bori_Aron_solution-1 |     0.796943 |       152.957  |   17.329   |