# 2026-08-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.67586  |       0.545251 |   0.445899 |
| k-d_tree_polars      |     0.461468 |       0.418763 |   0.451292 |
| barab-szabi-1        |     0.456865 |       0.410196 |   0.461079 |
| Bori_Aron_solution-1 |     4.74613  |       0.693164 |   0.479285 |
| solution-1           |     7.83094  |       1e-06    |   0.481033 |
| k-d_tree_pandas      |     0.864661 |       0.379513 |   0.553059 |
| k-d_tree_sklearn     |     2.87375  |       1.12359  |   1.05742  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464562 |       0.439734 |   0.44386  |
| barab-szabi-1        |     0.4691   |       0.425686 |   0.452245 |
| k-d_tree_polars      |     0.471187 |       0.416354 |   0.452424 |
| Bori_Aron_solution-1 |     0.463497 |       0.553019 |   0.543949 |
| k-d_tree_pandas      |     0.470245 |       0.399918 |   0.571143 |
| k-d_tree_sklearn     |     0.468939 |       1.00124  |   1.09156  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464965 |       0.451092 |   0.454352 |
| k-d_tree_polars      |     0.476256 |       0.47944  |   0.473263 |
| barab-szabi-1        |     0.468204 |       0.446827 |   0.482808 |
| Bori_Aron_solution-1 |     0.459109 |       0.592025 |   0.549771 |
| k-d_tree_pandas      |     0.489799 |       0.413245 |   0.594798 |
| k-d_tree_sklearn     |     0.466202 |       1.03728  |   1.09286  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464928 |       0.511492 |   0.479669 |
| Bori_Aron_solution-1 |     0.457973 |       0.764314 |   0.559786 |
| k-d_tree_polars      |     0.467406 |       0.562585 |   0.567019 |
| barab-szabi-1        |     0.470672 |       0.565922 |   0.579469 |
| k-d_tree_pandas      |     0.468499 |       0.49532  |   0.723017 |
| k-d_tree_sklearn     |     0.469383 |       1.26224  |   1.14285  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467292 |       0.729811 |   0.506793 |
| Bori_Aron_solution-1 |     0.462503 |       1.42729  |   0.582576 |
| k-d_tree_polars      |     0.464802 |       0.90927  |   0.91185  |
| barab-szabi-1        |     0.464646 |       0.924654 |   0.948833 |
| k-d_tree_pandas      |     0.465002 |       0.788904 |   1.17292  |
| k-d_tree_sklearn     |     0.46712  |       2.09348  |   1.214    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462686 |        5.11889 |   0.746204 |
| Bori_Aron_solution-1 |     0.463674 |       10.8871  |   0.811148 |
| k-d_tree_sklearn     |     0.502792 |       18.4771  |   1.40695  |
| barab-szabi-1        |     0.468709 |        5.18572 |   6.65574  |
| k-d_tree_polars      |     0.4666   |        5.35058 |   7.0405   |
| k-d_tree_pandas      |     0.472255 |        4.28855 |   7.0623   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.899132 |        69.7689 |    2.73121 |
| k-d_tree_sklearn     |     0.573978 |       229.771  |    3.80519 |
| Bori_Aron_solution-1 |     0.532681 |       153.599  |   23.3487  |