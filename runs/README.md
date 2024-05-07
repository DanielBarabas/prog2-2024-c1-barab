# 2024-05-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     8.33642  |       0.432385 |   0.357483 |
| barab-szabi-2        |     0.719317 |       0.376479 |   0.361641 |
| k-d_tree_polars      |     0.758502 |       0.443239 |   0.362082 |
| solution-1           |     8.24781  |       1e-06    |   0.384662 |
| k-d_tree_pandas      |     0.725917 |       0.401629 |   0.491281 |
| Bori_Aron_solution-1 |     0.723657 |       0.55541  |   0.539115 |
| k-d_tree_sklearn     |     3.39743  |       0.934313 |   0.694392 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.769348 |       0.420915 |   0.359548 |
| k-d_tree_polars      |     0.750321 |       0.43541  |   0.360932 |
| barab-szabi-2        |     0.754893 |       0.367088 |   0.363066 |
| Bori_Aron_solution-1 |     0.74532  |       0.505141 |   0.499384 |
| k-d_tree_pandas      |     0.75987  |       0.408109 |   0.517084 |
| k-d_tree_sklearn     |     0.772218 |       0.89795  |   0.68974  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.768313 |       0.382321 |   0.401035 |
| barab-szabi-1        |     0.772115 |       0.465409 |   0.413952 |
| k-d_tree_polars      |     0.768943 |       0.465071 |   0.419971 |
| Bori_Aron_solution-1 |     0.75721  |       0.559133 |   0.501055 |
| k-d_tree_pandas      |     0.786362 |       0.440102 |   0.569377 |
| k-d_tree_sklearn     |     0.790286 |       0.964425 |   0.737014 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.76122  |       0.45164  |   0.406404 |
| barab-szabi-1        |     0.75669  |       0.557541 |   0.506039 |
| k-d_tree_polars      |     0.772496 |       0.564434 |   0.512077 |
| Bori_Aron_solution-1 |     0.750352 |       0.730584 |   0.525417 |
| k-d_tree_pandas      |     0.771716 |       0.505086 |   0.695021 |
| k-d_tree_sklearn     |     0.762144 |       1.16396  |   0.790103 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.757213 |       0.696117 |   0.433972 |
| Bori_Aron_solution-1 |     0.753267 |       1.38535  |   0.536586 |
| k-d_tree_polars      |     0.772319 |       0.878275 |   0.848822 |
| k-d_tree_sklearn     |     0.759625 |       1.95935  |   0.881871 |
| barab-szabi-1        |     0.763415 |       0.880118 |   0.900712 |
| k-d_tree_pandas      |     0.752408 |       0.764126 |   1.13064  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.746848 |        5.63596 |   0.749433 |
| Bori_Aron_solution-1 |     0.74336  |       11.0371  |   0.792981 |
| k-d_tree_sklearn     |     0.745748 |       16.3744  |   1.09948  |
| k-d_tree_polars      |     0.770568 |        4.86959 |   6.78091  |
| k-d_tree_pandas      |     0.746408 |        3.84421 |   7.02048  |
| barab-szabi-1        |     0.763568 |        4.87668 |   7.08063  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06776  |        73.6336 |    4.09478 |
| k-d_tree_sklearn     |     0.852816 |       238.857  |    4.76242 |
| Bori_Aron_solution-1 |     0.74363  |       151.406  |   15.7684  |