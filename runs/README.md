# 2024-05-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.63868  |       0.389226 |   0.341981 |
| barab-szabi-1        |     0.793339 |       0.418719 |   0.351912 |
| k-d_tree_polars      |     0.793718 |       0.416678 |   0.354432 |
| Bori_Aron_solution-1 |     4.90493  |       0.410301 |   0.410886 |
| k-d_tree_pandas      |     0.799282 |       0.394227 |   0.493136 |
| solution-1           |     9.05934  |       1e-06    |   0.500627 |
| k-d_tree_sklearn     |     3.55455  |       1.16191  |   0.676832 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.780653 |       0.355216 |   0.341107 |
| k-d_tree_polars      |     0.794379 |       0.434368 |   0.353583 |
| barab-szabi-1        |     0.789525 |       0.424273 |   0.359063 |
| Bori_Aron_solution-1 |     0.775512 |       0.493082 |   0.478276 |
| k-d_tree_pandas      |     0.791958 |       0.391011 |   0.491526 |
| k-d_tree_sklearn     |     0.786631 |       0.84899  |   0.669909 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794876 |       0.368808 |   0.356282 |
| k-d_tree_polars      |     0.807813 |       0.460996 |   0.388077 |
| barab-szabi-1        |     0.794976 |       0.444396 |   0.393025 |
| Bori_Aron_solution-1 |     0.77338  |       0.555462 |   0.477837 |
| k-d_tree_pandas      |     0.788023 |       0.408704 |   0.532813 |
| k-d_tree_sklearn     |     0.789485 |       0.897162 |   0.71992  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.803165 |       0.468279 |   0.430351 |
| barab-szabi-1        |     0.790015 |       0.55234  |   0.492355 |
| k-d_tree_polars      |     0.786298 |       0.559307 |   0.49518  |
| Bori_Aron_solution-1 |     0.803548 |       0.709555 |   0.515708 |
| k-d_tree_pandas      |     0.782967 |       0.507269 |   0.660683 |
| k-d_tree_sklearn     |     0.861734 |       1.14767  |   0.759934 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789122 |       0.70113  |   0.449758 |
| Bori_Aron_solution-1 |     0.770974 |       1.37295  |   0.519842 |
| k-d_tree_polars      |     0.779868 |       0.877789 |   0.82372  |
| k-d_tree_sklearn     |     0.807303 |       1.98373  |   0.852042 |
| barab-szabi-1        |     0.782946 |       0.875511 |   0.862573 |
| k-d_tree_pandas      |     0.788656 |       0.766248 |   1.09393  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789308 |        5.44105 |   0.770567 |
| Bori_Aron_solution-1 |     0.773952 |       10.8625  |   0.783251 |
| k-d_tree_sklearn     |     0.788059 |       16.9057  |   1.07481  |
| k-d_tree_polars      |     0.788964 |        5.00123 |   6.70122  |
| k-d_tree_pandas      |     0.809942 |        4.03154 |   6.95506  |
| barab-szabi-1        |     0.79057  |        5.04138 |   7.13422  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02225  |        79.3442 |    3.81556 |
| k-d_tree_sklearn     |     0.960453 |       240.836  |    4.89421 |
| Bori_Aron_solution-1 |     0.775569 |       162.343  |   17.2076  |