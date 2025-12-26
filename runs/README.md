# 2025-12-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473087 |       0.469409 |   0.407158 |
| barab-szabi-1        |     0.471274 |       0.377366 |   0.407389 |
| k-d_tree_polars      |     0.485498 |       0.378269 |   0.407858 |
| solution-1           |     8.08828  |       1e-06    |   0.412114 |
| Bori_Aron_solution-1 |     0.473433 |       0.522472 |   0.53498  |
| k-d_tree_pandas      |     7.8068   |       0.430919 |   0.654628 |
| k-d_tree_sklearn     |     2.75502  |       1.02501  |   0.959797 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476456 |       0.407225 |   0.401391 |
| k-d_tree_polars      |     0.473696 |       0.378949 |   0.413996 |
| barab-szabi-1        |     0.473395 |       0.38264  |   0.460396 |
| k-d_tree_pandas      |     0.472566 |       0.362632 |   0.513513 |
| Bori_Aron_solution-1 |     0.46705  |       0.523914 |   0.52376  |
| k-d_tree_sklearn     |     0.477637 |       0.892382 |   0.980636 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490083 |       0.468268 |   0.416365 |
| k-d_tree_polars      |     0.48685  |       0.410377 |   0.435209 |
| barab-szabi-1        |     0.479668 |       0.414045 |   0.437753 |
| Bori_Aron_solution-1 |     0.476095 |       0.565544 |   0.544994 |
| k-d_tree_pandas      |     0.491252 |       0.397377 |   0.560102 |
| k-d_tree_sklearn     |     0.48682  |       0.944211 |   1.02246  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480022 |       0.482499 |   0.464802 |
| Bori_Aron_solution-1 |     0.478466 |       0.713924 |   0.52404  |
| k-d_tree_polars      |     0.488113 |       0.535526 |   0.524385 |
| barab-szabi-1        |     0.475955 |       0.53662  |   0.532909 |
| k-d_tree_pandas      |     0.490886 |       0.467042 |   0.680237 |
| k-d_tree_sklearn     |     0.484786 |       1.17593  |   1.0428   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503702 |       0.705215 |   0.517308 |
| Bori_Aron_solution-1 |     0.467689 |       1.34805  |   0.564675 |
| k-d_tree_polars      |     0.479501 |       0.844563 |   0.845434 |
| barab-szabi-1        |     0.477772 |       0.86903  |   0.869903 |
| k-d_tree_pandas      |     0.477081 |       0.71567  |   1.06576  |
| k-d_tree_sklearn     |     0.486903 |       1.91733  |   1.10527  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480494 |        5.04387 |   0.691505 |
| Bori_Aron_solution-1 |     0.475557 |       10.092   |   0.91469  |
| k-d_tree_sklearn     |     0.482715 |       14.2429  |   1.25687  |
| barab-szabi-1        |     0.475638 |        4.89705 |   6.18401  |
| k-d_tree_polars      |     0.471739 |        4.86421 |   6.29562  |
| k-d_tree_pandas      |     0.477293 |        3.82156 |   6.56499  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476735 |        83.1231 |    2.69364 |
| k-d_tree_sklearn     |     0.490198 |       172.777  |    4.24037 |
| Bori_Aron_solution-1 |     0.580847 |       137.217  |   15.9673  |