# 2026-11-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.72296  |       1e-06    |   0.300954 |
| barab-szabi-2        |     0.356846 |       0.355862 |   0.349914 |
| barab-szabi-1        |     0.356092 |       0.342216 |   0.362905 |
| k-d_tree_polars      |     8.11992  |       0.365854 |   0.387495 |
| k-d_tree_pandas      |     0.366739 |       0.329813 |   0.439822 |
| Bori_Aron_solution-1 |     0.354523 |       0.463825 |   0.448046 |
| k-d_tree_sklearn     |     2.43587  |       0.87552  |   0.96711  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.377867 |       0.36733  |   0.365996 |
| k-d_tree_polars      |     0.375231 |       0.37276  |   0.377334 |
| barab-szabi-1        |     0.369177 |       0.377065 |   0.383629 |
| Bori_Aron_solution-1 |     0.382543 |       0.470125 |   0.470094 |
| k-d_tree_pandas      |     0.381087 |       0.336062 |   0.478187 |
| k-d_tree_sklearn     |     0.383203 |       0.836099 |   0.944978 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.38811  |       0.381209 |   0.376352 |
| k-d_tree_polars      |     0.381437 |       0.415343 |   0.400665 |
| barab-szabi-1        |     0.37764  |       0.430075 |   0.402827 |
| Bori_Aron_solution-1 |     0.374823 |       0.509154 |   0.504482 |
| k-d_tree_pandas      |     0.375211 |       0.358203 |   0.506476 |
| k-d_tree_sklearn     |     0.390642 |       0.894837 |   0.968661 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.395397 |       0.447932 |   0.392438 |
| k-d_tree_polars      |     0.379577 |       0.491814 |   0.479423 |
| barab-szabi-1        |     0.374046 |       0.460813 |   0.480149 |
| Bori_Aron_solution-1 |     0.411966 |       0.688502 |   0.496711 |
| k-d_tree_pandas      |     0.382599 |       0.434086 |   0.704762 |
| k-d_tree_sklearn     |     0.363127 |       1.05419  |   0.947783 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360945 |       0.654285 |   0.448575 |
| Bori_Aron_solution-1 |     0.363544 |       1.19656  |   0.498559 |
| k-d_tree_polars      |     0.366574 |       0.720034 |   0.797187 |
| barab-szabi-1        |     0.358201 |       0.720396 |   0.864656 |
| k-d_tree_sklearn     |     0.359251 |       1.74666  |   0.967717 |
| k-d_tree_pandas      |     0.35757  |       0.625241 |   0.982933 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.389198 |        5.24579 |   0.756685 |
| Bori_Aron_solution-1 |     0.357134 |        9.76913 |   0.955883 |
| k-d_tree_sklearn     |     0.38832  |       16.3502  |   1.18383  |
| k-d_tree_polars      |     0.355427 |        4.54961 |   6.42036  |
| barab-szabi-1        |     0.388411 |        4.45712 |   6.64846  |
| k-d_tree_pandas      |     0.366188 |        3.2203  |   6.70603  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.535407 |       226.628  |    3.47069 |
| barab-szabi-2        |     0.553308 |        75.4815 |    3.6927  |
| Bori_Aron_solution-1 |     0.39824  |       149.33   |   24.1991  |