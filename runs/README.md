# 2025-06-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569146 |       0.437881 |   0.432229 |
| barab-szabi-1        |     0.562031 |       0.40756  |   0.433803 |
| k-d_tree_polars      |     0.566262 |       0.410653 |   0.47382  |
| solution-1           |     8.38748  |       1e-06    |   0.523952 |
| Bori_Aron_solution-1 |     0.560452 |       0.563001 |   0.570807 |
| k-d_tree_pandas      |     0.577863 |       0.395725 |   0.581636 |
| k-d_tree_sklearn     |    10.8622   |       1.65821  |   1.10767  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554996 |       0.424912 |   0.425752 |
| k-d_tree_polars      |     0.576081 |       0.421294 |   0.436812 |
| barab-szabi-1        |     0.572314 |       0.427032 |   0.448529 |
| Bori_Aron_solution-1 |     0.553874 |       0.557442 |   0.54243  |
| k-d_tree_pandas      |     0.568093 |       0.396677 |   0.553802 |
| k-d_tree_sklearn     |     0.565799 |       1.01302  |   1.08184  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558564 |       0.437453 |   0.432424 |
| k-d_tree_polars      |     0.565316 |       0.47075  |   0.456604 |
| barab-szabi-1        |     0.558683 |       0.447468 |   0.463595 |
| Bori_Aron_solution-1 |     0.545163 |       0.594896 |   0.553443 |
| k-d_tree_pandas      |     0.556262 |       0.409162 |   0.600621 |
| k-d_tree_sklearn     |     0.557803 |       1.02357  |   1.11214  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550966 |       0.501855 |   0.470243 |
| k-d_tree_polars      |     0.554167 |       0.549721 |   0.554935 |
| Bori_Aron_solution-1 |     0.56391  |       0.761206 |   0.560342 |
| barab-szabi-1        |     0.547908 |       0.543086 |   0.56611  |
| k-d_tree_pandas      |     0.55348  |       0.489026 |   0.736988 |
| k-d_tree_sklearn     |     0.557709 |       1.26211  |   1.13285  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553324 |       0.741057 |   0.491684 |
| Bori_Aron_solution-1 |     0.55278  |       1.43821  |   0.589299 |
| k-d_tree_polars      |     0.555782 |       0.881851 |   0.908458 |
| barab-szabi-1        |     0.557336 |       0.880919 |   0.946328 |
| k-d_tree_pandas      |     0.551136 |       0.757823 |   1.17511  |
| k-d_tree_sklearn     |     0.55708  |       2.08094  |   1.2035   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548992 |        5.34654 |   0.724107 |
| Bori_Aron_solution-1 |     0.551502 |       10.6262  |   0.838025 |
| k-d_tree_sklearn     |     0.557213 |       16.1499  |   1.30609  |
| k-d_tree_polars      |     0.559168 |        4.90192 |   6.59303  |
| barab-szabi-1        |     0.556845 |        4.95356 |   6.61682  |
| k-d_tree_pandas      |     0.554515 |        3.903   |   7.07108  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587196 |        70.6373 |    2.62744 |
| k-d_tree_sklearn     |     0.557983 |       235.292  |    3.97616 |
| Bori_Aron_solution-1 |     0.556094 |       146.609  |   16.2221  |