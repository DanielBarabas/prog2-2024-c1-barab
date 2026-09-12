# 2026-09-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.8576   |       1e-06    |   0.431084 |
| barab-szabi-2        |     0.483159 |       0.431528 |   0.437501 |
| k-d_tree_polars      |     0.455122 |       0.417962 |   0.439517 |
| k-d_tree_pandas      |     0.452127 |       0.381744 |   0.536417 |
| Bori_Aron_solution-1 |     0.455624 |       0.5363   |   0.542385 |
| barab-szabi-1        |     9.64291  |       0.463793 |   0.581434 |
| k-d_tree_sklearn     |     3.05046  |       1.12565  |   1.04809  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464012 |       0.437203 |   0.435053 |
| k-d_tree_polars      |     0.465185 |       0.416794 |   0.438307 |
| barab-szabi-1        |     0.458921 |       0.419634 |   0.439522 |
| Bori_Aron_solution-1 |     0.454101 |       0.542104 |   0.535215 |
| k-d_tree_pandas      |     0.462456 |       0.38917  |   0.544342 |
| k-d_tree_sklearn     |     0.469164 |       1.01416  |   1.05312  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460966 |       0.450262 |   0.446613 |
| barab-szabi-1        |     0.46328  |       0.448719 |   0.46029  |
| k-d_tree_polars      |     0.463191 |       0.447644 |   0.466569 |
| Bori_Aron_solution-1 |     0.459172 |       0.585953 |   0.538463 |
| k-d_tree_pandas      |     0.462089 |       0.403493 |   0.578729 |
| k-d_tree_sklearn     |     0.534011 |       1.14504  |   1.07695  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465321 |       0.505152 |   0.469029 |
| Bori_Aron_solution-1 |     0.457474 |       0.768424 |   0.555576 |
| k-d_tree_polars      |     0.46825  |       0.556757 |   0.561863 |
| barab-szabi-1        |     0.460877 |       0.560793 |   0.572367 |
| k-d_tree_pandas      |     0.462344 |       0.494358 |   0.709617 |
| k-d_tree_sklearn     |     0.470861 |       1.25008  |   1.11269  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462333 |       0.759451 |   0.511572 |
| Bori_Aron_solution-1 |     0.453235 |       1.44901  |   0.577647 |
| k-d_tree_polars      |     0.463469 |       0.891427 |   0.959172 |
| barab-szabi-1        |     0.463367 |       0.904355 |   0.98602  |
| k-d_tree_sklearn     |     0.469118 |       2.11502  |   1.14675  |
| k-d_tree_pandas      |     0.463382 |       0.771547 |   1.16975  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463421 |        5.64952 |   0.738572 |
| Bori_Aron_solution-1 |     0.456151 |       11.3597  |   0.80471  |
| k-d_tree_sklearn     |     0.463836 |       17.1526  |   1.22742  |
| barab-szabi-1        |     0.461539 |        5.02209 |   7.51156  |
| k-d_tree_polars      |     0.460524 |        5.06097 |   7.51513  |
| k-d_tree_pandas      |     0.463175 |        4.02228 |   7.89222  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558932 |        86.3242 |    2.68345 |
| k-d_tree_sklearn     |     0.710534 |       261.3    |    3.47815 |
| Bori_Aron_solution-1 |     0.458776 |       157.321  |   16.0089  |