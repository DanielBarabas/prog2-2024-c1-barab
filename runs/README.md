# 2025-10-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556745 |       0.422811 |   0.438092 |
| barab-szabi-2        |     0.534312 |       0.591105 |   0.438245 |
| barab-szabi-1        |     0.582543 |       0.454291 |   0.461007 |
| solution-1           |     7.26574  |       1e-06    |   0.493434 |
| Bori_Aron_solution-1 |     0.569163 |       0.560931 |   0.564062 |
| k-d_tree_pandas      |     7.69661  |       0.43067  |   0.720693 |
| k-d_tree_sklearn     |     2.98967  |       1.27561  |   1.18895  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565209 |       0.445615 |   0.442582 |
| k-d_tree_polars      |     0.564978 |       0.434764 |   0.462369 |
| barab-szabi-1        |     0.564835 |       0.451249 |   0.464252 |
| k-d_tree_pandas      |     0.551446 |       0.400267 |   0.586274 |
| Bori_Aron_solution-1 |     0.575325 |       0.588484 |   0.620412 |
| k-d_tree_sklearn     |     0.57082  |       1.08845  |   1.13356  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.573654 |       0.451282 |   0.463655 |
| barab-szabi-1        |     0.552814 |       0.456988 |   0.470308 |
| barab-szabi-2        |     0.554539 |       0.448389 |   0.499053 |
| Bori_Aron_solution-1 |     0.541654 |       0.646107 |   0.595117 |
| k-d_tree_pandas      |     0.565648 |       0.464955 |   0.643221 |
| k-d_tree_sklearn     |     0.559619 |       1.06588  |   1.13205  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602216 |       0.525445 |   0.500474 |
| Bori_Aron_solution-1 |     0.583144 |       0.820617 |   0.578521 |
| k-d_tree_polars      |     0.577585 |       0.630203 |   0.585565 |
| barab-szabi-1        |     0.557748 |       0.588428 |   0.598321 |
| k-d_tree_pandas      |     0.601362 |       0.536994 |   0.77065  |
| k-d_tree_sklearn     |     0.6152   |       1.40339  |   1.20859  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.562139 |       1.50144  |   0.606355 |
| barab-szabi-2        |     0.555608 |       0.798635 |   0.666608 |
| k-d_tree_polars      |     0.554463 |       0.985146 |   0.963748 |
| barab-szabi-1        |     0.609559 |       0.988169 |   0.984061 |
| k-d_tree_pandas      |     0.552315 |       0.839505 |   1.19504  |
| k-d_tree_sklearn     |     0.615536 |       2.25611  |   1.28068  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616008 |        5.90669 |   0.792639 |
| Bori_Aron_solution-1 |     0.547261 |       11.8554  |   0.906708 |
| k-d_tree_sklearn     |     0.588793 |       19.2798  |   1.50863  |
| k-d_tree_polars      |     0.625289 |        5.81715 |   7.18823  |
| barab-szabi-1        |     0.585324 |        5.84688 |   7.70626  |
| k-d_tree_pandas      |     0.557346 |        4.69868 |   7.92296  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569933 |        77.7619 |    3.12701 |
| k-d_tree_sklearn     |     0.57121  |       259.594  |    4.62551 |
| Bori_Aron_solution-1 |     0.821635 |       159.419  |   18.4775  |