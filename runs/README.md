# 2024-06-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.58885  |       0.349283 |   0.337381 |
| k-d_tree_polars      |     0.801226 |       0.399035 |   0.344463 |
| barab-szabi-1        |     0.794314 |       0.401318 |   0.369259 |
| solution-1           |     8.17662  |       1e-06    |   0.399551 |
| Bori_Aron_solution-1 |     4.87537  |       0.405219 |   0.401444 |
| k-d_tree_pandas      |     0.792698 |       0.380163 |   0.473724 |
| k-d_tree_sklearn     |     3.56121  |       0.922956 |   0.670503 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.797606 |       0.410486 |   0.349251 |
| barab-szabi-1        |     0.799964 |       0.41728  |   0.350599 |
| barab-szabi-2        |     0.800041 |       0.349853 |   0.352075 |
| Bori_Aron_solution-1 |     0.786851 |       0.479985 |   0.470882 |
| k-d_tree_pandas      |     0.790895 |       0.385786 |   0.520117 |
| k-d_tree_sklearn     |     0.81034  |       0.849384 |   0.682114 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807794 |       0.375867 |   0.352275 |
| k-d_tree_polars      |     0.799926 |       0.4302   |   0.377369 |
| barab-szabi-1        |     0.796479 |       0.431358 |   0.378214 |
| Bori_Aron_solution-1 |     0.781296 |       0.523242 |   0.482009 |
| k-d_tree_pandas      |     0.804122 |       0.403041 |   0.523312 |
| k-d_tree_sklearn     |     0.800492 |       0.909396 |   0.721514 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.799325 |       0.428586 |   0.389775 |
| k-d_tree_polars      |     0.805585 |       0.545471 |   0.477552 |
| barab-szabi-1        |     0.810964 |       0.546993 |   0.488606 |
| Bori_Aron_solution-1 |     0.787639 |       0.710554 |   0.498326 |
| k-d_tree_pandas      |     0.809612 |       0.487026 |   0.675917 |
| k-d_tree_sklearn     |     0.803196 |       1.15341  |   0.789106 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.786479 |       0.675857 |   0.424477 |
| Bori_Aron_solution-1 |     0.789229 |       1.34971  |   0.515666 |
| k-d_tree_polars      |     0.794749 |       0.870819 |   0.826373 |
| barab-szabi-1        |     0.791406 |       0.868979 |   0.859054 |
| k-d_tree_sklearn     |     0.80263  |       1.94925  |   0.869007 |
| k-d_tree_pandas      |     0.788819 |       0.75679  |   1.09184  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.802408 |        5.27355 |   0.722735 |
| Bori_Aron_solution-1 |     0.783333 |       10.7048  |   0.771028 |
| k-d_tree_sklearn     |     0.801574 |       15.9199  |   1.04411  |
| k-d_tree_polars      |     0.794863 |        4.96648 |   6.48435  |
| barab-szabi-1        |     0.788795 |        4.99532 |   6.52163  |
| k-d_tree_pandas      |     0.79653  |        4.00139 |   6.85086  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.09309  |        70.3567 |    3.81956 |
| k-d_tree_sklearn     |     0.939725 |       222.725  |    4.56648 |
| Bori_Aron_solution-1 |     0.797725 |       148.469  |   17.1683  |