# 2025-12-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519753 |       0.524534 |   0.426161 |
| barab-szabi-1        |     0.528617 |       0.405752 |   0.433156 |
| k-d_tree_polars      |     0.538081 |       0.405015 |   0.433521 |
| solution-1           |     7.55433  |       4e-06    |   0.483281 |
| Bori_Aron_solution-1 |     0.523757 |       0.548342 |   0.551533 |
| k-d_tree_pandas      |     8.19485  |       0.422964 |   0.674935 |
| k-d_tree_sklearn     |     3.0188   |       1.20072  |   1.0843   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532267 |       0.435451 |   0.43382  |
| barab-szabi-1        |     0.53534  |       0.414349 |   0.439095 |
| k-d_tree_polars      |     0.535934 |       0.413846 |   0.441272 |
| Bori_Aron_solution-1 |     0.520413 |       0.562093 |   0.556784 |
| k-d_tree_pandas      |     0.56092  |       0.409433 |   0.556993 |
| k-d_tree_sklearn     |     0.537621 |       0.979181 |   1.07284  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543813 |       0.447063 |   0.445503 |
| barab-szabi-1        |     0.53382  |       0.447621 |   0.468858 |
| k-d_tree_polars      |     0.533392 |       0.453705 |   0.469753 |
| Bori_Aron_solution-1 |     0.532176 |       0.60314  |   0.568557 |
| k-d_tree_pandas      |     0.533654 |       0.416238 |   0.625367 |
| k-d_tree_sklearn     |     0.555431 |       1.02715  |   1.09889  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531314 |       0.512283 |   0.477389 |
| k-d_tree_polars      |     0.533329 |       0.557362 |   0.554521 |
| Bori_Aron_solution-1 |     0.528954 |       0.78265  |   0.562259 |
| barab-szabi-1        |     0.532023 |       0.560144 |   0.575412 |
| k-d_tree_pandas      |     0.535386 |       0.513097 |   0.745815 |
| k-d_tree_sklearn     |     0.544278 |       1.24682  |   1.1562   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5466   |       0.753756 |   0.501886 |
| Bori_Aron_solution-1 |     0.526913 |       1.46978  |   0.589503 |
| k-d_tree_polars      |     0.530986 |       0.943798 |   0.915888 |
| barab-szabi-1        |     0.528075 |       0.93314  |   0.948093 |
| k-d_tree_pandas      |     0.546419 |       0.819077 |   1.18328  |
| k-d_tree_sklearn     |     0.534545 |       2.13901  |   1.22058  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526761 |        5.22801 |   0.743006 |
| Bori_Aron_solution-1 |     0.525931 |       11.1679  |   0.840448 |
| k-d_tree_sklearn     |     0.540976 |       16.7544  |   1.32225  |
| k-d_tree_polars      |     0.528302 |        5.43577 |   6.56414  |
| barab-szabi-1        |     0.532009 |        5.4707  |   6.64649  |
| k-d_tree_pandas      |     0.533409 |        4.54979 |   6.9878   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534352 |        81.1134 |    2.72841 |
| k-d_tree_sklearn     |     0.56718  |       236.643  |    4.18575 |
| Bori_Aron_solution-1 |     0.659614 |       153.424  |   16.5517  |