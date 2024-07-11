# 2024-07-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65567  |       1e-06    |   0.365375 |
| barab-szabi-2        |     0.563869 |       0.408546 |   0.393122 |
| barab-szabi-1        |     0.56986  |       0.407584 |   0.394254 |
| k-d_tree_polars      |     0.560078 |       0.406813 |   0.398854 |
| Bori_Aron_solution-1 |     0.55358  |       0.530335 |   0.534971 |
| k-d_tree_pandas      |     0.564919 |       0.402623 |   0.541818 |
| k-d_tree_sklearn     |    10.4828   |       1.0554   |   0.727132 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.567149 |       0.423301 |   0.399354 |
| barab-szabi-2        |     0.598038 |       0.396374 |   0.399487 |
| k-d_tree_polars      |     0.579377 |       0.414746 |   0.405339 |
| Bori_Aron_solution-1 |     0.562076 |       0.541866 |   0.525595 |
| k-d_tree_pandas      |     0.568353 |       0.394852 |   0.545772 |
| k-d_tree_sklearn     |     0.562619 |       0.916915 |   0.74473  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573326 |       0.40776  |   0.398772 |
| k-d_tree_polars      |     0.564729 |       0.430036 |   0.418337 |
| barab-szabi-1        |     0.557947 |       0.426598 |   0.420884 |
| Bori_Aron_solution-1 |     0.550183 |       0.565493 |   0.537694 |
| k-d_tree_pandas      |     0.572786 |       0.416476 |   0.577388 |
| k-d_tree_sklearn     |     0.576137 |       0.983413 |   0.761784 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566492 |       0.469115 |   0.439443 |
| k-d_tree_polars      |     0.559455 |       0.544423 |   0.522782 |
| barab-szabi-1        |     0.566462 |       0.550294 |   0.533404 |
| Bori_Aron_solution-1 |     0.558753 |       0.759021 |   0.570852 |
| k-d_tree_pandas      |     0.563911 |       0.485038 |   0.707993 |
| k-d_tree_sklearn     |     0.563781 |       1.17864  |   0.789898 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560012 |       0.727467 |   0.485396 |
| Bori_Aron_solution-1 |     0.551086 |       1.42365  |   0.565819 |
| k-d_tree_polars      |     0.579244 |       0.875929 |   0.89351  |
| k-d_tree_sklearn     |     0.561372 |       2.02447  |   0.907836 |
| barab-szabi-1        |     0.563192 |       0.86894  |   0.948735 |
| k-d_tree_pandas      |     0.571036 |       0.758153 |   1.16049  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56273  |        5.7448  |   0.831918 |
| Bori_Aron_solution-1 |     0.560445 |       10.9469  |   0.873266 |
| k-d_tree_sklearn     |     0.563769 |       16.5758  |   1.06795  |
| k-d_tree_polars      |     0.571534 |        4.82178 |   6.96337  |
| barab-szabi-1        |     0.562564 |        4.8688  |   7.03277  |
| k-d_tree_pandas      |     0.562763 |        3.90516 |   7.4315   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740762 |        79.0827 |    4.1429  |
| k-d_tree_sklearn     |     0.564555 |       244.693  |    4.42327 |
| Bori_Aron_solution-1 |     0.563678 |       151.714  |   17.4918  |