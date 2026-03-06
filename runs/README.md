# 2026-03-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.61412  |       1e-06    |   0.42894  |
| barab-szabi-2        |     0.490801 |       0.447396 |   0.437373 |
| k-d_tree_polars      |     0.488008 |       0.413652 |   0.45358  |
| Bori_Aron_solution-1 |     0.479228 |       0.550473 |   0.559787 |
| k-d_tree_pandas      |     0.491667 |       0.393136 |   0.562535 |
| barab-szabi-1        |     7.95484  |       0.451455 |   0.607485 |
| k-d_tree_sklearn     |     2.94223  |       1.1074   |   1.10696  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497985 |       0.452652 |   0.437145 |
| barab-szabi-1        |     0.498568 |       0.416161 |   0.444415 |
| k-d_tree_polars      |     0.505142 |       0.428942 |   0.454738 |
| Bori_Aron_solution-1 |     0.490511 |       0.570603 |   0.560209 |
| k-d_tree_pandas      |     0.521081 |       0.418377 |   0.561495 |
| k-d_tree_sklearn     |     0.507162 |       0.986933 |   1.08866  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505626 |       0.455117 |   0.448302 |
| barab-szabi-1        |     0.496936 |       0.451131 |   0.473532 |
| k-d_tree_polars      |     0.497533 |       0.459776 |   0.483209 |
| Bori_Aron_solution-1 |     0.491327 |       0.610491 |   0.563463 |
| k-d_tree_pandas      |     0.498776 |       0.422467 |   0.620503 |
| k-d_tree_sklearn     |     0.499592 |       1.04696  |   1.12324  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515082 |       0.531803 |   0.496908 |
| k-d_tree_polars      |     0.500304 |       0.564766 |   0.565526 |
| barab-szabi-1        |     0.502218 |       0.576151 |   0.579999 |
| Bori_Aron_solution-1 |     0.494397 |       0.795444 |   0.580634 |
| k-d_tree_pandas      |     0.501609 |       0.509128 |   0.742571 |
| k-d_tree_sklearn     |     0.493278 |       1.28758  |   1.15062  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501472 |       0.741154 |   0.515879 |
| Bori_Aron_solution-1 |     0.491607 |       1.47238  |   0.59844  |
| k-d_tree_polars      |     0.498331 |       0.942407 |   0.92962  |
| barab-szabi-1        |     0.497304 |       0.940341 |   0.988543 |
| k-d_tree_pandas      |     0.498948 |       0.826461 |   1.20074  |
| k-d_tree_sklearn     |     0.499797 |       2.17263  |   1.22604  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506861 |        5.20661 |   0.758675 |
| Bori_Aron_solution-1 |     0.485242 |       11.0307  |   0.827039 |
| k-d_tree_sklearn     |     0.509065 |       17.0933  |   1.33198  |
| k-d_tree_polars      |     0.490142 |        5.56478 |   6.48854  |
| barab-szabi-1        |     0.496649 |        5.51999 |   6.74899  |
| k-d_tree_pandas      |     0.49383  |        4.42864 |   7.11094  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.508413 |        86.5567 |    3.02272 |
| k-d_tree_sklearn     |     0.739493 |       258.201  |    4.19862 |
| Bori_Aron_solution-1 |     0.507413 |       151.985  |   14.6287  |