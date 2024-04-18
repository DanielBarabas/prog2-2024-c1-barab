# 2024-04-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.721408 |       0.39988  |   0.33895  |
| barab-szabi-2        |     0.706625 |       0.361449 |   0.341037 |
| barab-szabi-1        |     8.68433  |       0.421286 |   0.363324 |
| solution-1           |     7.94502  |       1e-06    |   0.369063 |
| k-d_tree_pandas      |     0.717183 |       0.391144 |   0.486393 |
| Bori_Aron_solution-1 |     0.721634 |       0.48055  |   0.506337 |
| k-d_tree_sklearn     |     3.29531  |       0.909593 |   0.655906 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.748489 |       0.360067 |   0.340827 |
| barab-szabi-1        |     0.749403 |       0.437139 |   0.355937 |
| k-d_tree_polars      |     0.739969 |       0.463888 |   0.451928 |
| Bori_Aron_solution-1 |     0.746955 |       0.489895 |   0.48146  |
| k-d_tree_pandas      |     0.727941 |       0.389938 |   0.498378 |
| k-d_tree_sklearn     |     0.749181 |       0.871913 |   0.699952 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735898 |       0.373083 |   0.367626 |
| barab-szabi-1        |     0.744829 |       0.43704  |   0.374161 |
| k-d_tree_polars      |     0.757979 |       0.432767 |   0.379904 |
| Bori_Aron_solution-1 |     0.725647 |       0.52164  |   0.4774   |
| k-d_tree_pandas      |     0.733227 |       0.405565 |   0.571561 |
| k-d_tree_sklearn     |     0.746583 |       0.925177 |   0.71197  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.777385 |       0.441515 |   0.408145 |
| barab-szabi-1        |     0.736311 |       0.537858 |   0.484262 |
| k-d_tree_polars      |     0.743187 |       0.565324 |   0.496693 |
| Bori_Aron_solution-1 |     0.737771 |       0.713024 |   0.507418 |
| k-d_tree_pandas      |     0.763608 |       0.502258 |   0.685796 |
| k-d_tree_sklearn     |     0.759995 |       1.12949  |   0.772644 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745898 |       0.6835   |   0.452864 |
| Bori_Aron_solution-1 |     0.748169 |       1.37309  |   0.515288 |
| k-d_tree_polars      |     0.74998  |       0.860138 |   0.845406 |
| barab-szabi-1        |     0.741705 |       0.863478 |   0.866551 |
| k-d_tree_sklearn     |     0.759668 |       1.99696  |   0.875303 |
| k-d_tree_pandas      |     0.750481 |       0.767626 |   1.11375  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73568  |        5.29477 |   0.730749 |
| Bori_Aron_solution-1 |     0.717472 |       10.6093  |   0.765503 |
| k-d_tree_sklearn     |     0.74045  |       15.6109  |   1.03597  |
| barab-szabi-1        |     0.734397 |        4.82744 |   6.52159  |
| k-d_tree_polars      |     0.730867 |        4.83827 |   6.60278  |
| k-d_tree_pandas      |     0.729186 |        3.88021 |   6.79821  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.976139 |        71.7557 |    3.87647 |
| k-d_tree_sklearn     |     0.794149 |       228.019  |    4.82877 |
| Bori_Aron_solution-1 |     0.719878 |       146.471  |   17.0255  |