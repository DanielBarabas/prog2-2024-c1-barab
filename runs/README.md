# 2024-10-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614661 |       0.383916 |   0.384286 |
| barab-szabi-1        |     0.611907 |       0.40901  |   0.387866 |
| Bori_Aron_solution-1 |     4.85653  |       0.715782 |   0.455435 |
| k-d_tree_polars      |     0.611196 |       0.470294 |   0.506723 |
| k-d_tree_pandas      |     4.37503  |       0.427949 |   0.527874 |
| solution-1           |     8.04068  |       1e-06    |   0.708049 |
| k-d_tree_sklearn     |     3.01275  |       1.22613  |   0.975892 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613832 |       0.39432  |   0.387302 |
| barab-szabi-1        |     0.645117 |       0.404175 |   0.393295 |
| k-d_tree_polars      |     0.612372 |       0.401785 |   0.421346 |
| k-d_tree_pandas      |     0.611968 |       0.384337 |   0.531476 |
| Bori_Aron_solution-1 |     0.613138 |       0.530248 |   0.594568 |
| k-d_tree_sklearn     |     0.624585 |       0.893774 |   0.958852 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614444 |       0.407818 |   0.398231 |
| k-d_tree_polars      |     0.617378 |       0.432328 |   0.419791 |
| barab-szabi-1        |     0.624042 |       0.426635 |   0.425793 |
| Bori_Aron_solution-1 |     0.601952 |       0.563351 |   0.529214 |
| k-d_tree_pandas      |     0.616348 |       0.402641 |   0.572725 |
| k-d_tree_sklearn     |     0.620851 |       0.940627 |   0.977247 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639309 |       0.528293 |   0.467415 |
| k-d_tree_polars      |     0.60904  |       0.529841 |   0.524258 |
| Bori_Aron_solution-1 |     0.611155 |       0.76047  |   0.529667 |
| barab-szabi-1        |     0.608202 |       0.559819 |   0.534954 |
| k-d_tree_pandas      |     0.619144 |       0.488211 |   0.710779 |
| k-d_tree_sklearn     |     0.635866 |       1.22382  |   1.09907  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631583 |       0.733418 |   0.491879 |
| Bori_Aron_solution-1 |     0.716932 |       1.41405  |   0.600661 |
| k-d_tree_polars      |     0.641758 |       0.86656  |   0.902256 |
| barab-szabi-1        |     0.64017  |       0.868568 |   0.947203 |
| k-d_tree_pandas      |     0.631493 |       0.751402 |   1.19259  |
| k-d_tree_sklearn     |     0.642262 |       2.09875  |   1.21795  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638601 |        5.51417 |   0.747447 |
| Bori_Aron_solution-1 |     0.6393   |       12.185   |   0.928795 |
| k-d_tree_sklearn     |     0.7244   |       17.3199  |   1.30981  |
| k-d_tree_polars      |     0.692837 |        5.01969 |   7.69049  |
| barab-szabi-1        |     0.658587 |        5.08399 |   8.25401  |
| k-d_tree_pandas      |     0.66187  |        3.93879 |   8.52217  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.696553 |        75.7226 |    3.12244 |
| k-d_tree_sklearn     |     0.933582 |       255.102  |    4.29209 |
| Bori_Aron_solution-1 |     0.635133 |       154.807  |   16.9588  |