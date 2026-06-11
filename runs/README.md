# 2026-06-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.15995  |       0.780391 |   0.422676 |
| k-d_tree_polars      |     0.464786 |       0.401449 |   0.432759 |
| barab-szabi-1        |     0.833963 |       0.414087 |   0.455298 |
| solution-1           |     8.76665  |       1e-06    |   0.535942 |
| Bori_Aron_solution-1 |     0.461436 |       0.543834 |   0.536199 |
| k-d_tree_pandas      |     0.467988 |       0.385976 |   0.545069 |
| k-d_tree_sklearn     |     3.12299  |       1.60353  |   1.10942  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.464029 |       0.415143 |   0.432547 |
| barab-szabi-1        |     0.466526 |       0.406273 |   0.435311 |
| barab-szabi-2        |     0.472088 |       0.440519 |   0.438027 |
| Bori_Aron_solution-1 |     0.455468 |       0.55406  |   0.545322 |
| k-d_tree_pandas      |     0.474443 |       0.397249 |   0.565422 |
| k-d_tree_sklearn     |     0.466598 |       0.965198 |   1.09172  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472677 |       0.451265 |   0.451077 |
| barab-szabi-1        |     0.46997  |       0.436619 |   0.465744 |
| k-d_tree_polars      |     0.464988 |       0.437197 |   0.46778  |
| Bori_Aron_solution-1 |     0.457485 |       0.589416 |   0.541574 |
| k-d_tree_pandas      |     0.465189 |       0.413416 |   0.58137  |
| k-d_tree_sklearn     |     0.484878 |       1.02537  |   1.08437  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462701 |       0.513234 |   0.469133 |
| k-d_tree_polars      |     0.46464  |       0.57376  |   0.557896 |
| Bori_Aron_solution-1 |     0.466645 |       0.790548 |   0.56164  |
| barab-szabi-1        |     0.471992 |       0.559379 |   0.581114 |
| k-d_tree_pandas      |     0.466967 |       0.507034 |   0.720727 |
| k-d_tree_sklearn     |     0.475713 |       1.25998  |   1.12748  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475717 |       0.761863 |   0.528547 |
| Bori_Aron_solution-1 |     0.459443 |       1.48841  |   0.589961 |
| k-d_tree_polars      |     0.464839 |       0.923164 |   0.960455 |
| barab-szabi-1        |     0.468841 |       0.913956 |   0.997518 |
| k-d_tree_sklearn     |     0.476435 |       2.17434  |   1.18149  |
| k-d_tree_pandas      |     0.478714 |       0.805697 |   1.18443  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464994 |        5.61286 |   0.744906 |
| Bori_Aron_solution-1 |     0.452153 |       11.5409  |   0.804705 |
| k-d_tree_sklearn     |     0.462168 |       17.8267  |   1.26863  |
| barab-szabi-1        |     0.465785 |        5.31305 |   7.48664  |
| k-d_tree_polars      |     0.464128 |        5.21738 |   7.55329  |
| k-d_tree_pandas      |     0.472498 |        4.13013 |   7.96246  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465917 |        80.9079 |    2.73143 |
| k-d_tree_sklearn     |     0.823658 |       263.059  |    3.521   |
| Bori_Aron_solution-1 |     0.475593 |       158.949  |   24.9211  |