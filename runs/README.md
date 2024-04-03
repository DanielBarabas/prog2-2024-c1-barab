# 2024-04-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.719885 |       0.355346 |   0.339714 |
| barab-szabi-1        |     0.759532 |       0.414777 |   0.354621 |
| k-d_tree_polars      |     0.746888 |       0.425648 |   0.364506 |
| solution-1           |     8.67539  |       1e-06    |   0.377411 |
| Bori_Aron_solution-1 |     0.706564 |       0.490132 |   0.479999 |
| k-d_tree_pandas      |     8.47704  |       0.409301 |   0.485333 |
| k-d_tree_sklearn     |     3.33835  |       0.933993 |   0.667922 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.761987 |       0.417506 |   0.351146 |
| barab-szabi-2        |     0.748583 |       0.35383  |   0.352767 |
| barab-szabi-1        |     0.770392 |       0.422717 |   0.356884 |
| k-d_tree_pandas      |     0.75564  |       0.406305 |   0.499267 |
| Bori_Aron_solution-1 |     0.749018 |       0.495624 |   0.516454 |
| k-d_tree_sklearn     |     0.791756 |       0.89622  |   0.706742 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.769095 |       0.366746 |   0.362254 |
| k-d_tree_polars      |     0.754498 |       0.438484 |   0.3794   |
| barab-szabi-1        |     0.760626 |       0.430011 |   0.381732 |
| Bori_Aron_solution-1 |     0.746735 |       0.52937  |   0.501939 |
| k-d_tree_pandas      |     0.760282 |       0.413588 |   0.550957 |
| k-d_tree_sklearn     |     0.764614 |       0.893425 |   0.698897 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.748549 |       0.43479  |   0.392267 |
| k-d_tree_polars      |     0.765692 |       0.554872 |   0.482762 |
| Bori_Aron_solution-1 |     0.731869 |       0.706404 |   0.492651 |
| barab-szabi-1        |     0.746544 |       0.55153  |   0.498628 |
| k-d_tree_pandas      |     0.739774 |       0.486793 |   0.665658 |
| k-d_tree_sklearn     |     0.767433 |       1.1361   |   0.77939  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754397 |       0.686351 |   0.513217 |
| Bori_Aron_solution-1 |     0.753266 |       1.37692  |   0.528725 |
| k-d_tree_polars      |     0.752246 |       0.866036 |   0.833456 |
| k-d_tree_sklearn     |     0.757751 |       1.98218  |   0.863894 |
| barab-szabi-1        |     0.750158 |       0.868877 |   0.881184 |
| k-d_tree_pandas      |     0.771786 |       0.761329 |   1.10606  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744756 |        5.58816 |   0.743381 |
| Bori_Aron_solution-1 |     0.736575 |       11.0146  |   0.791612 |
| k-d_tree_sklearn     |     0.759868 |       16.6136  |   1.09246  |
| barab-szabi-1        |     0.77059  |        4.91071 |   6.78995  |
| k-d_tree_polars      |     0.752435 |        4.83873 |   6.87166  |
| k-d_tree_pandas      |     0.754029 |        3.85538 |   7.07132  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.752544 |         74.891 |    3.79686 |
| k-d_tree_sklearn     |     0.938809 |        233.752 |    4.87476 |
| Bori_Aron_solution-1 |     0.88939  |        148.257 |   14.0391  |