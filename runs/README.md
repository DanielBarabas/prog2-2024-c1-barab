# 2025-08-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     1.00675  |       0.399414 |   0.420821 |
| barab-szabi-2        |     8.68143  |       0.831368 |   0.424538 |
| barab-szabi-1        |     1.00108  |       0.408096 |   0.429528 |
| k-d_tree_pandas      |     1.01024  |       0.379983 |   0.541782 |
| Bori_Aron_solution-1 |     0.998341 |       0.544336 |   0.557425 |
| solution-1           |     7.78298  |       1e-06    |   0.636971 |
| k-d_tree_sklearn     |     3.95916  |       1.26227  |   1.05209  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.912575 |       0.425186 |   0.424207 |
| k-d_tree_polars      |     0.557307 |       0.411817 |   0.435489 |
| barab-szabi-1        |     0.569596 |       0.418778 |   0.442783 |
| k-d_tree_pandas      |     0.564399 |       0.390998 |   0.551485 |
| Bori_Aron_solution-1 |     0.553793 |       0.555267 |   0.563201 |
| k-d_tree_sklearn     |     0.559971 |       0.976061 |   1.06327  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561567 |       0.439182 |   0.451959 |
| barab-szabi-1        |     0.555558 |       0.431452 |   0.455834 |
| k-d_tree_polars      |     0.565877 |       0.438785 |   0.460041 |
| Bori_Aron_solution-1 |     0.556517 |       0.599345 |   0.552548 |
| k-d_tree_pandas      |     0.559583 |       0.412357 |   0.59929  |
| k-d_tree_sklearn     |     0.563207 |       1.02266  |   1.08468  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577748 |       0.504859 |   0.469693 |
| k-d_tree_polars      |     0.559789 |       0.561143 |   0.566266 |
| Bori_Aron_solution-1 |     0.553996 |       0.768952 |   0.5684   |
| barab-szabi-1        |     0.55172  |       0.564837 |   0.584801 |
| k-d_tree_pandas      |     0.559184 |       0.486273 |   0.738585 |
| k-d_tree_sklearn     |     0.559233 |       1.25769  |   1.14211  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553841 |       0.75467  |   0.508692 |
| Bori_Aron_solution-1 |     0.54736  |       1.41671  |   0.613229 |
| k-d_tree_polars      |     0.551559 |       0.887613 |   0.900351 |
| barab-szabi-1        |     0.558886 |       0.893175 |   0.948246 |
| k-d_tree_pandas      |     0.569594 |       0.767748 |   1.18262  |
| k-d_tree_sklearn     |     0.560829 |       2.13008  |   1.22215  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558882 |        5.33509 |   0.733326 |
| Bori_Aron_solution-1 |     0.556557 |       10.8018  |   0.851176 |
| k-d_tree_sklearn     |     0.559074 |       16.7689  |   1.34769  |
| k-d_tree_polars      |     0.570353 |        5.09351 |   6.75647  |
| barab-szabi-1        |     0.56018  |        5.06226 |   6.76648  |
| k-d_tree_pandas      |     0.571899 |        3.95933 |   7.11464  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563966 |        71.5399 |    2.63562 |
| k-d_tree_sklearn     |     0.771644 |       229.143  |    4.01559 |
| Bori_Aron_solution-1 |     0.56991  |       140.838  |   15.6738  |