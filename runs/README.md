# 2026-02-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488168 |       0.433484 |   0.428295 |
| k-d_tree_polars      |     0.481356 |       0.402851 |   0.436808 |
| solution-1           |     7.83219  |       1e-06    |   0.453358 |
| Bori_Aron_solution-1 |     0.471749 |       0.547549 |   0.549113 |
| k-d_tree_pandas      |     0.492208 |       0.383685 |   0.554477 |
| barab-szabi-1        |     8.36495  |       0.499656 |   0.560743 |
| k-d_tree_sklearn     |     2.95221  |       1.10888  |   1.10299  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49146  |       0.438334 |   0.43295  |
| k-d_tree_polars      |     0.495478 |       0.411783 |   0.437622 |
| barab-szabi-1        |     0.495072 |       0.409407 |   0.439262 |
| Bori_Aron_solution-1 |     0.485196 |       0.562786 |   0.55341  |
| k-d_tree_pandas      |     0.504675 |       0.394222 |   0.56058  |
| k-d_tree_sklearn     |     0.491693 |       0.984288 |   1.11909  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492962 |       0.447933 |   0.444738 |
| barab-szabi-1        |     0.492512 |       0.438397 |   0.468334 |
| k-d_tree_polars      |     0.492221 |       0.440249 |   0.472343 |
| Bori_Aron_solution-1 |     0.484567 |       0.610838 |   0.558272 |
| k-d_tree_pandas      |     0.492066 |       0.432423 |   0.63707  |
| k-d_tree_sklearn     |     0.534646 |       1.08306  |   1.12741  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496858 |       0.511662 |   0.478861 |
| barab-szabi-1        |     0.499597 |       0.567311 |   0.573248 |
| Bori_Aron_solution-1 |     0.500077 |       0.803821 |   0.577111 |
| k-d_tree_polars      |     0.500499 |       0.56718  |   0.578335 |
| k-d_tree_pandas      |     0.503565 |       0.504161 |   0.74316  |
| k-d_tree_sklearn     |     0.497415 |       1.30557  |   1.18987  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510015 |       0.775859 |   0.519547 |
| Bori_Aron_solution-1 |     0.50627  |       1.51844  |   0.61324  |
| k-d_tree_polars      |     0.503331 |       0.936752 |   0.936986 |
| barab-szabi-1        |     0.519818 |       0.938046 |   0.985947 |
| k-d_tree_pandas      |     0.501977 |       0.842333 |   1.20987  |
| k-d_tree_sklearn     |     0.498605 |       2.16278  |   1.25831  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.511779 |        5.19533 |   0.749331 |
| Bori_Aron_solution-1 |     0.492309 |       11.0552  |   0.841971 |
| k-d_tree_sklearn     |     0.498104 |       17.1602  |   1.32543  |
| barab-szabi-1        |     0.515005 |        5.46943 |   6.5863   |
| k-d_tree_polars      |     0.510415 |        5.54983 |   6.5899   |
| k-d_tree_pandas      |     0.497651 |        4.42702 |   7.10166  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502558 |        75.1919 |    2.72731 |
| k-d_tree_sklearn     |     0.79404  |       245.718  |    4.14661 |
| Bori_Aron_solution-1 |     0.499928 |       152.879  |   14.6447  |