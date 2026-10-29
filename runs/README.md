# 2026-10-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     4.86199  |       1e-06    |   0.235574 |
| k-d_tree_polars      |     0.277398 |       0.283911 |   0.280176 |
| barab-szabi-2        |     0.277028 |       0.282305 |   0.285228 |
| barab-szabi-1        |     6.15878  |       0.289688 |   0.325164 |
| Bori_Aron_solution-1 |     0.279119 |       0.342412 |   0.343716 |
| k-d_tree_pandas      |     0.293723 |       0.261851 |   0.369876 |
| k-d_tree_sklearn     |     1.92766  |       0.663582 |   0.673099 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.288702 |       0.28671  |   0.28397  |
| barab-szabi-1        |     0.283343 |       0.298641 |   0.307838 |
| k-d_tree_polars      |     0.299378 |       0.336207 |   0.321663 |
| k-d_tree_pandas      |     0.291414 |       0.260257 |   0.367058 |
| Bori_Aron_solution-1 |     0.285039 |       0.376789 |   0.390137 |
| k-d_tree_sklearn     |     0.284871 |       0.708929 |   0.696993 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.291224 |       0.30717  |   0.297733 |
| k-d_tree_polars      |     0.281027 |       0.304382 |   0.308438 |
| barab-szabi-1        |     0.3274   |       0.300415 |   0.349928 |
| Bori_Aron_solution-1 |     0.285523 |       0.396282 |   0.362244 |
| k-d_tree_pandas      |     0.284816 |       0.276805 |   0.438022 |
| k-d_tree_sklearn     |     0.290153 |       0.735043 |   0.765163 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.311655 |       0.368116 |   0.32588  |
| k-d_tree_polars      |     0.293856 |       0.375744 |   0.373062 |
| Bori_Aron_solution-1 |     0.291233 |       0.520695 |   0.377206 |
| barab-szabi-1        |     0.283281 |       0.362442 |   0.383455 |
| k-d_tree_pandas      |     0.288478 |       0.335433 |   0.489758 |
| k-d_tree_sklearn     |     0.329285 |       0.889765 |   0.772877 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.29673  |       0.553391 |   0.388576 |
| Bori_Aron_solution-1 |     0.444116 |       0.960909 |   0.410275 |
| k-d_tree_polars      |     0.284266 |       0.552993 |   0.628327 |
| barab-szabi-1        |     0.30922  |       0.624261 |   0.6548   |
| k-d_tree_pandas      |     0.297675 |       0.483558 |   0.746719 |
| k-d_tree_sklearn     |     0.303982 |       1.53643  |   1.01063  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.280098 |        3.98315 |   0.650657 |
| Bori_Aron_solution-1 |     0.297112 |        7.31492 |   0.798911 |
| k-d_tree_sklearn     |     0.310856 |       12.5681  |   0.915443 |
| barab-szabi-1        |     0.291711 |        3.66194 |   4.763    |
| k-d_tree_pandas      |     0.276707 |        2.28264 |   4.90296  |
| k-d_tree_polars      |     0.308012 |        3.51908 |   5.09384  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.307743 |       165.168  |    2.39818 |
| barab-szabi-2        |     0.296729 |        61.7432 |    3.16568 |
| Bori_Aron_solution-1 |     0.293121 |       124.557  |   24.3032  |