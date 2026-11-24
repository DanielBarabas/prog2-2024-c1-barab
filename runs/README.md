# 2026-11-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.91197  |       1e-06    |   0.330568 |
| barab-szabi-2        |     0.362808 |       0.347039 |   0.344432 |
| k-d_tree_polars      |     0.362219 |       0.345873 |   0.349267 |
| barab-szabi-1        |     0.353873 |       0.34693  |   0.349666 |
| Bori_Aron_solution-1 |     3.78647  |       0.510911 |   0.391297 |
| k-d_tree_pandas      |     0.361974 |       0.308424 |   0.43848  |
| k-d_tree_sklearn     |     6.14513  |       0.836893 |   0.879891 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359626 |       0.354419 |   0.346988 |
| k-d_tree_polars      |     0.357917 |       0.355298 |   0.356022 |
| barab-szabi-1        |     0.365328 |       0.342405 |   0.358165 |
| k-d_tree_pandas      |     0.356822 |       0.320476 |   0.446715 |
| Bori_Aron_solution-1 |     0.357963 |       0.448567 |   0.447065 |
| k-d_tree_sklearn     |     0.361079 |       0.809267 |   0.876784 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359635 |       0.365373 |   0.358537 |
| barab-szabi-1        |     0.362855 |       0.36797  |   0.38584  |
| k-d_tree_polars      |     0.364765 |       0.390868 |   0.387182 |
| k-d_tree_pandas      |     0.358989 |       0.329892 |   0.47437  |
| Bori_Aron_solution-1 |     0.353746 |       0.50963  |   0.475257 |
| k-d_tree_sklearn     |     0.368805 |       0.845104 |   0.88392  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364212 |       0.440876 |   0.385422 |
| Bori_Aron_solution-1 |     0.35584  |       0.640265 |   0.460695 |
| barab-szabi-1        |     0.363452 |       0.463197 |   0.46872  |
| k-d_tree_polars      |     0.359958 |       0.452092 |   0.473622 |
| k-d_tree_pandas      |     0.363226 |       0.411685 |   0.57253  |
| k-d_tree_sklearn     |     0.361784 |       1.03635  |   0.934874 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360725 |       0.655466 |   0.479478 |
| Bori_Aron_solution-1 |     0.354926 |       1.1975   |   0.506992 |
| k-d_tree_polars      |     0.358166 |       0.722368 |   0.778042 |
| barab-szabi-1        |     0.360867 |       0.71294  |   0.82116  |
| k-d_tree_pandas      |     0.361512 |       0.627807 |   0.962231 |
| k-d_tree_sklearn     |     0.361229 |       1.74301  |   0.975232 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.358263 |        4.81374 |   0.727632 |
| Bori_Aron_solution-1 |     0.35506  |        9.36013 |   0.898626 |
| k-d_tree_sklearn     |     0.358477 |       14.7098  |   1.07378  |
| k-d_tree_polars      |     0.353821 |        4.45767 |   6.1684   |
| barab-szabi-1        |     0.364136 |        4.57393 |   6.19858  |
| k-d_tree_pandas      |     0.361705 |        3.20958 |   6.44238  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.566748 |       221.784  |    3.24507 |
| barab-szabi-2        |     0.438274 |        71.7947 |    3.55014 |
| Bori_Aron_solution-1 |     0.356497 |       148.103  |   22.2146  |