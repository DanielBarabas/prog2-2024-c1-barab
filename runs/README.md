# 2026-04-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4501   |       0.419049 |   0.421812 |
| k-d_tree_polars      |     0.45264  |       0.38981  |   0.423389 |
| solution-1           |     7.30147  |       1e-06    |   0.451771 |
| Bori_Aron_solution-1 |     0.444157 |       0.529752 |   0.529746 |
| k-d_tree_pandas      |     0.451727 |       0.381067 |   0.594421 |
| barab-szabi-1        |     7.78687  |       0.471567 |   0.682368 |
| k-d_tree_sklearn     |     2.85424  |       1.14169  |   1.04822  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451601 |       0.428237 |   0.425133 |
| k-d_tree_polars      |     0.451169 |       0.399978 |   0.428501 |
| barab-szabi-1        |     0.508531 |       0.398587 |   0.433131 |
| Bori_Aron_solution-1 |     0.451753 |       0.53944  |   0.528348 |
| k-d_tree_pandas      |     0.45026  |       0.378794 |   0.543586 |
| k-d_tree_sklearn     |     0.455055 |       0.94859  |   1.04483  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452012 |       0.435737 |   0.439455 |
| barab-szabi-1        |     0.451983 |       0.425086 |   0.453333 |
| k-d_tree_polars      |     0.454479 |       0.424902 |   0.454049 |
| Bori_Aron_solution-1 |     0.44619  |       0.581614 |   0.535482 |
| k-d_tree_pandas      |     0.451947 |       0.399166 |   0.584023 |
| k-d_tree_sklearn     |     0.454202 |       0.99532  |   1.05753  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449303 |       0.494922 |   0.462916 |
| Bori_Aron_solution-1 |     0.448662 |       0.770176 |   0.545962 |
| k-d_tree_polars      |     0.458563 |       0.551822 |   0.551749 |
| barab-szabi-1        |     0.452542 |       0.549851 |   0.565359 |
| k-d_tree_pandas      |     0.455609 |       0.492448 |   0.721357 |
| k-d_tree_sklearn     |     0.460034 |       1.23458  |   1.1119   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449841 |       0.714283 |   0.493937 |
| Bori_Aron_solution-1 |     0.44241  |       1.42094  |   0.56995  |
| k-d_tree_polars      |     0.451693 |       0.917995 |   0.896199 |
| barab-szabi-1        |     0.453594 |       0.918898 |   0.932851 |
| k-d_tree_pandas      |     0.454885 |       0.804235 |   1.15581  |
| k-d_tree_sklearn     |     0.452215 |       2.08367  |   1.18209  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.44784  |        4.74775 |   0.745048 |
| Bori_Aron_solution-1 |     0.458828 |       10.7139  |   0.7946   |
| k-d_tree_sklearn     |     0.453329 |       16.0605  |   1.26687  |
| k-d_tree_polars      |     0.447047 |        5.68398 |   6.24821  |
| barab-szabi-1        |     0.45164  |        5.66283 |   6.25232  |
| k-d_tree_pandas      |     0.453444 |        4.42317 |   6.65788  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.708482 |         70.666 |    2.72449 |
| k-d_tree_sklearn     |     0.456382 |        233     |    3.85057 |
| Bori_Aron_solution-1 |     0.452874 |        146.837 |   17.9615  |