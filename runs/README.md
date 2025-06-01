# 2025-06-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549953 |       0.415693 |   0.414371 |
| k-d_tree_polars      |     0.565078 |       0.400318 |   0.424415 |
| solution-1           |     7.24479  |       1e-06    |   0.425061 |
| Bori_Aron_solution-1 |     0.529577 |       0.540648 |   0.539861 |
| barab-szabi-1        |     7.58043  |       0.437743 |   0.541743 |
| k-d_tree_pandas      |     0.548058 |       0.380789 |   0.550783 |
| k-d_tree_sklearn     |     2.8634   |       1.58694  |   1.03207  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547308 |       0.418446 |   0.423287 |
| barab-szabi-1        |     0.547331 |       0.421553 |   0.424463 |
| k-d_tree_polars      |     0.547806 |       0.407193 |   0.428641 |
| Bori_Aron_solution-1 |     0.54021  |       0.552966 |   0.545042 |
| k-d_tree_pandas      |     0.55201  |       0.391289 |   0.56255  |
| k-d_tree_sklearn     |     0.550941 |       0.953318 |   1.02807  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547684 |       0.433313 |   0.433829 |
| k-d_tree_polars      |     0.54518  |       0.432176 |   0.453627 |
| barab-szabi-1        |     0.55177  |       0.438051 |   0.454354 |
| Bori_Aron_solution-1 |     0.546706 |       0.58679  |   0.546147 |
| k-d_tree_pandas      |     0.54768  |       0.403206 |   0.586927 |
| k-d_tree_sklearn     |     0.54588  |       0.988419 |   1.07176  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547383 |       0.489925 |   0.460116 |
| k-d_tree_polars      |     0.549731 |       0.569071 |   0.547134 |
| barab-szabi-1        |     0.545399 |       0.542943 |   0.551287 |
| Bori_Aron_solution-1 |     0.542291 |       0.761433 |   0.571738 |
| k-d_tree_pandas      |     0.550182 |       0.485426 |   0.731096 |
| k-d_tree_sklearn     |     0.560746 |       1.21924  |   1.11984  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542577 |       0.739658 |   0.489107 |
| Bori_Aron_solution-1 |     0.542855 |       1.40572  |   0.579133 |
| k-d_tree_polars      |     0.54921  |       0.874559 |   0.903559 |
| barab-szabi-1        |     0.543786 |       0.877131 |   0.938759 |
| k-d_tree_pandas      |     0.554153 |       0.76719  |   1.16634  |
| k-d_tree_sklearn     |     0.549084 |       2.03715  |   1.2078   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54609  |        5.20777 |   0.726216 |
| Bori_Aron_solution-1 |     0.540819 |       10.4749  |   0.870692 |
| k-d_tree_sklearn     |     0.551872 |       15.8303  |   1.31599  |
| k-d_tree_polars      |     0.546098 |        5.02059 |   6.42158  |
| barab-szabi-1        |     0.551473 |        4.96734 |   6.49059  |
| k-d_tree_pandas      |     0.549006 |        4.02516 |   6.87144  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632989 |        71.0412 |    2.64997 |
| k-d_tree_sklearn     |     0.765182 |       225.9    |    4.29115 |
| Bori_Aron_solution-1 |     0.550241 |       149.938  |   12.1487  |