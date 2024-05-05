# 2024-05-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.705696 |       0.340754 |   0.332293 |
| k-d_tree_polars      |     0.697169 |       0.399269 |   0.340662 |
| barab-szabi-1        |     8.17606  |       0.529353 |   0.343675 |
| solution-1           |     7.91813  |       1e-06    |   0.365611 |
| Bori_Aron_solution-1 |     0.690802 |       0.466836 |   0.467166 |
| k-d_tree_pandas      |     0.720204 |       0.379219 |   0.469739 |
| k-d_tree_sklearn     |     3.31014  |       0.887375 |   0.652468 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721269 |       0.342607 |   0.331757 |
| k-d_tree_polars      |     0.727525 |       0.404149 |   0.349036 |
| barab-szabi-1        |     0.724448 |       0.401689 |   0.349308 |
| Bori_Aron_solution-1 |     0.742053 |       0.478264 |   0.47312  |
| k-d_tree_pandas      |     0.726035 |       0.385188 |   0.479738 |
| k-d_tree_sklearn     |     0.736262 |       0.88361  |   0.652173 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723959 |       0.364564 |   0.352049 |
| k-d_tree_polars      |     0.729098 |       0.424102 |   0.370341 |
| barab-szabi-1        |     0.728637 |       0.42642  |   0.374675 |
| Bori_Aron_solution-1 |     0.718241 |       0.513976 |   0.469145 |
| k-d_tree_pandas      |     0.757243 |       0.398058 |   0.523465 |
| k-d_tree_sklearn     |     0.736505 |       0.881616 |   0.685109 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725147 |       0.429014 |   0.383972 |
| k-d_tree_polars      |     0.733472 |       0.536536 |   0.472929 |
| Bori_Aron_solution-1 |     0.711185 |       0.702407 |   0.479589 |
| barab-szabi-1        |     0.724625 |       0.53408  |   0.485796 |
| k-d_tree_pandas      |     0.722482 |       0.481025 |   0.659681 |
| k-d_tree_sklearn     |     0.734334 |       1.10424  |   0.749431 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727515 |       0.675748 |   0.421911 |
| Bori_Aron_solution-1 |     0.712655 |       1.33678  |   0.510581 |
| k-d_tree_polars      |     0.726834 |       0.854585 |   0.823107 |
| k-d_tree_sklearn     |     0.73727  |       1.89678  |   0.854358 |
| barab-szabi-1        |     0.727227 |       0.854761 |   0.86172  |
| k-d_tree_pandas      |     0.730569 |       0.742543 |   1.08127  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734073 |        5.41671 |   0.74107  |
| Bori_Aron_solution-1 |     0.719122 |       10.6706  |   0.775033 |
| k-d_tree_sklearn     |     0.737692 |       16.2991  |   1.05814  |
| barab-szabi-1        |     0.733785 |        4.86327 |   6.62945  |
| k-d_tree_polars      |     0.731359 |        4.87776 |   6.68538  |
| k-d_tree_pandas      |     0.72647  |        3.88594 |   6.92662  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02235  |        71.3754 |    4.00154 |
| k-d_tree_sklearn     |     0.833214 |       224.723  |    4.73228 |
| Bori_Aron_solution-1 |     0.715812 |       146.376  |   16.2814  |