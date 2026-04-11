# 2026-04-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63079  |       1e-06    |   0.416077 |
| barab-szabi-1        |     0.46843  |       0.404267 |   0.432713 |
| k-d_tree_polars      |     0.463905 |       0.416587 |   0.433834 |
| barab-szabi-2        |     0.465224 |       0.437341 |   0.439951 |
| Bori_Aron_solution-1 |     0.44958  |       0.552635 |   0.553793 |
| k-d_tree_pandas      |     0.462613 |       0.392783 |   0.561866 |
| k-d_tree_sklearn     |    10.1963   |       1.33939  |   1.112    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.468073 |       0.417481 |   0.449789 |
| barab-szabi-2        |     0.479362 |       0.456661 |   0.4554   |
| k-d_tree_polars      |     0.484255 |       0.437643 |   0.456306 |
| k-d_tree_pandas      |     0.476436 |       0.41384  |   0.56816  |
| Bori_Aron_solution-1 |     0.464472 |       0.609247 |   0.617956 |
| k-d_tree_sklearn     |     0.466404 |       1.01368  |   1.11514  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475795 |       0.446905 |   0.439306 |
| barab-szabi-1        |     0.473867 |       0.444898 |   0.454226 |
| k-d_tree_polars      |     0.474187 |       0.435245 |   0.456735 |
| Bori_Aron_solution-1 |     0.475444 |       0.667771 |   0.584324 |
| k-d_tree_pandas      |     0.462053 |       0.424901 |   0.601119 |
| k-d_tree_sklearn     |     0.487315 |       1.12064  |   1.14613  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467016 |       0.50423  |   0.462836 |
| Bori_Aron_solution-1 |     0.457642 |       0.789572 |   0.569447 |
| k-d_tree_polars      |     0.460899 |       0.54346  |   0.572654 |
| barab-szabi-1        |     0.465484 |       0.563087 |   0.577721 |
| k-d_tree_pandas      |     0.455442 |       0.502245 |   0.720141 |
| k-d_tree_sklearn     |     0.459286 |       1.27109  |   1.20716  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460416 |       0.736086 |   0.500233 |
| Bori_Aron_solution-1 |     0.44719  |       1.45852  |   0.565855 |
| k-d_tree_polars      |     0.460531 |       0.910725 |   0.946639 |
| barab-szabi-1        |     0.455719 |       0.917536 |   0.976001 |
| k-d_tree_sklearn     |     0.475299 |       2.13115  |   1.14073  |
| k-d_tree_pandas      |     0.453445 |       0.783144 |   1.16284  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487705 |        5.57496 |   0.736868 |
| Bori_Aron_solution-1 |     0.463706 |       11.4232  |   0.796858 |
| k-d_tree_sklearn     |     0.456228 |       17.1056  |   1.28078  |
| barab-szabi-1        |     0.474323 |        5.31134 |   7.35729  |
| k-d_tree_polars      |     0.467509 |        5.54253 |   7.50881  |
| k-d_tree_pandas      |     0.468163 |        4.18989 |   7.79935  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731886 |        77.0769 |    2.46194 |
| k-d_tree_sklearn     |     0.467988 |       264.576  |    3.3684  |
| Bori_Aron_solution-1 |     0.458495 |       157.951  |   24.2345  |