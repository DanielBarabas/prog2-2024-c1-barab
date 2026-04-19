# 2026-04-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.411479 |       0.401577 |   0.403664 |
| k-d_tree_polars      |     0.411701 |       0.368967 |   0.408088 |
| barab-szabi-1        |     0.412823 |       0.420366 |   0.413779 |
| solution-1           |     7.38318  |       1e-06    |   0.483293 |
| Bori_Aron_solution-1 |     0.405896 |       0.498181 |   0.501099 |
| k-d_tree_pandas      |     0.412087 |       0.361378 |   0.505523 |
| k-d_tree_sklearn     |    10.5754   |       1.21331  |   0.977291 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.421472 |       0.4091   |   0.403914 |
| barab-szabi-1        |     0.409964 |       0.377008 |   0.407357 |
| k-d_tree_polars      |     0.410477 |       0.384635 |   0.412282 |
| Bori_Aron_solution-1 |     0.405527 |       0.507657 |   0.500113 |
| k-d_tree_pandas      |     0.425652 |       0.368161 |   0.517673 |
| k-d_tree_sklearn     |     0.416046 |       0.891911 |   0.95849  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.416883 |       0.426557 |   0.417986 |
| k-d_tree_polars      |     0.41566  |       0.405156 |   0.431314 |
| barab-szabi-1        |     0.418666 |       0.403689 |   0.445394 |
| Bori_Aron_solution-1 |     0.406762 |       0.551162 |   0.506425 |
| k-d_tree_pandas      |     0.414795 |       0.378803 |   0.558827 |
| k-d_tree_sklearn     |     0.410085 |       0.928595 |   0.995991 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422217 |       0.466948 |   0.443029 |
| k-d_tree_polars      |     0.424133 |       0.526566 |   0.51487  |
| Bori_Aron_solution-1 |     0.410685 |       0.716757 |   0.527534 |
| barab-szabi-1        |     0.424191 |       0.537115 |   0.532483 |
| k-d_tree_pandas      |     0.415006 |       0.457689 |   0.669537 |
| k-d_tree_sklearn     |     0.423442 |       1.14354  |   1.02956  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.414777 |       0.714002 |   0.517766 |
| Bori_Aron_solution-1 |     0.415041 |       1.30591  |   0.559442 |
| k-d_tree_polars      |     0.414711 |       0.871497 |   0.840492 |
| barab-szabi-1        |     0.409567 |       0.844829 |   0.863842 |
| k-d_tree_pandas      |     0.42236  |       0.722432 |   1.05308  |
| k-d_tree_sklearn     |     0.476293 |       1.92932  |   1.11302  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432812 |        5.11263 |   0.781982 |
| Bori_Aron_solution-1 |     0.413935 |       10.1889  |   0.917547 |
| k-d_tree_sklearn     |     0.435523 |       14.0273  |   1.21616  |
| barab-szabi-1        |     0.422152 |        4.9535  |   6.22111  |
| k-d_tree_polars      |     0.436263 |        4.89194 |   6.28367  |
| k-d_tree_pandas      |     0.42856  |        3.89661 |   6.51357  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.644672 |        63.6149 |    2.53391 |
| k-d_tree_sklearn     |     0.422437 |       170.546  |    3.86601 |
| Bori_Aron_solution-1 |     0.410882 |       138.828  |   16.0069  |