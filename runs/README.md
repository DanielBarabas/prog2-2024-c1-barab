# 2026-06-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.59953  |       1e-06    |   0.425801 |
| barab-szabi-2        |     0.471338 |       0.455145 |   0.457181 |
| k-d_tree_polars      |     0.481866 |       0.420884 |   0.467934 |
| Bori_Aron_solution-1 |     0.481622 |       0.571144 |   0.568685 |
| barab-szabi-1        |     8.32818  |       0.461244 |   0.591528 |
| k-d_tree_pandas      |     0.482759 |       0.392839 |   0.643748 |
| k-d_tree_sklearn     |     3.09842  |       1.20362  |   1.13448  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.481523 |       0.415904 |   0.45487  |
| barab-szabi-1        |     0.499513 |       0.424947 |   0.459625 |
| barab-szabi-2        |     0.491382 |       0.454662 |   0.467659 |
| Bori_Aron_solution-1 |     0.478073 |       0.567532 |   0.563777 |
| k-d_tree_pandas      |     0.487712 |       0.405859 |   0.589993 |
| k-d_tree_sklearn     |     0.487759 |       1.00604  |   1.14314  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487463 |       0.465775 |   0.494995 |
| k-d_tree_polars      |     0.498289 |       0.470447 |   0.496263 |
| barab-szabi-1        |     0.506145 |       0.464161 |   0.49835  |
| Bori_Aron_solution-1 |     0.491968 |       0.633497 |   0.586709 |
| k-d_tree_pandas      |     0.495342 |       0.426936 |   0.662697 |
| k-d_tree_sklearn     |     0.507811 |       1.11578  |   1.19982  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507907 |       0.537549 |   0.500451 |
| Bori_Aron_solution-1 |     0.48622  |       0.814113 |   0.593716 |
| k-d_tree_polars      |     0.502268 |       0.605588 |   0.610158 |
| barab-szabi-1        |     0.505295 |       0.614108 |   0.617051 |
| k-d_tree_pandas      |     0.499352 |       0.533351 |   0.768863 |
| k-d_tree_sklearn     |     0.508093 |       1.35862  |   1.25617  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499983 |       0.756802 |   0.58961  |
| Bori_Aron_solution-1 |     0.481375 |       1.48419  |   0.617937 |
| k-d_tree_polars      |     0.4894   |       0.946445 |   0.95151  |
| barab-szabi-1        |     0.507359 |       0.963873 |   1.01781  |
| k-d_tree_pandas      |     0.497632 |       0.82975  |   1.21851  |
| k-d_tree_sklearn     |     0.500173 |       2.23101  |   1.2981   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499576 |        5.62519 |   0.808424 |
| Bori_Aron_solution-1 |     0.497001 |       11.396   |   0.845301 |
| k-d_tree_sklearn     |     0.511016 |       17.6278  |   1.33151  |
| barab-szabi-1        |     0.496264 |        5.542   |   7.00411  |
| k-d_tree_polars      |     0.481633 |        5.52714 |   7.14083  |
| k-d_tree_pandas      |     0.516052 |        4.55958 |   7.58169  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479431 |        72.1866 |    2.87548 |
| k-d_tree_sklearn     |     0.681388 |       241.645  |    4.03643 |
| Bori_Aron_solution-1 |     0.468384 |       155.645  |   16.8233  |