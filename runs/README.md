# 2026-05-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484963 |       0.433565 |   0.440545 |
| k-d_tree_polars      |     0.462999 |       0.406075 |   0.442995 |
| solution-1           |     7.30528  |       1e-06    |   0.454569 |
| Bori_Aron_solution-1 |     0.465388 |       0.544106 |   0.54339  |
| k-d_tree_pandas      |     0.466498 |       0.384792 |   0.556896 |
| barab-szabi-1        |     8.06158  |       0.528015 |   0.584281 |
| k-d_tree_sklearn     |     2.9211   |       1.12612  |   1.0803   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475909 |       0.445445 |   0.443881 |
| k-d_tree_polars      |     0.47433  |       0.411087 |   0.444874 |
| barab-szabi-1        |     0.470262 |       0.417152 |   0.453828 |
| Bori_Aron_solution-1 |     0.463161 |       0.550044 |   0.539943 |
| k-d_tree_pandas      |     0.478403 |       0.392635 |   0.559885 |
| k-d_tree_sklearn     |     0.480638 |       0.9696   |   1.06051  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47865  |       0.451512 |   0.447855 |
| k-d_tree_polars      |     0.470415 |       0.437748 |   0.469431 |
| barab-szabi-1        |     0.468425 |       0.444692 |   0.476417 |
| Bori_Aron_solution-1 |     0.475163 |       0.591469 |   0.554656 |
| k-d_tree_pandas      |     0.471855 |       0.406244 |   0.624547 |
| k-d_tree_sklearn     |     0.505641 |       1.03211  |   1.08607  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473135 |       0.516702 |   0.492186 |
| k-d_tree_polars      |     0.488538 |       0.558095 |   0.563489 |
| Bori_Aron_solution-1 |     0.471301 |       0.800169 |   0.564416 |
| barab-szabi-1        |     0.469232 |       0.570709 |   0.57556  |
| k-d_tree_pandas      |     0.469567 |       0.49926  |   0.740202 |
| k-d_tree_sklearn     |     0.484794 |       1.29704  |   1.19192  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494399 |       0.79383  |   0.588377 |
| Bori_Aron_solution-1 |     0.49102  |       1.53146  |   0.620968 |
| k-d_tree_polars      |     0.494087 |       0.961094 |   0.963103 |
| barab-szabi-1        |     0.477476 |       0.951715 |   0.999936 |
| k-d_tree_sklearn     |     0.513096 |       2.24678  |   1.28174  |
| k-d_tree_pandas      |     0.508707 |       0.821334 |   1.29713  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486684 |        5.23668 |   0.759902 |
| Bori_Aron_solution-1 |     0.479568 |       11.2758  |   0.819063 |
| k-d_tree_sklearn     |     0.478889 |       17.3703  |   1.35835  |
| barab-szabi-1        |     0.523362 |        5.55128 |   6.5729   |
| k-d_tree_polars      |     0.462714 |        5.50337 |   6.7817   |
| k-d_tree_pandas      |     0.472843 |        4.49564 |   7.23324  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48452  |        71.7665 |    2.63533 |
| k-d_tree_sklearn     |     0.507134 |       246.503  |    3.7872  |
| Bori_Aron_solution-1 |     0.494995 |       158.4    |   14.2731  |