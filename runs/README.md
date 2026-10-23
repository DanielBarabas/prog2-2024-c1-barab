# 2026-10-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470118 |       0.423631 |   0.428047 |
| k-d_tree_polars      |     0.466152 |       0.426454 |   0.440475 |
| solution-1           |    10.0058   |       1e-06    |   0.481495 |
| barab-szabi-1        |     9.12354  |       0.512258 |   0.519436 |
| k-d_tree_pandas      |     0.474627 |       0.400239 |   0.552132 |
| Bori_Aron_solution-1 |     0.452362 |       0.548696 |   0.556391 |
| k-d_tree_sklearn     |     3.63651  |       1.33168  |   1.09511  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483618 |       0.43966  |   0.44349  |
| k-d_tree_polars      |     0.489773 |       0.446044 |   0.452169 |
| barab-szabi-1        |     0.471858 |       0.44606  |   0.466666 |
| Bori_Aron_solution-1 |     0.500157 |       0.573901 |   0.558923 |
| k-d_tree_pandas      |     0.486591 |       0.405653 |   0.606129 |
| k-d_tree_sklearn     |     0.482054 |       1.0412   |   1.10356  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479798 |       0.456416 |   0.447482 |
| barab-szabi-1        |     0.486104 |       0.455366 |   0.475883 |
| k-d_tree_polars      |     0.486993 |       0.466342 |   0.488466 |
| Bori_Aron_solution-1 |     0.473874 |       0.604281 |   0.563564 |
| k-d_tree_pandas      |     0.467802 |       0.415089 |   0.595849 |
| k-d_tree_sklearn     |     0.476337 |       1.05479  |   1.11038  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486533 |       0.524997 |   0.47139  |
| k-d_tree_polars      |     0.476128 |       0.577332 |   0.559808 |
| barab-szabi-1        |     0.479199 |       0.594013 |   0.569291 |
| Bori_Aron_solution-1 |     0.474645 |       0.787703 |   0.579751 |
| k-d_tree_pandas      |     0.47716  |       0.509006 |   0.745589 |
| k-d_tree_sklearn     |     0.480586 |       1.29698  |   1.16546  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475472 |       0.751639 |   0.506987 |
| Bori_Aron_solution-1 |     0.489694 |       1.44759  |   0.600316 |
| k-d_tree_polars      |     0.476511 |       0.940797 |   0.91204  |
| barab-szabi-1        |     0.477564 |       0.928524 |   0.973049 |
| k-d_tree_pandas      |     0.480185 |       0.808813 |   1.19181  |
| k-d_tree_sklearn     |     0.472964 |       2.15967  |   1.26605  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485726 |        5.73387 |   0.804018 |
| Bori_Aron_solution-1 |     0.460744 |       11.1222  |   0.852763 |
| k-d_tree_sklearn     |     0.474763 |       17.4187  |   1.54379  |
| barab-szabi-1        |     0.477078 |        5.40204 |   7.04893  |
| k-d_tree_pandas      |     0.477678 |        4.42652 |   7.05189  |
| k-d_tree_polars      |     0.472105 |        5.31923 |   7.0744   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.945853 |        77.6308 |    2.93761 |
| k-d_tree_sklearn     |     0.663844 |       253.229  |    4.01164 |
| Bori_Aron_solution-1 |     0.476505 |       169.445  |   16.2243  |