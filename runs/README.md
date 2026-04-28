# 2026-04-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.48366  |       0.41565  |   0.451573 |
| k-d_tree_polars      |     0.534033 |       0.416268 |   0.453393 |
| barab-szabi-2        |     0.474844 |       0.450919 |   0.494688 |
| Bori_Aron_solution-1 |     0.958864 |       0.564276 |   0.578651 |
| k-d_tree_pandas      |     0.493818 |       0.396755 |   0.582473 |
| solution-1           |     8.57266  |       1e-06    |   0.627936 |
| k-d_tree_sklearn     |    11.4721   |       1.47126  |   1.18057  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475799 |       0.461007 |   0.455204 |
| k-d_tree_polars      |     0.492225 |       0.432805 |   0.458334 |
| barab-szabi-1        |     0.493678 |       0.449006 |   0.493146 |
| Bori_Aron_solution-1 |     0.470001 |       0.570938 |   0.573639 |
| k-d_tree_pandas      |     0.485279 |       0.412254 |   0.616295 |
| k-d_tree_sklearn     |     0.491347 |       1.02597  |   1.14157  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470413 |       0.465968 |   0.465184 |
| k-d_tree_polars      |     0.492298 |       0.454575 |   0.498645 |
| barab-szabi-1        |     0.510182 |       0.476523 |   0.503735 |
| Bori_Aron_solution-1 |     0.480464 |       0.639159 |   0.599864 |
| k-d_tree_pandas      |     0.480626 |       0.428351 |   0.619262 |
| k-d_tree_sklearn     |     0.506453 |       1.15086  |   1.17738  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480653 |       0.521536 |   0.494225 |
| Bori_Aron_solution-1 |     0.479518 |       0.806105 |   0.587313 |
| k-d_tree_polars      |     0.485596 |       0.578166 |   0.588209 |
| barab-szabi-1        |     0.476416 |       0.583199 |   0.597584 |
| k-d_tree_pandas      |     0.494018 |       0.520088 |   0.764817 |
| k-d_tree_sklearn     |     0.491182 |       1.35734  |   1.22614  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481344 |       0.782184 |   0.567665 |
| Bori_Aron_solution-1 |     0.477041 |       1.51612  |   0.643405 |
| k-d_tree_polars      |     0.491085 |       0.946562 |   0.983823 |
| barab-szabi-1        |     0.476149 |       0.970395 |   1.03604  |
| k-d_tree_pandas      |     0.479563 |       0.832414 |   1.22181  |
| k-d_tree_sklearn     |     0.490594 |       2.25547  |   1.31264  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484278 |        5.52122 |   0.820257 |
| Bori_Aron_solution-1 |     0.493804 |       11.5151  |   0.872821 |
| k-d_tree_sklearn     |     0.528855 |       18.1298  |   1.42385  |
| barab-szabi-1        |     0.477275 |        5.54237 |   6.83232  |
| k-d_tree_polars      |     0.498881 |        5.68245 |   6.83755  |
| k-d_tree_pandas      |     0.510825 |        4.56056 |   7.33213  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793365 |        74.2299 |    2.90502 |
| k-d_tree_sklearn     |     0.485161 |       243.162  |    4.01385 |
| Bori_Aron_solution-1 |     0.480157 |       160.245  |   13.28    |