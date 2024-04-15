# 2024-04-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.811644 |       0.372946 |   0.371521 |
| barab-szabi-1        |     0.792892 |       0.452803 |   0.394543 |
| Bori_Aron_solution-1 |     0.784946 |       0.545599 |   0.524793 |
| k-d_tree_pandas      |     0.802497 |       0.430283 |   0.550487 |
| k-d_tree_polars      |    10.5002   |       0.616163 |   0.65968  |
| k-d_tree_sklearn     |     3.58838  |       1.5481   |   0.722678 |
| solution-1           |     9.91269  |       1e-06    |   0.88647  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.788404 |       0.45081  |   0.377536 |
| barab-szabi-2        |     0.771266 |       0.368557 |   0.377569 |
| barab-szabi-1        |     0.786865 |       0.443151 |   0.379178 |
| Bori_Aron_solution-1 |     0.767022 |       0.540011 |   0.522984 |
| k-d_tree_pandas      |     0.779199 |       0.421478 |   0.531356 |
| k-d_tree_sklearn     |     0.794528 |       0.938326 |   0.726453 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785925 |       0.417258 |   0.371236 |
| k-d_tree_polars      |     0.789047 |       0.477764 |   0.40117  |
| barab-szabi-1        |     0.789701 |       0.459729 |   0.402951 |
| Bori_Aron_solution-1 |     0.764562 |       0.570754 |   0.522841 |
| k-d_tree_pandas      |     0.812375 |       0.443476 |   0.582782 |
| k-d_tree_sklearn     |     0.803478 |       0.989841 |   0.770909 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789524 |       0.458519 |   0.421217 |
| k-d_tree_polars      |     0.791583 |       0.586522 |   0.510922 |
| barab-szabi-1        |     0.779801 |       0.581537 |   0.523793 |
| Bori_Aron_solution-1 |     0.75669  |       0.752997 |   0.554725 |
| k-d_tree_pandas      |     0.782943 |       0.514591 |   0.718842 |
| k-d_tree_sklearn     |     0.78633  |       1.22814  |   0.823472 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785355 |       0.721885 |   0.544395 |
| Bori_Aron_solution-1 |     0.759009 |       1.44991  |   0.55965  |
| k-d_tree_polars      |     0.778658 |       0.902276 |   0.896762 |
| barab-szabi-1        |     0.776142 |       0.898309 |   0.924594 |
| k-d_tree_sklearn     |     0.805126 |       2.15468  |   0.933822 |
| k-d_tree_pandas      |     0.797295 |       0.780271 |   1.18144  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.799392 |        5.68745 |   0.776308 |
| Bori_Aron_solution-1 |     0.791242 |       11.0099  |   0.826338 |
| k-d_tree_sklearn     |     0.806421 |       17.4616  |   1.14465  |
| k-d_tree_polars      |     0.779698 |        4.96203 |   6.76139  |
| barab-szabi-1        |     0.810508 |        4.94136 |   7.10064  |
| k-d_tree_pandas      |     0.777397 |        3.88014 |   7.26457  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.824461 |        74.1321 |    3.54027 |
| k-d_tree_sklearn     |     0.829939 |       236.76   |    5.22108 |
| Bori_Aron_solution-1 |     0.803063 |       144.969  |   17.2238  |