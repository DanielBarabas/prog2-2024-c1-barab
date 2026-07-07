# 2026-07-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.37299  |       1e-06    |   0.419697 |
| barab-szabi-2        |     7.8394   |       0.615019 |   0.438411 |
| barab-szabi-1        |     0.460453 |       0.415986 |   0.445631 |
| k-d_tree_polars      |     0.46004  |       0.420912 |   0.447082 |
| Bori_Aron_solution-1 |     0.454494 |       0.542375 |   0.542176 |
| k-d_tree_pandas      |     0.466056 |       0.38092  |   0.544385 |
| k-d_tree_sklearn     |     2.88698  |       1.16871  |   1.05649  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.466096 |       0.411516 |   0.451428 |
| barab-szabi-1        |     0.471269 |       0.424532 |   0.451923 |
| barab-szabi-2        |     0.468936 |       0.435704 |   0.519699 |
| Bori_Aron_solution-1 |     0.45871  |       0.552273 |   0.537505 |
| k-d_tree_pandas      |     0.464815 |       0.380189 |   0.551694 |
| k-d_tree_sklearn     |     0.470855 |       1.00497  |   1.05781  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468565 |       0.44928  |   0.450883 |
| k-d_tree_polars      |     0.475568 |       0.445741 |   0.468549 |
| barab-szabi-1        |     0.468161 |       0.4528   |   0.486823 |
| Bori_Aron_solution-1 |     0.463188 |       0.588031 |   0.541134 |
| k-d_tree_pandas      |     0.464392 |       0.404431 |   0.592558 |
| k-d_tree_sklearn     |     0.501677 |       1.02478  |   1.0828   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467904 |       0.515022 |   0.474006 |
| Bori_Aron_solution-1 |     0.45907  |       0.767362 |   0.553083 |
| k-d_tree_polars      |     0.468814 |       0.568654 |   0.564811 |
| barab-szabi-1        |     0.468556 |       0.568084 |   0.568168 |
| k-d_tree_pandas      |     0.468088 |       0.491163 |   0.723887 |
| k-d_tree_sklearn     |     0.466751 |       1.27241  |   1.1328   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465086 |       0.722715 |   0.509924 |
| Bori_Aron_solution-1 |     0.459481 |       1.41636  |   0.580538 |
| k-d_tree_polars      |     0.468724 |       0.943163 |   0.905566 |
| barab-szabi-1        |     0.467707 |       0.926623 |   0.942451 |
| k-d_tree_pandas      |     0.466312 |       0.795281 |   1.16277  |
| k-d_tree_sklearn     |     0.473001 |       2.08254  |   1.2025   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463142 |        4.96533 |   0.732494 |
| Bori_Aron_solution-1 |     0.455606 |       10.705   |   0.797792 |
| k-d_tree_sklearn     |     0.471808 |       16.2154  |   1.27797  |
| k-d_tree_polars      |     0.467501 |        5.35879 |   6.52051  |
| barab-szabi-1        |     0.465263 |        5.35328 |   6.53268  |
| k-d_tree_pandas      |     0.469567 |        4.31712 |   6.89501  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468814 |        69.1484 |    2.66819 |
| k-d_tree_sklearn     |     0.69248  |       228.292  |    4.16702 |
| Bori_Aron_solution-1 |     0.466999 |       147.118  |   34.0901  |