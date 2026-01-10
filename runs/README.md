# 2026-01-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.98513  |       1e-06    |   0.473957 |
| barab-szabi-1        |     0.601457 |       0.451812 |   0.480738 |
| k-d_tree_polars      |     0.585779 |       0.481338 |   0.504352 |
| barab-szabi-2        |     0.560747 |       0.544758 |   0.51547  |
| Bori_Aron_solution-1 |     0.585331 |       0.641901 |   0.629718 |
| k-d_tree_pandas      |     8.9587   |       0.479699 |   0.768709 |
| k-d_tree_sklearn     |     3.56148  |       1.21205  |   1.21257  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582736 |       0.506253 |   0.487975 |
| k-d_tree_polars      |     0.588107 |       0.475335 |   0.498713 |
| barab-szabi-1        |     0.599126 |       0.469074 |   0.512363 |
| Bori_Aron_solution-1 |     0.591029 |       0.669866 |   0.617303 |
| k-d_tree_pandas      |     0.596803 |       0.454669 |   0.642517 |
| k-d_tree_sklearn     |     0.607758 |       1.14428  |   1.22658  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.606807 |       0.48171  |   0.514995 |
| barab-szabi-2        |     0.580024 |       0.512696 |   0.516393 |
| k-d_tree_polars      |     0.580454 |       0.518457 |   0.524499 |
| Bori_Aron_solution-1 |     0.587295 |       0.678977 |   0.62977  |
| k-d_tree_pandas      |     0.584676 |       0.477397 |   0.702581 |
| k-d_tree_sklearn     |     0.602708 |       1.14362  |   1.23089  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587972 |       0.572467 |   0.541596 |
| k-d_tree_polars      |     0.579288 |       0.628486 |   0.620242 |
| barab-szabi-1        |     0.592595 |       0.616256 |   0.625326 |
| Bori_Aron_solution-1 |     0.581222 |       0.860797 |   0.654691 |
| k-d_tree_pandas      |     0.605682 |       0.551488 |   0.827361 |
| k-d_tree_sklearn     |     0.591435 |       1.44818  |   1.32186  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.580733 |       1.62702  |   0.679385 |
| barab-szabi-2        |     0.607876 |       0.855801 |   0.783224 |
| k-d_tree_polars      |     0.607372 |       0.974348 |   1.04226  |
| barab-szabi-1        |     0.591973 |       1.0152   |   1.09648  |
| k-d_tree_pandas      |     0.604939 |       0.875784 |   1.36143  |
| k-d_tree_sklearn     |     0.613416 |       2.50182  |   1.42314  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592414 |        5.9433  |   0.851401 |
| Bori_Aron_solution-1 |     0.594234 |       11.9878  |   0.898993 |
| k-d_tree_sklearn     |     0.607591 |       19.0233  |   1.46763  |
| barab-szabi-1        |     0.592092 |        5.55775 |   7.52733  |
| k-d_tree_polars      |     0.590383 |        5.57963 |   7.54913  |
| k-d_tree_pandas      |     0.599843 |        4.5903  |   7.84816  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564684 |        87.6645 |    2.97868 |
| k-d_tree_sklearn     |     0.62109  |       264.792  |    4.48311 |
| Bori_Aron_solution-1 |     0.737154 |       157.72   |   18.4572  |