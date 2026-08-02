# 2026-08-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.467346 |       0.413982 |   0.447029 |
| solution-1           |     7.22596  |       1e-06    |   0.447227 |
| barab-szabi-2        |     0.467033 |       0.436041 |   0.460912 |
| k-d_tree_pandas      |     0.467765 |       0.387122 |   0.544891 |
| Bori_Aron_solution-1 |     0.450936 |       0.547981 |   0.557579 |
| k-d_tree_polars      |     8.12213  |       0.475554 |   0.629013 |
| k-d_tree_sklearn     |     2.83626  |       1.15372  |   1.06794  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475375 |       0.447392 |   0.451184 |
| barab-szabi-1        |     0.483659 |       0.422693 |   0.462661 |
| k-d_tree_polars      |     0.489786 |       0.433696 |   0.463565 |
| Bori_Aron_solution-1 |     0.583168 |       0.572686 |   0.556342 |
| k-d_tree_pandas      |     0.506504 |       0.400303 |   0.569025 |
| k-d_tree_sklearn     |     0.47272  |       1.01051  |   1.07703  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465578 |       0.455405 |   0.453937 |
| k-d_tree_polars      |     0.482229 |       0.459501 |   0.476072 |
| barab-szabi-1        |     0.468327 |       0.505682 |   0.479063 |
| Bori_Aron_solution-1 |     0.459992 |       0.592143 |   0.56643  |
| k-d_tree_pandas      |     0.474634 |       0.412743 |   0.597126 |
| k-d_tree_sklearn     |     0.481172 |       1.0625   |   1.09897  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46972  |       0.505645 |   0.479448 |
| Bori_Aron_solution-1 |     0.46035  |       0.768325 |   0.556472 |
| k-d_tree_polars      |     0.469934 |       0.587164 |   0.566572 |
| barab-szabi-1        |     0.4666   |       0.554331 |   0.577861 |
| k-d_tree_pandas      |     0.469282 |       0.492712 |   0.726419 |
| k-d_tree_sklearn     |     0.465918 |       1.27558  |   1.13448  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467577 |       0.722152 |   0.510022 |
| Bori_Aron_solution-1 |     0.468287 |       1.40984  |   0.580253 |
| k-d_tree_polars      |     0.477538 |       0.900108 |   0.916841 |
| barab-szabi-1        |     0.46913  |       0.899635 |   0.963511 |
| k-d_tree_pandas      |     0.469223 |       0.793708 |   1.16339  |
| k-d_tree_sklearn     |     0.479198 |       2.11263  |   1.21749  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464839 |        5.19759 |   0.753808 |
| Bori_Aron_solution-1 |     0.462515 |       10.9985  |   0.808686 |
| k-d_tree_sklearn     |     0.466633 |       17.0461  |   1.34987  |
| barab-szabi-1        |     0.486197 |        5.35398 |   6.70228  |
| k-d_tree_polars      |     0.468402 |        5.41931 |   6.72595  |
| k-d_tree_pandas      |     0.470807 |        4.30626 |   7.03769  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579581 |        70.1177 |    2.76245 |
| k-d_tree_sklearn     |     0.830283 |       239.513  |    4.01509 |
| Bori_Aron_solution-1 |     0.463733 |       151.653  |   24.8087  |