# 2024-11-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.53958  |       1e-06    |   0.348833 |
| barab-szabi-2        |     0.62045  |       0.387286 |   0.383733 |
| barab-szabi-1        |     0.614296 |       0.39506  |   0.384653 |
| k-d_tree_polars      |     0.612058 |       0.399623 |   0.386101 |
| Bori_Aron_solution-1 |     0.605194 |       0.517069 |   0.512971 |
| k-d_tree_pandas      |     0.607603 |       0.378426 |   0.517155 |
| k-d_tree_sklearn     |    10.3236   |       1.00289  |   0.950928 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607613 |       0.386377 |   0.383407 |
| k-d_tree_polars      |     0.607898 |       0.404726 |   0.386334 |
| barab-szabi-1        |     0.613709 |       0.410244 |   0.401298 |
| k-d_tree_pandas      |     0.619026 |       0.381171 |   0.5241   |
| Bori_Aron_solution-1 |     0.611495 |       0.528073 |   0.528091 |
| k-d_tree_sklearn     |     0.612807 |       0.890108 |   0.961059 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614673 |       0.401334 |   0.398476 |
| k-d_tree_polars      |     0.611663 |       0.42861  |   0.416074 |
| barab-szabi-1        |     0.615159 |       0.439435 |   0.428199 |
| Bori_Aron_solution-1 |     0.610794 |       0.565296 |   0.520476 |
| k-d_tree_pandas      |     0.61277  |       0.413186 |   0.57897  |
| k-d_tree_sklearn     |     0.613856 |       0.928328 |   0.991141 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621022 |       0.46843  |   0.431946 |
| k-d_tree_polars      |     0.621201 |       0.546203 |   0.521655 |
| barab-szabi-1        |     0.630628 |       0.543831 |   0.532146 |
| Bori_Aron_solution-1 |     0.617482 |       0.754117 |   0.534936 |
| k-d_tree_pandas      |     0.621077 |       0.481689 |   0.71653  |
| k-d_tree_sklearn     |     0.627948 |       1.19191  |   1.05417  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617803 |       0.724247 |   0.467746 |
| Bori_Aron_solution-1 |     0.60703  |       1.42062  |   0.569257 |
| k-d_tree_polars      |     0.62194  |       0.870495 |   0.898283 |
| barab-szabi-1        |     0.619147 |       0.863945 |   0.906776 |
| k-d_tree_sklearn     |     0.622226 |       2.04289  |   1.14583  |
| k-d_tree_pandas      |     0.628819 |       0.764927 |   1.1645   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612072 |        5.18552 |   0.706004 |
| Bori_Aron_solution-1 |     0.604661 |       10.6634  |   0.809273 |
| k-d_tree_sklearn     |     0.629384 |       15.7932  |   1.2346   |
| barab-szabi-1        |     0.612756 |        4.88646 |   6.42642  |
| k-d_tree_polars      |     0.609433 |        4.85053 |   6.51565  |
| k-d_tree_pandas      |     0.621869 |        3.89526 |   6.9337   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627955 |        70.0482 |    2.81761 |
| k-d_tree_sklearn     |     0.621182 |       224.82   |    4.20097 |
| Bori_Aron_solution-1 |     0.623432 |       141.865  |   17.8287  |