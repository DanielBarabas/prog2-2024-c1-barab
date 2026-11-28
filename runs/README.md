# 2026-11-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.9341   |       2e-06    |   0.318717 |
| k-d_tree_polars      |     0.375692 |       0.416694 |   0.377224 |
| barab-szabi-2        |     0.371766 |       0.392174 |   0.381938 |
| barab-szabi-1        |     0.384405 |       0.368942 |   0.405033 |
| Bori_Aron_solution-1 |     4.12047  |       0.453632 |   0.409492 |
| k-d_tree_pandas      |     0.399879 |       0.342811 |   0.485763 |
| k-d_tree_sklearn     |     7.90865  |       0.897373 |   0.924488 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.385682 |       0.377162 |   0.363526 |
| barab-szabi-1        |     0.37841  |       0.373734 |   0.3799   |
| k-d_tree_polars      |     0.371929 |       0.379174 |   0.380542 |
| Bori_Aron_solution-1 |     0.37673  |       0.479015 |   0.481476 |
| k-d_tree_pandas      |     0.37172  |       0.358024 |   0.534582 |
| k-d_tree_sklearn     |     0.379768 |       0.863948 |   0.951754 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.370376 |       0.379159 |   0.359661 |
| k-d_tree_polars      |     0.409176 |       0.401138 |   0.394735 |
| barab-szabi-1        |     0.382366 |       0.424005 |   0.39501  |
| Bori_Aron_solution-1 |     0.372233 |       0.510939 |   0.486715 |
| k-d_tree_pandas      |     0.370308 |       0.339565 |   0.512171 |
| k-d_tree_sklearn     |     0.373701 |       0.915591 |   0.936678 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.408377 |       0.472089 |   0.41367  |
| k-d_tree_polars      |     0.37403  |       0.493891 |   0.470491 |
| barab-szabi-1        |     0.370547 |       0.495235 |   0.484979 |
| Bori_Aron_solution-1 |     0.3699   |       0.674107 |   0.49128  |
| k-d_tree_pandas      |     0.387265 |       0.423344 |   0.59947  |
| k-d_tree_sklearn     |     0.387668 |       1.12759  |   1.13227  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.375062 |       1.23383  |   0.537136 |
| barab-szabi-2        |     0.372606 |       0.67545  |   0.541286 |
| k-d_tree_polars      |     0.385607 |       0.885194 |   0.839152 |
| barab-szabi-1        |     0.387835 |       0.837808 |   0.862403 |
| k-d_tree_sklearn     |     0.37942  |       1.94653  |   1.02375  |
| k-d_tree_pandas      |     0.379853 |       0.64052  |   1.03347  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.382987 |        5.80908 |   0.787785 |
| Bori_Aron_solution-1 |     0.374948 |        9.88078 |   0.94694  |
| k-d_tree_sklearn     |     0.389233 |       16.3738  |   1.16806  |
| k-d_tree_polars      |     0.380358 |        4.47196 |   6.63465  |
| barab-szabi-1        |     0.375869 |        4.6653  |   6.87543  |
| k-d_tree_pandas      |     0.412459 |        3.20817 |   6.99998  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     1.6529   |       236.331  |    4.26098 |
| barab-szabi-2        |     0.439396 |        76.5512 |    4.43855 |
| Bori_Aron_solution-1 |     0.392878 |       155.816  |   28.6364  |