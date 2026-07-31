# 2026-07-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492379 |       0.468738 |   0.4651   |
| barab-szabi-1        |     0.492797 |       0.43042  |   0.476425 |
| k-d_tree_pandas      |     0.48536  |       0.401702 |   0.566956 |
| k-d_tree_polars      |     8.50696  |       0.480409 |   0.603852 |
| Bori_Aron_solution-1 |     0.485754 |       0.60285  |   0.647811 |
| k-d_tree_sklearn     |     3.01103  |       1.16831  |   1.11177  |
| solution-1           |     8.2446   |       1e-06    |   1.21674  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482631 |       0.457327 |   0.455458 |
| k-d_tree_polars      |     0.498652 |       0.455659 |   0.470183 |
| barab-szabi-1        |     0.486444 |       0.447865 |   0.47376  |
| Bori_Aron_solution-1 |     0.488293 |       0.567566 |   0.574086 |
| k-d_tree_pandas      |     0.492472 |       0.414307 |   0.584795 |
| k-d_tree_sklearn     |     0.488566 |       1.07119  |   1.14134  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489305 |       0.485077 |   0.476373 |
| k-d_tree_polars      |     0.483837 |       0.477745 |   0.486995 |
| barab-szabi-1        |     0.495301 |       0.469029 |   0.502221 |
| Bori_Aron_solution-1 |     0.48901  |       0.628008 |   0.591792 |
| k-d_tree_pandas      |     0.492077 |       0.478742 |   0.620477 |
| k-d_tree_sklearn     |     0.480695 |       1.09895  |   1.16284  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490054 |       0.525705 |   0.499974 |
| k-d_tree_polars      |     0.487213 |       0.589511 |   0.572977 |
| barab-szabi-1        |     0.488472 |       0.601614 |   0.593291 |
| Bori_Aron_solution-1 |     0.478903 |       0.804115 |   0.59838  |
| k-d_tree_pandas      |     0.490776 |       0.518764 |   0.764138 |
| k-d_tree_sklearn     |     0.493596 |       1.33651  |   1.21931  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487556 |       0.759896 |   0.589494 |
| Bori_Aron_solution-1 |     0.482414 |       1.46155  |   0.606142 |
| k-d_tree_polars      |     0.482809 |       0.939713 |   0.947525 |
| barab-szabi-1        |     0.483957 |       0.937721 |   0.988498 |
| k-d_tree_pandas      |     0.494428 |       0.81029  |   1.20953  |
| k-d_tree_sklearn     |     0.480853 |       2.24026  |   1.25705  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488689 |        5.27909 |   0.7723   |
| Bori_Aron_solution-1 |     0.485615 |       11.1189  |   0.824867 |
| k-d_tree_sklearn     |     0.502702 |       17.1445  |   1.37314  |
| k-d_tree_polars      |     0.491422 |        5.36741 |   6.77509  |
| barab-szabi-1        |     0.503587 |        5.34081 |   6.85306  |
| k-d_tree_pandas      |     0.494767 |        4.39929 |   7.22522  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589842 |        76.0759 |    2.88075 |
| k-d_tree_sklearn     |     0.703597 |       242.78   |    4.26122 |
| Bori_Aron_solution-1 |     0.482152 |       154.164  |   25.5311  |