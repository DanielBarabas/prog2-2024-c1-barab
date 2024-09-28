# 2024-09-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617339 |       0.390056 |   0.382792 |
| barab-szabi-1        |     0.634304 |       0.40777  |   0.39686  |
| Bori_Aron_solution-1 |     4.4951   |       0.829173 |   0.464054 |
| k-d_tree_polars      |     0.607687 |       0.432612 |   0.49774  |
| k-d_tree_pandas      |     4.30029  |       0.4614   |   0.52082  |
| solution-1           |     7.75862  |       1e-06    |   0.659724 |
| k-d_tree_sklearn     |     3.10374  |       1.24124  |   0.982167 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.623843 |       0.408083 |   0.390377 |
| barab-szabi-1        |     0.615365 |       0.452673 |   0.393619 |
| barab-szabi-2        |     0.617052 |       0.390563 |   0.400794 |
| Bori_Aron_solution-1 |     0.633388 |       0.538908 |   0.540505 |
| k-d_tree_pandas      |     0.627637 |       0.393895 |   0.573601 |
| k-d_tree_sklearn     |     0.619891 |       0.900598 |   0.976225 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.641153 |       0.454484 |   0.422847 |
| k-d_tree_polars      |     0.623522 |       0.430629 |   0.426873 |
| barab-szabi-2        |     0.612643 |       0.40858  |   0.44437  |
| Bori_Aron_solution-1 |     0.608176 |       0.601491 |   0.54396  |
| k-d_tree_pandas      |     0.627453 |       0.411709 |   0.579475 |
| k-d_tree_sklearn     |     0.62403  |       0.96269  |   0.991971 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617073 |       0.471235 |   0.439692 |
| k-d_tree_polars      |     0.632324 |       0.539574 |   0.518597 |
| barab-szabi-1        |     0.625598 |       0.538435 |   0.531305 |
| Bori_Aron_solution-1 |     0.616845 |       0.743049 |   0.539104 |
| k-d_tree_pandas      |     0.620643 |       0.485138 |   0.720857 |
| k-d_tree_sklearn     |     0.636734 |       1.19103  |   1.05059  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629445 |       0.713109 |   0.517465 |
| Bori_Aron_solution-1 |     0.618398 |       1.40467  |   0.572515 |
| k-d_tree_polars      |     0.624079 |       0.848245 |   0.866757 |
| barab-szabi-1        |     0.619995 |       0.856891 |   0.916406 |
| k-d_tree_sklearn     |     0.616517 |       2.00685  |   1.15545  |
| k-d_tree_pandas      |     0.623203 |       0.744361 |   1.16642  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631293 |        5.258   |   0.724086 |
| Bori_Aron_solution-1 |     0.617295 |       10.6531  |   0.825794 |
| k-d_tree_sklearn     |     0.619101 |       16.2219  |   1.28841  |
| k-d_tree_polars      |     0.627893 |        4.81153 |   6.60608  |
| barab-szabi-1        |     0.615664 |        4.80426 |   6.78376  |
| k-d_tree_pandas      |     0.627624 |        3.8413  |   7.01882  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.751598 |        73.7354 |    3.0726  |
| k-d_tree_sklearn     |     0.882877 |       233.118  |    4.37288 |
| Bori_Aron_solution-1 |     0.619787 |       148.021  |   17.0314  |