# 2025-04-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.514015 |       0.404561 |   0.419861 |
| barab-szabi-2        |     0.51141  |       0.416953 |   0.420512 |
| k-d_tree_polars      |     8.18773  |       0.441039 |   0.553449 |
| Bori_Aron_solution-1 |     0.523657 |       0.569192 |   0.565486 |
| k-d_tree_pandas      |     0.521045 |       0.392672 |   0.571067 |
| solution-1           |     7.9712   |       1e-06    |   0.582874 |
| k-d_tree_sklearn     |     3.02615  |       1.06329  |   1.05536  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.536273 |       0.410741 |   0.421685 |
| k-d_tree_polars      |     0.572079 |       0.419668 |   0.422801 |
| barab-szabi-2        |     0.538465 |       0.411902 |   0.423512 |
| Bori_Aron_solution-1 |     0.523789 |       0.57053  |   0.554006 |
| k-d_tree_pandas      |     0.540235 |       0.408873 |   0.565344 |
| k-d_tree_sklearn     |     0.547756 |       0.985657 |   1.04548  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539419 |       0.440071 |   0.446389 |
| k-d_tree_polars      |     0.531777 |       0.461112 |   0.450184 |
| barab-szabi-1        |     0.532017 |       0.448085 |   0.459335 |
| Bori_Aron_solution-1 |     0.541555 |       0.632691 |   0.57993  |
| k-d_tree_pandas      |     0.547524 |       0.422969 |   0.625431 |
| k-d_tree_sklearn     |     0.552612 |       1.06866  |   1.13194  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547117 |       0.494597 |   0.456063 |
| k-d_tree_polars      |     0.539277 |       0.560883 |   0.545538 |
| Bori_Aron_solution-1 |     0.517177 |       0.774158 |   0.564091 |
| barab-szabi-1        |     0.534554 |       0.551564 |   0.576711 |
| k-d_tree_pandas      |     0.542003 |       0.498967 |   0.751652 |
| k-d_tree_sklearn     |     0.534561 |       1.28744  |   1.14053  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529446 |       0.742759 |   0.501626 |
| Bori_Aron_solution-1 |     0.530921 |       1.44833  |   0.606313 |
| k-d_tree_polars      |     0.530262 |       0.894562 |   0.915343 |
| barab-szabi-1        |     0.538634 |       0.893982 |   0.949215 |
| k-d_tree_pandas      |     0.534236 |       0.772413 |   1.21074  |
| k-d_tree_sklearn     |     0.537893 |       2.19278  |   1.27858  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53649  |        5.48348 |   0.749948 |
| Bori_Aron_solution-1 |     0.53726  |       10.86    |   0.895528 |
| k-d_tree_sklearn     |     0.537028 |       17.0488  |   1.34755  |
| barab-szabi-1        |     0.5449   |        5.06536 |   6.78974  |
| k-d_tree_polars      |     0.541408 |        5.00955 |   6.85999  |
| k-d_tree_pandas      |     0.535192 |        3.99161 |   7.24022  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528514 |        78.5634 |    2.78541 |
| k-d_tree_sklearn     |     0.743168 |       238.472  |    4.56216 |
| Bori_Aron_solution-1 |     0.543994 |       150.473  |   18.9669  |