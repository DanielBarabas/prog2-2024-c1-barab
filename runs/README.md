# 2024-07-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.77471  |       1e-06    |   0.361791 |
| k-d_tree_polars      |     0.566647 |       0.420974 |   0.39019  |
| barab-szabi-2        |     0.567235 |       0.390355 |   0.391084 |
| barab-szabi-1        |     0.565049 |       0.400681 |   0.392419 |
| Bori_Aron_solution-1 |     0.562575 |       0.52316  |   0.5251   |
| k-d_tree_pandas      |     0.559908 |       0.38204  |   0.525295 |
| k-d_tree_sklearn     |    10.4946   |       0.972445 |   0.697975 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556039 |       0.416137 |   0.383752 |
| barab-szabi-1        |     0.562092 |       0.40729  |   0.392005 |
| k-d_tree_polars      |     0.559594 |       0.454556 |   0.408581 |
| Bori_Aron_solution-1 |     0.548946 |       0.533514 |   0.529711 |
| k-d_tree_pandas      |     0.56683  |       0.391957 |   0.536957 |
| k-d_tree_sklearn     |     0.56145  |       0.890261 |   0.703288 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563889 |       0.434899 |   0.399873 |
| barab-szabi-1        |     0.558419 |       0.429946 |   0.42284  |
| k-d_tree_polars      |     0.593149 |       0.448845 |   0.424577 |
| Bori_Aron_solution-1 |     0.558466 |       0.570707 |   0.529637 |
| k-d_tree_pandas      |     0.568372 |       0.424479 |   0.579997 |
| k-d_tree_sklearn     |     0.579847 |       0.933016 |   0.73572  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564031 |       0.464987 |   0.43796  |
| k-d_tree_polars      |     0.566294 |       0.539768 |   0.521743 |
| barab-szabi-1        |     0.569434 |       0.534594 |   0.533469 |
| Bori_Aron_solution-1 |     0.552859 |       0.75224  |   0.544492 |
| k-d_tree_pandas      |     0.560758 |       0.486723 |   0.721102 |
| k-d_tree_sklearn     |     0.560669 |       1.17542  |   0.808272 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561936 |       0.733467 |   0.4767   |
| Bori_Aron_solution-1 |     0.550678 |       1.38682  |   0.570904 |
| k-d_tree_polars      |     0.556723 |       0.841328 |   0.868743 |
| k-d_tree_sklearn     |     0.560882 |       1.96927  |   0.898424 |
| barab-szabi-1        |     0.55501  |       0.859263 |   0.922467 |
| k-d_tree_pandas      |     0.562671 |       0.751453 |   1.20873  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559369 |        5.45764 |   0.787001 |
| Bori_Aron_solution-1 |     0.549003 |       10.8915  |   0.89257  |
| k-d_tree_sklearn     |     0.565663 |       16.3185  |   1.05218  |
| k-d_tree_polars      |     0.56386  |        4.88531 |   6.77154  |
| barab-szabi-1        |     0.567678 |        4.90636 |   6.77392  |
| k-d_tree_pandas      |     0.565049 |        3.91889 |   7.05637  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.852803 |        72.9993 |    4.10864 |
| k-d_tree_sklearn     |     0.564353 |       228.438  |    4.38566 |
| Bori_Aron_solution-1 |     0.572243 |       141.955  |   18.6384  |