# 2024-04-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72291  |       0.337399 |   0.333461 |
| barab-szabi-1        |     0.727062 |       0.389796 |   0.336652 |
| k-d_tree_polars      |     8.5693   |       0.428537 |   0.352363 |
| solution-1           |     7.83466  |       1e-06    |   0.370869 |
| Bori_Aron_solution-1 |     0.717543 |       0.462199 |   0.464029 |
| k-d_tree_pandas      |     0.694654 |       0.373948 |   0.47441  |
| k-d_tree_sklearn     |     3.33434  |       0.88181  |   0.644053 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735164 |       0.353173 |   0.339322 |
| k-d_tree_polars      |     0.732051 |       0.401763 |   0.343788 |
| barab-szabi-1        |     0.728358 |       0.398791 |   0.345042 |
| Bori_Aron_solution-1 |     0.709077 |       0.474959 |   0.465312 |
| k-d_tree_pandas      |     0.728086 |       0.382411 |   0.477258 |
| k-d_tree_sklearn     |     0.731021 |       0.818839 |   0.656689 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745666 |       0.362636 |   0.351379 |
| barab-szabi-1        |     0.722839 |       0.42601  |   0.371795 |
| k-d_tree_polars      |     0.724521 |       0.425797 |   0.373734 |
| Bori_Aron_solution-1 |     0.718211 |       0.513558 |   0.466358 |
| k-d_tree_pandas      |     0.723566 |       0.398591 |   0.520649 |
| k-d_tree_sklearn     |     0.740022 |       0.868508 |   0.680136 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726228 |       0.425855 |   0.387254 |
| k-d_tree_polars      |     0.733771 |       0.53041  |   0.469034 |
| barab-szabi-1        |     0.733503 |       0.53198  |   0.476905 |
| Bori_Aron_solution-1 |     0.717394 |       0.693646 |   0.483525 |
| k-d_tree_pandas      |     0.748786 |       0.47869  |   0.651272 |
| k-d_tree_sklearn     |     0.739042 |       1.11654  |   0.74315  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.722429 |       0.670208 |   0.421093 |
| Bori_Aron_solution-1 |     0.720473 |       1.32519  |   0.507848 |
| k-d_tree_polars      |     0.732012 |       0.860526 |   0.814935 |
| k-d_tree_sklearn     |     0.732978 |       1.89424  |   0.84215  |
| barab-szabi-1        |     0.727698 |       0.8491   |   0.848298 |
| k-d_tree_pandas      |     0.725517 |       0.744627 |   1.07357  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.720011 |        5.44323 |   0.731663 |
| Bori_Aron_solution-1 |     0.718493 |       10.7352  |   0.774055 |
| k-d_tree_sklearn     |     0.732099 |       15.8904  |   1.04301  |
| k-d_tree_polars      |     0.734521 |        4.83248 |   6.633    |
| barab-szabi-1        |     0.732503 |        4.81135 |   6.66775  |
| k-d_tree_pandas      |     0.732457 |        3.83744 |   6.99026  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791996 |        74.7463 |    3.55828 |
| k-d_tree_sklearn     |     0.734593 |       234.247  |    5.04422 |
| Bori_Aron_solution-1 |     0.76541  |       144.333  |   17.6767  |