# 2025-12-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.958978 |       0.55996  |   0.426355 |
| k-d_tree_polars      |     0.97768  |       0.40901  |   0.435394 |
| barab-szabi-1        |     0.994421 |       0.40518  |   0.436758 |
| Bori_Aron_solution-1 |     0.978212 |       0.567793 |   0.548286 |
| solution-1           |     9.30394  |       1e-06    |   0.702254 |
| k-d_tree_pandas      |     9.18969  |       0.457812 |   0.729134 |
| k-d_tree_sklearn     |     3.88547  |       1.23045  |   1.05652  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.980853 |       0.419941 |   0.431036 |
| barab-szabi-2        |     0.981374 |       0.434038 |   0.436512 |
| barab-szabi-1        |     0.980316 |       0.403983 |   0.437567 |
| Bori_Aron_solution-1 |     0.971576 |       0.551132 |   0.533931 |
| k-d_tree_pandas      |     0.989429 |       0.40258  |   0.574703 |
| k-d_tree_sklearn     |     0.982625 |       0.97609  |   1.05465  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553043 |       0.439396 |   0.441298 |
| k-d_tree_polars      |     0.533199 |       0.437718 |   0.452079 |
| barab-szabi-1        |     0.522017 |       0.429298 |   0.455807 |
| Bori_Aron_solution-1 |     0.5179   |       0.587917 |   0.544043 |
| k-d_tree_pandas      |     0.753315 |       0.407921 |   0.594022 |
| k-d_tree_sklearn     |     0.525425 |       1.00114  |   1.0698   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525662 |       0.497363 |   0.470665 |
| Bori_Aron_solution-1 |     0.518263 |       0.768724 |   0.553823 |
| barab-szabi-1        |     0.52859  |       0.553176 |   0.568576 |
| k-d_tree_polars      |     0.53348  |       0.549448 |   0.572063 |
| k-d_tree_pandas      |     0.526855 |       0.501836 |   0.73366  |
| k-d_tree_sklearn     |     0.533269 |       1.24096  |   1.11773  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526195 |       0.730696 |   0.496833 |
| Bori_Aron_solution-1 |     0.52335  |       1.44791  |   0.57727  |
| k-d_tree_polars      |     0.525881 |       0.913582 |   0.899075 |
| barab-szabi-1        |     0.547973 |       0.916464 |   0.936792 |
| k-d_tree_pandas      |     0.527458 |       0.811832 |   1.15897  |
| k-d_tree_sklearn     |     0.532757 |       2.08854  |   1.19812  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521204 |        4.89009 |   0.735061 |
| Bori_Aron_solution-1 |     0.532605 |       10.8802  |   0.834539 |
| k-d_tree_sklearn     |     0.534914 |       15.7835  |   1.30426  |
| k-d_tree_polars      |     0.54291  |        5.43916 |   6.47452  |
| barab-szabi-1        |     0.528265 |        5.35672 |   6.50046  |
| k-d_tree_pandas      |     0.53054  |        4.44188 |   6.68469  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530116 |         79.604 |    2.6404  |
| k-d_tree_sklearn     |     0.553401 |        230.872 |    4.01837 |
| Bori_Aron_solution-1 |     0.608641 |        151.488 |   15.1572  |