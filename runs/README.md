# 2026-02-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488621 |       0.496298 |   0.433389 |
| barab-szabi-1        |     0.499008 |       0.43385  |   0.440031 |
| k-d_tree_polars      |     0.499936 |       0.409243 |   0.447807 |
| solution-1           |     7.82958  |       1e-06    |   0.514725 |
| Bori_Aron_solution-1 |     0.535385 |       0.558269 |   0.581266 |
| k-d_tree_pandas      |     8.33854  |       0.477342 |   0.695373 |
| k-d_tree_sklearn     |     2.93662  |       1.17138  |   1.10488  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.500088 |       0.416668 |   0.440501 |
| barab-szabi-1        |     0.499215 |       0.423528 |   0.441934 |
| barab-szabi-2        |     0.526752 |       0.458644 |   0.452169 |
| Bori_Aron_solution-1 |     0.505647 |       0.580519 |   0.569268 |
| k-d_tree_pandas      |     0.518805 |       0.424583 |   0.614511 |
| k-d_tree_sklearn     |     0.509046 |       1.011    |   1.10093  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522161 |       0.459457 |   0.465693 |
| barab-szabi-1        |     0.4909   |       0.434261 |   0.46589  |
| k-d_tree_polars      |     0.489608 |       0.452365 |   0.466732 |
| Bori_Aron_solution-1 |     0.493275 |       0.602642 |   0.574871 |
| k-d_tree_pandas      |     0.507531 |       0.427694 |   0.629493 |
| k-d_tree_sklearn     |     0.528811 |       1.02376  |   1.10498  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504949 |       0.512703 |   0.488403 |
| Bori_Aron_solution-1 |     0.491231 |       0.792986 |   0.559407 |
| k-d_tree_polars      |     0.488372 |       0.579085 |   0.57744  |
| barab-szabi-1        |     0.497692 |       0.563977 |   0.577788 |
| k-d_tree_pandas      |     0.495964 |       0.506603 |   0.760918 |
| k-d_tree_sklearn     |     0.494843 |       1.305    |   1.17386  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488302 |       0.740138 |   0.526295 |
| Bori_Aron_solution-1 |     0.479491 |       1.50351  |   0.604716 |
| k-d_tree_polars      |     0.490585 |       0.94599  |   0.918537 |
| barab-szabi-1        |     0.489217 |       0.938955 |   0.952254 |
| k-d_tree_pandas      |     0.491071 |       0.822737 |   1.19292  |
| k-d_tree_sklearn     |     0.507322 |       2.18239  |   1.2375   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507945 |        5.43426 |   0.753824 |
| Bori_Aron_solution-1 |     0.497197 |       11.5725  |   0.85123  |
| k-d_tree_sklearn     |     0.50372  |       17.456   |   1.34934  |
| k-d_tree_polars      |     0.49883  |        5.65168 |   6.99153  |
| barab-szabi-1        |     0.499986 |        5.60933 |   6.99988  |
| k-d_tree_pandas      |     0.507437 |        4.49923 |   7.30842  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505322 |        75.5335 |    2.78694 |
| k-d_tree_sklearn     |     0.519103 |       248.267  |    4.26175 |
| Bori_Aron_solution-1 |     0.68204  |       150.341  |   18.2972  |