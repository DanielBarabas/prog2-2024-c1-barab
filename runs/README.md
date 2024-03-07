# 2024-03-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.735237 |       0.401267 |   0.365862 |
| solution-1           |     8.15704  |       1e-06    |   0.371487 |
| barab-szabi-2        |     0.740247 |       0.363665 |   0.398759 |
| k-d_tree_polars      |     8.28413  |       0.423442 |   0.40939  |
| Bori_Aron_solution-1 |     0.727374 |       0.508571 |   0.50572  |
| k-d_tree_pandas      |     0.757062 |       0.403276 |   0.519254 |
| k-d_tree_sklearn     |     3.19871  |       0.902089 |   0.690408 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732354 |       0.371586 |   0.363498 |
| k-d_tree_polars      |     0.749195 |       0.41489  |   0.370459 |
| barab-szabi-1        |     0.734338 |       0.410727 |   0.370901 |
| Bori_Aron_solution-1 |     0.725296 |       0.508667 |   0.507042 |
| k-d_tree_pandas      |     0.741945 |       0.390316 |   0.518502 |
| k-d_tree_sklearn     |     0.738953 |       0.858946 |   0.686877 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734713 |       0.38452  |   0.377935 |
| barab-szabi-1        |     0.746308 |       0.443602 |   0.398065 |
| k-d_tree_polars      |     0.744462 |       0.45584  |   0.409194 |
| Bori_Aron_solution-1 |     0.728253 |       0.554123 |   0.513722 |
| k-d_tree_pandas      |     0.735403 |       0.411718 |   0.559437 |
| k-d_tree_sklearn     |     0.756167 |       0.955588 |   0.715871 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.746953 |       0.447796 |   0.412335 |
| k-d_tree_polars      |     0.737897 |       0.554244 |   0.493633 |
| barab-szabi-1        |     0.75925  |       0.574183 |   0.535553 |
| Bori_Aron_solution-1 |     0.734234 |       0.770572 |   0.556578 |
| k-d_tree_pandas      |     0.756231 |       0.527896 |   0.732967 |
| k-d_tree_sklearn     |     0.754063 |       1.18139  |   0.791047 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733306 |       0.688436 |   0.453373 |
| Bori_Aron_solution-1 |     0.731868 |       1.3773   |   0.540257 |
| barab-szabi-1        |     0.734414 |       0.858668 |   0.871265 |
| k-d_tree_polars      |     0.765452 |       0.897542 |   0.878653 |
| k-d_tree_sklearn     |     0.761539 |       2.04193  |   0.887246 |
| k-d_tree_pandas      |     0.732541 |       0.761896 |   1.12252  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743297 |        5.28056 |   0.753873 |
| Bori_Aron_solution-1 |     0.742234 |       10.7511  |   0.787271 |
| k-d_tree_sklearn     |     0.73273  |       16.1332  |   1.06396  |
| barab-szabi-1        |     0.731828 |        4.94166 |   6.50554  |
| k-d_tree_polars      |     0.736495 |        5.00178 |   6.64864  |
| k-d_tree_pandas      |     0.728224 |        3.96583 |   6.83721  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.933613 |        72.2981 |    3.5573  |
| k-d_tree_sklearn     |     0.729472 |       235.702  |    5.22925 |
| Bori_Aron_solution-1 |     0.860845 |       147.669  |   17.6388  |