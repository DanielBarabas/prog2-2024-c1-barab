# 2024-05-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.61212  |       0.348997 |   0.343498 |
| k-d_tree_polars      |     0.793538 |       0.402932 |   0.346363 |
| barab-szabi-1        |     0.792081 |       0.407427 |   0.349532 |
| solution-1           |     7.97828  |       1e-06    |   0.359935 |
| Bori_Aron_solution-1 |     4.62297  |       0.419721 |   0.407826 |
| k-d_tree_pandas      |     0.797084 |       0.387834 |   0.486439 |
| k-d_tree_sklearn     |     3.36548  |       0.913742 |   0.686547 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.797418 |       0.410747 |   0.351945 |
| barab-szabi-1        |     0.799199 |       0.410819 |   0.355886 |
| barab-szabi-2        |     0.791194 |       0.382297 |   0.385117 |
| Bori_Aron_solution-1 |     0.786307 |       0.485227 |   0.474623 |
| k-d_tree_pandas      |     0.792422 |       0.392734 |   0.498185 |
| k-d_tree_sklearn     |     0.798277 |       0.861319 |   0.690267 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791765 |       0.365379 |   0.364143 |
| k-d_tree_polars      |     0.792778 |       0.444895 |   0.376118 |
| barab-szabi-1        |     0.794338 |       0.434588 |   0.415738 |
| Bori_Aron_solution-1 |     0.788392 |       0.521726 |   0.479528 |
| k-d_tree_pandas      |     0.802401 |       0.410804 |   0.527947 |
| k-d_tree_sklearn     |     0.801965 |       0.904024 |   0.716694 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.79064  |       0.424897 |   0.388012 |
| k-d_tree_polars      |     0.798933 |       0.542846 |   0.474663 |
| Bori_Aron_solution-1 |     0.779703 |       0.704715 |   0.48952  |
| barab-szabi-1        |     0.796499 |       0.550563 |   0.492228 |
| k-d_tree_pandas      |     0.798089 |       0.489291 |   0.664654 |
| k-d_tree_sklearn     |     0.800052 |       1.13508  |   0.764538 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792839 |       0.678459 |   0.433454 |
| Bori_Aron_solution-1 |     0.790193 |       1.35236  |   0.517332 |
| k-d_tree_polars      |     0.787816 |       0.871733 |   0.831394 |
| k-d_tree_sklearn     |     0.805193 |       1.96063  |   0.869479 |
| barab-szabi-1        |     0.80716  |       0.871281 |   0.872707 |
| k-d_tree_pandas      |     0.798128 |       0.762065 |   1.09893  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789717 |        5.37572 |   0.756756 |
| Bori_Aron_solution-1 |     0.786137 |       10.8321  |   0.776098 |
| k-d_tree_sklearn     |     0.809495 |       16.1915  |   1.04235  |
| k-d_tree_polars      |     0.794599 |        4.97632 |   6.66215  |
| barab-szabi-1        |     0.79289  |        5.00625 |   6.70026  |
| k-d_tree_pandas      |     0.802614 |        4.0155  |   7.05748  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.15192  |        75.1557 |    4.24114 |
| k-d_tree_sklearn     |     0.921444 |       234.688  |    4.56556 |
| Bori_Aron_solution-1 |     0.785836 |       151.122  |   17.0661  |