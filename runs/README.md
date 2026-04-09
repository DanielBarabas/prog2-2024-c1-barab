# 2026-04-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.46425  |       0.398737 |   0.4223   |
| barab-szabi-1        |     0.458105 |       0.397124 |   0.423367 |
| barab-szabi-2        |     0.450086 |       0.421988 |   0.426946 |
| solution-1           |     7.84516  |       1e-06    |   0.493413 |
| k-d_tree_pandas      |     0.468949 |       0.395261 |   0.550018 |
| Bori_Aron_solution-1 |     0.451352 |       0.533081 |   0.55104  |
| k-d_tree_sklearn     |    10.5844   |       1.40261  |   1.08064  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452582 |       0.423192 |   0.420935 |
| k-d_tree_polars      |     0.460198 |       0.410732 |   0.428626 |
| barab-szabi-1        |     0.459033 |       0.41215  |   0.432125 |
| k-d_tree_pandas      |     0.453944 |       0.389734 |   0.550374 |
| Bori_Aron_solution-1 |     0.45653  |       0.56431  |   0.574865 |
| k-d_tree_sklearn     |     0.471792 |       0.985291 |   1.06401  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45244  |       0.440325 |   0.436359 |
| k-d_tree_polars      |     0.454024 |       0.435738 |   0.45571  |
| barab-szabi-1        |     0.459673 |       0.441653 |   0.464037 |
| Bori_Aron_solution-1 |     0.45202  |       0.588581 |   0.534461 |
| k-d_tree_pandas      |     0.460087 |       0.411222 |   0.591142 |
| k-d_tree_sklearn     |     0.459342 |       1.02996  |   1.08888  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460025 |       0.504416 |   0.465852 |
| k-d_tree_polars      |     0.516283 |       0.563498 |   0.556338 |
| barab-szabi-1        |     0.45614  |       0.554341 |   0.564722 |
| Bori_Aron_solution-1 |     0.448889 |       0.792056 |   0.593368 |
| k-d_tree_pandas      |     0.458974 |       0.509669 |   0.725147 |
| k-d_tree_sklearn     |     0.462066 |       1.26591  |   1.11764  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457147 |       0.751783 |   0.527681 |
| Bori_Aron_solution-1 |     0.45315  |       1.51925  |   0.590266 |
| k-d_tree_polars      |     0.459512 |       0.914628 |   0.958833 |
| barab-szabi-1        |     0.456147 |       0.910194 |   0.982881 |
| k-d_tree_sklearn     |     0.457801 |       2.13481  |   1.14867  |
| k-d_tree_pandas      |     0.467505 |       0.787288 |   1.17905  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448414 |        5.57547 |    0.73219 |
| Bori_Aron_solution-1 |     0.454397 |       11.5328  |    0.7962  |
| k-d_tree_sklearn     |     0.464694 |       17.3888  |    1.21807 |
| barab-szabi-1        |     0.453652 |        5.42107 |    7.42583 |
| k-d_tree_polars      |     0.460907 |        5.16596 |    7.45714 |
| k-d_tree_pandas      |     0.455497 |        4.10316 |    7.74768 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.748985 |         77.978 |    2.42181 |
| k-d_tree_sklearn     |     0.45885  |        265.542 |    3.2479  |
| Bori_Aron_solution-1 |     0.462061 |        163.05  |   12.1311  |