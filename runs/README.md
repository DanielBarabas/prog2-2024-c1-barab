# 2025-11-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.540418 |       0.409403 |   0.436176 |
| barab-szabi-1        |     0.548841 |       0.42061  |   0.453715 |
| barab-szabi-2        |     0.563277 |       0.523432 |   0.46162  |
| solution-1           |     8.40686  |       1e-06    |   0.567598 |
| Bori_Aron_solution-1 |     0.531279 |       0.559635 |   0.604563 |
| k-d_tree_pandas      |     9.05654  |       0.467124 |   0.841228 |
| k-d_tree_sklearn     |     3.47714  |       1.30403  |   1.13347  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54373  |       0.434362 |   0.446218 |
| k-d_tree_polars      |     0.553183 |       0.440146 |   0.462414 |
| barab-szabi-1        |     0.552274 |       0.443076 |   0.48541  |
| Bori_Aron_solution-1 |     0.542952 |       0.588524 |   0.560226 |
| k-d_tree_pandas      |     0.542507 |       0.417351 |   0.579451 |
| k-d_tree_sklearn     |     0.547581 |       1.06506  |   1.11445  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547751 |       0.456693 |   0.463441 |
| barab-szabi-1        |     0.548161 |       0.478712 |   0.50705  |
| k-d_tree_polars      |     0.568534 |       0.530089 |   0.522732 |
| Bori_Aron_solution-1 |     0.561088 |       0.643467 |   0.575951 |
| k-d_tree_pandas      |     0.537358 |       0.42272  |   0.623894 |
| k-d_tree_sklearn     |     0.567636 |       1.12266  |   1.19764  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565146 |       0.524507 |   0.515458 |
| k-d_tree_polars      |     0.562409 |       0.594812 |   0.593743 |
| Bori_Aron_solution-1 |     0.58163  |       0.821484 |   0.593802 |
| barab-szabi-1        |     0.547425 |       0.602763 |   0.601819 |
| k-d_tree_pandas      |     0.550009 |       0.551605 |   0.779775 |
| k-d_tree_sklearn     |     0.592126 |       1.32735  |   1.26551  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.634553 |       1.6974   |   0.674884 |
| barab-szabi-2        |     0.580718 |       0.835639 |   0.697058 |
| k-d_tree_polars      |     0.599472 |       0.983006 |   1.0196   |
| barab-szabi-1        |     0.584667 |       1.01661  |   1.11629  |
| k-d_tree_pandas      |     0.566209 |       0.901067 |   1.27603  |
| k-d_tree_sklearn     |     0.582566 |       2.43254  |   1.34163  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.594571 |       12.8006  |   0.935574 |
| barab-szabi-2        |     0.578296 |        6.74271 |   1.15832  |
| k-d_tree_sklearn     |     0.57887  |       23.1454  |   1.58146  |
| barab-szabi-1        |     0.593412 |        5.77708 |   8.41561  |
| k-d_tree_polars      |     0.584519 |        5.71655 |   8.53582  |
| k-d_tree_pandas      |     0.582849 |        4.58302 |   8.69802  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578454 |        101.748 |    3.93607 |
| k-d_tree_sklearn     |     0.612745 |        254.94  |    4.22246 |
| Bori_Aron_solution-1 |     0.650772 |        160.1   |   18.4912  |