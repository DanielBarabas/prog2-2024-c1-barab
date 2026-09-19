# 2026-09-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.468156 |       0.419018 |   0.457176 |
| solution-1           |     7.55858  |       2e-06    |   0.460304 |
| barab-szabi-2        |     0.488276 |       0.535919 |   0.50739  |
| Bori_Aron_solution-1 |     0.457034 |       0.547601 |   0.542166 |
| k-d_tree_pandas      |     0.464187 |       0.389828 |   0.558246 |
| barab-szabi-1        |     8.46793  |       0.494374 |   0.586185 |
| k-d_tree_sklearn     |     3.00737  |       1.14019  |   1.10198  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.478026 |       0.433241 |   0.455297 |
| k-d_tree_polars      |     0.494624 |       0.430379 |   0.468141 |
| barab-szabi-2        |     0.475084 |       0.456704 |   0.471151 |
| Bori_Aron_solution-1 |     0.469686 |       0.561927 |   0.553586 |
| k-d_tree_pandas      |     0.482647 |       0.401825 |   0.558816 |
| k-d_tree_sklearn     |     0.486298 |       1.00685  |   1.09034  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494582 |       0.460129 |   0.459839 |
| barab-szabi-1        |     0.480256 |       0.459341 |   0.482775 |
| k-d_tree_polars      |     0.479537 |       0.448885 |   0.484741 |
| Bori_Aron_solution-1 |     0.489562 |       0.600058 |   0.560887 |
| k-d_tree_pandas      |     0.477878 |       0.416054 |   0.613958 |
| k-d_tree_sklearn     |     0.478949 |       1.05514  |   1.11611  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473722 |       0.527782 |   0.497951 |
| Bori_Aron_solution-1 |     0.474091 |       0.780426 |   0.565107 |
| k-d_tree_polars      |     0.485655 |       0.585485 |   0.577959 |
| barab-szabi-1        |     0.477168 |       0.571756 |   0.607196 |
| k-d_tree_pandas      |     0.478378 |       0.516294 |   0.74767  |
| k-d_tree_sklearn     |     0.477319 |       1.31203  |   1.16958  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483709 |       0.734262 |   0.526869 |
| Bori_Aron_solution-1 |     0.469403 |       1.45408  |   0.606597 |
| k-d_tree_polars      |     0.479886 |       0.930301 |   0.936823 |
| barab-szabi-1        |     0.474472 |       0.937035 |   0.97017  |
| k-d_tree_pandas      |     0.479876 |       0.81237  |   1.19464  |
| k-d_tree_sklearn     |     0.483104 |       2.11787  |   1.29704  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481268 |        5.12017 |   0.755415 |
| Bori_Aron_solution-1 |     0.468263 |       11.007   |   0.821943 |
| k-d_tree_sklearn     |     0.487109 |       16.5855  |   1.33491  |
| k-d_tree_polars      |     0.480708 |        5.31539 |   6.62412  |
| barab-szabi-1        |     0.481314 |        5.42601 |   6.74689  |
| k-d_tree_pandas      |     0.481788 |        4.30572 |   7.03089  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578239 |        68.5823 |    2.80183 |
| k-d_tree_sklearn     |     0.670835 |       234.739  |    4.03262 |
| Bori_Aron_solution-1 |     0.471413 |       146.926  |   26.0983  |