# 2025-05-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63712  |       1e-06    |   0.358376 |
| barab-szabi-2        |     0.512856 |       0.411741 |   0.412255 |
| barab-szabi-1        |     0.515065 |       0.400319 |   0.414689 |
| k-d_tree_polars      |     7.88192  |       0.463078 |   0.472758 |
| Bori_Aron_solution-1 |     0.504358 |       0.541514 |   0.544593 |
| k-d_tree_pandas      |     0.506935 |       0.383661 |   0.555585 |
| k-d_tree_sklearn     |     2.97235  |       0.979118 |   1.03328  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524251 |       0.425627 |   0.415644 |
| barab-szabi-1        |     0.520788 |       0.409953 |   0.423539 |
| k-d_tree_polars      |     0.517237 |       0.443781 |   0.425082 |
| Bori_Aron_solution-1 |     0.523373 |       0.550571 |   0.543899 |
| k-d_tree_pandas      |     0.527274 |       0.390249 |   0.560598 |
| k-d_tree_sklearn     |     0.523521 |       0.963821 |   1.04243  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523839 |       0.430293 |   0.425365 |
| barab-szabi-1        |     0.520915 |       0.432718 |   0.452634 |
| k-d_tree_polars      |     0.530417 |       0.438229 |   0.455488 |
| Bori_Aron_solution-1 |     0.512434 |       0.591583 |   0.572425 |
| k-d_tree_pandas      |     0.525096 |       0.403491 |   0.600776 |
| k-d_tree_sklearn     |     0.533828 |       1.00415  |   1.08249  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532043 |       0.486155 |   0.460116 |
| k-d_tree_polars      |     0.529664 |       0.546193 |   0.538747 |
| Bori_Aron_solution-1 |     0.517531 |       0.758716 |   0.556982 |
| barab-szabi-1        |     0.528928 |       0.547042 |   0.558478 |
| k-d_tree_pandas      |     0.522794 |       0.492519 |   0.737222 |
| k-d_tree_sklearn     |     0.52738  |       1.23692  |   1.13267  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519317 |       0.726307 |   0.49059  |
| Bori_Aron_solution-1 |     0.52196  |       1.39536  |   0.592664 |
| k-d_tree_polars      |     0.525948 |       0.883176 |   0.887397 |
| barab-szabi-1        |     0.522626 |       0.89425  |   0.935991 |
| k-d_tree_pandas      |     0.522931 |       0.757799 |   1.17382  |
| k-d_tree_sklearn     |     0.52302  |       2.04888  |   1.20606  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516598 |        5.2819  |   0.736084 |
| Bori_Aron_solution-1 |     0.528517 |       10.5857  |   0.881907 |
| k-d_tree_sklearn     |     0.533669 |       16.7775  |   1.32696  |
| barab-szabi-1        |     0.520541 |        5.03787 |   6.55454  |
| k-d_tree_polars      |     0.522172 |        5.08867 |   6.55547  |
| k-d_tree_pandas      |     0.522121 |        3.99738 |   7.06288  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51968  |        74.8945 |    2.92963 |
| k-d_tree_sklearn     |     0.726009 |       233.164  |    4.20565 |
| Bori_Aron_solution-1 |     0.57619  |       144.946  |   18.0014  |