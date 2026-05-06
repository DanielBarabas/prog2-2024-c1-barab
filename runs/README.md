# 2026-05-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.426342 |       0.411512 |   0.403074 |
| barab-szabi-1        |     0.419755 |       0.386146 |   0.407446 |
| solution-1           |     6.90333  |       1e-06    |   0.417573 |
| k-d_tree_polars      |     0.421285 |       0.382531 |   0.424644 |
| Bori_Aron_solution-1 |     0.416981 |       0.512132 |   0.513769 |
| k-d_tree_pandas      |     0.428832 |       0.36128  |   0.523956 |
| k-d_tree_sklearn     |    10.244    |       1.15042  |   1.01275  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.42975  |       0.397313 |   0.416848 |
| barab-szabi-1        |     0.422472 |       0.394447 |   0.417213 |
| barab-szabi-2        |     0.431374 |       0.452887 |   0.444471 |
| Bori_Aron_solution-1 |     0.419263 |       0.523652 |   0.517401 |
| k-d_tree_pandas      |     0.424726 |       0.376498 |   0.531446 |
| k-d_tree_sklearn     |     0.475031 |       0.926498 |   1.02365  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.418586 |       0.418643 |   0.414693 |
| k-d_tree_polars      |     0.427954 |       0.423314 |   0.435778 |
| barab-szabi-1        |     0.427279 |       0.416061 |   0.448445 |
| Bori_Aron_solution-1 |     0.416364 |       0.558547 |   0.523652 |
| k-d_tree_pandas      |     0.418267 |       0.378541 |   0.556699 |
| k-d_tree_sklearn     |     0.423343 |       0.95045  |   1.01569  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.434351 |       0.482878 |   0.45423  |
| k-d_tree_polars      |     0.41878  |       0.554935 |   0.527459 |
| Bori_Aron_solution-1 |     0.416908 |       0.712108 |   0.52864  |
| barab-szabi-1        |     0.421727 |       0.531228 |   0.53489  |
| k-d_tree_pandas      |     0.423422 |       0.478527 |   0.678991 |
| k-d_tree_sklearn     |     0.426641 |       1.16964  |   1.08302  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.42012  |       1.35243  |   0.560136 |
| barab-szabi-2        |     0.423433 |       0.719218 |   0.564501 |
| k-d_tree_polars      |     0.42552  |       0.844423 |   0.85217  |
| barab-szabi-1        |     0.426684 |       0.862145 |   0.900105 |
| k-d_tree_pandas      |     0.433748 |       0.729874 |   1.07075  |
| k-d_tree_sklearn     |     0.427398 |       2.02603  |   1.126    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422326 |        5.06195 |   0.680357 |
| Bori_Aron_solution-1 |     0.425355 |       10.1874  |   0.863904 |
| k-d_tree_sklearn     |     0.429372 |       15.2938  |   1.24508  |
| k-d_tree_polars      |     0.425949 |        4.8707  |   6.32371  |
| barab-szabi-1        |     0.423823 |        4.85267 |   6.33294  |
| k-d_tree_pandas      |     0.422181 |        3.86638 |   6.69219  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.713957 |        66.3183 |    2.54159 |
| k-d_tree_sklearn     |     0.432712 |       182.671  |    3.81412 |
| Bori_Aron_solution-1 |     0.421849 |       133.368  |   25.2836  |