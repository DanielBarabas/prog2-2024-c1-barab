# 2026-09-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.46141  |       0.421999 |   0.451152 |
| barab-szabi-2        |     0.482126 |       0.45855  |   0.461021 |
| k-d_tree_pandas      |     0.468313 |       0.38869  |   0.546507 |
| Bori_Aron_solution-1 |     0.487778 |       0.541492 |   0.547384 |
| solution-1           |     7.7374   |       1e-06    |   0.663027 |
| barab-szabi-1        |     8.54552  |       0.566224 |   0.882609 |
| k-d_tree_sklearn     |     3.5381   |       1.52752  |   1.11593  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492938 |       0.461939 |   0.463315 |
| k-d_tree_polars      |     0.486501 |       0.438312 |   0.468328 |
| barab-szabi-1        |     0.486901 |       0.443127 |   0.472952 |
| Bori_Aron_solution-1 |     0.486071 |       0.597971 |   0.575172 |
| k-d_tree_pandas      |     0.489514 |       0.412894 |   0.587392 |
| k-d_tree_sklearn     |     0.523735 |       1.04538  |   1.15762  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470886 |       0.459017 |   0.457412 |
| k-d_tree_polars      |     0.479332 |       0.452049 |   0.475269 |
| barab-szabi-1        |     0.497065 |       0.485194 |   0.491498 |
| Bori_Aron_solution-1 |     0.466885 |       0.59357  |   0.553949 |
| k-d_tree_pandas      |     0.480557 |       0.411421 |   0.597738 |
| k-d_tree_sklearn     |     0.478135 |       1.06014  |   1.10342  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470126 |       0.516514 |   0.486416 |
| Bori_Aron_solution-1 |     0.482665 |       0.798368 |   0.583617 |
| k-d_tree_polars      |     0.482462 |       0.591028 |   0.589913 |
| barab-szabi-1        |     0.489913 |       0.593805 |   0.598383 |
| k-d_tree_pandas      |     0.488156 |       0.511821 |   0.780133 |
| k-d_tree_sklearn     |     0.489473 |       1.3351   |   1.18985  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472084 |       0.774676 |   0.570113 |
| Bori_Aron_solution-1 |     0.478226 |       1.42366  |   0.590997 |
| k-d_tree_polars      |     0.49818  |       0.941271 |   0.95032  |
| barab-szabi-1        |     0.473204 |       0.942848 |   0.982759 |
| k-d_tree_pandas      |     0.473806 |       0.807948 |   1.22208  |
| k-d_tree_sklearn     |     0.478718 |       2.14093  |   1.22689  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47823  |        5.28033 |   0.775941 |
| Bori_Aron_solution-1 |     0.473559 |       11.0011  |   0.814531 |
| k-d_tree_sklearn     |     0.48157  |       17.1263  |   1.31408  |
| k-d_tree_polars      |     0.480618 |        5.41758 |   6.73805  |
| barab-szabi-1        |     0.501124 |        5.38003 |   6.78691  |
| k-d_tree_pandas      |     0.468642 |        4.41008 |   7.13875  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60386  |         78.714 |    3.09818 |
| k-d_tree_sklearn     |     0.868822 |        249.648 |    4.10175 |
| Bori_Aron_solution-1 |     0.496016 |        160     |   15.7233  |