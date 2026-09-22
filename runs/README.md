# 2026-09-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.84069  |       0.354021 |   0.35674  |
| k-d_tree_polars      |     0.837596 |       0.32253  |   0.368971 |
| Bori_Aron_solution-1 |     0.836781 |       0.430451 |   0.418978 |
| k-d_tree_pandas      |     0.84553  |       0.303356 |   0.425051 |
| solution-1           |     7.18396  |       1e-06    |   0.489172 |
| barab-szabi-1        |     8.16219  |       0.451811 |   0.757472 |
| k-d_tree_sklearn     |     2.91841  |       1.12819  |   0.830053 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.35688  |       0.35694  |   0.3471   |
| k-d_tree_polars      |     0.353056 |       0.334024 |   0.364222 |
| barab-szabi-1        |     0.85594  |       0.328988 |   0.377251 |
| k-d_tree_pandas      |     0.862186 |       0.31736  |   0.433755 |
| Bori_Aron_solution-1 |     0.762311 |       0.438914 |   0.448316 |
| k-d_tree_sklearn     |     0.365308 |       0.79433  |   0.843811 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.354666 |       0.365452 |   0.355027 |
| k-d_tree_polars      |     0.358383 |       0.358723 |   0.385424 |
| barab-szabi-1        |     0.358723 |       0.358222 |   0.400553 |
| Bori_Aron_solution-1 |     0.358506 |       0.473196 |   0.46326  |
| k-d_tree_pandas      |     0.363245 |       0.327467 |   0.467619 |
| k-d_tree_sklearn     |     0.357301 |       0.799584 |   0.834053 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359786 |       0.418418 |   0.392835 |
| Bori_Aron_solution-1 |     0.354996 |       0.607704 |   0.441012 |
| k-d_tree_polars      |     0.357912 |       0.458641 |   0.45559  |
| barab-szabi-1        |     0.353796 |       0.495484 |   0.466383 |
| k-d_tree_pandas      |     0.351638 |       0.403273 |   0.565548 |
| k-d_tree_sklearn     |     0.361031 |       0.986685 |   0.865472 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.353333 |       0.611843 |   0.426405 |
| Bori_Aron_solution-1 |     0.351277 |       1.1128   |   0.47189  |
| k-d_tree_polars      |     0.3571   |       0.724472 |   0.722425 |
| barab-szabi-1        |     0.361768 |       0.721918 |   0.744798 |
| k-d_tree_pandas      |     0.356424 |       0.618039 |   0.889922 |
| k-d_tree_sklearn     |     0.360626 |       1.66468  |   0.906327 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360695 |        3.45532 |   0.569838 |
| Bori_Aron_solution-1 |     0.355088 |        7.86069 |   0.758599 |
| k-d_tree_sklearn     |     0.369279 |       11.5893  |   1.03925  |
| barab-szabi-1        |     0.355663 |        4.97479 |   4.58119  |
| k-d_tree_polars      |     0.36271  |        4.69237 |   4.71087  |
| k-d_tree_pandas      |     0.358176 |        3.22646 |   4.88197  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538477 |        54.4892 |    2.37691 |
| k-d_tree_sklearn     |     0.465201 |       147.825  |    3.37715 |
| Bori_Aron_solution-1 |     0.369634 |       133.673  |   26.6534  |