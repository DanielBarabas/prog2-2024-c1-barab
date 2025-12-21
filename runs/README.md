# 2025-12-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510998 |       0.490621 |   0.427238 |
| k-d_tree_polars      |     0.535571 |       0.407752 |   0.434614 |
| solution-1           |     7.84627  |       1e-06    |   0.438385 |
| barab-szabi-1        |     0.543844 |       0.415572 |   0.447034 |
| Bori_Aron_solution-1 |     0.528949 |       0.559485 |   0.545643 |
| k-d_tree_pandas      |     9.73949  |       0.406824 |   0.630193 |
| k-d_tree_sklearn     |     3.2444   |       1.07203  |   1.05738  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527074 |       0.433654 |   0.428837 |
| barab-szabi-1        |     0.529478 |       0.414293 |   0.435198 |
| k-d_tree_polars      |     0.530328 |       0.427614 |   0.445413 |
| Bori_Aron_solution-1 |     0.532919 |       0.553342 |   0.551674 |
| k-d_tree_pandas      |     0.530621 |       0.389414 |   0.553605 |
| k-d_tree_sklearn     |     0.533072 |       0.977899 |   1.06629  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.537603 |       0.458463 |   0.462909 |
| barab-szabi-2        |     0.550131 |       0.460154 |   0.463209 |
| k-d_tree_polars      |     0.526978 |       0.435409 |   0.468386 |
| Bori_Aron_solution-1 |     0.523417 |       0.594245 |   0.552469 |
| k-d_tree_pandas      |     0.542321 |       0.413481 |   0.607753 |
| k-d_tree_sklearn     |     0.552317 |       1.05986  |   1.11622  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529275 |       0.508724 |   0.46807  |
| k-d_tree_polars      |     0.54213  |       0.559342 |   0.558295 |
| Bori_Aron_solution-1 |     0.527247 |       0.778514 |   0.5622   |
| barab-szabi-1        |     0.53451  |       0.568087 |   0.582098 |
| k-d_tree_pandas      |     0.527254 |       0.500269 |   0.739007 |
| k-d_tree_sklearn     |     0.533552 |       1.28192  |   1.16108  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541167 |       0.750451 |   0.527186 |
| Bori_Aron_solution-1 |     0.534678 |       1.47845  |   0.601558 |
| k-d_tree_polars      |     0.551088 |       0.923743 |   0.941543 |
| barab-szabi-1        |     0.546896 |       0.946469 |   0.999634 |
| k-d_tree_pandas      |     0.533669 |       0.816281 |   1.18079  |
| k-d_tree_sklearn     |     0.542749 |       2.22668  |   1.29496  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521249 |        5.4695  |   0.748394 |
| Bori_Aron_solution-1 |     0.518229 |       11.4215  |   0.832226 |
| k-d_tree_sklearn     |     0.5402   |       16.9421  |   1.39193  |
| barab-szabi-1        |     0.550389 |        5.38488 |   6.729    |
| k-d_tree_polars      |     0.524198 |        5.16629 |   6.74146  |
| k-d_tree_pandas      |     0.539978 |        4.42589 |   7.32314  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527465 |        76.6042 |    2.74212 |
| k-d_tree_sklearn     |     0.542837 |       237.287  |    4.23938 |
| Bori_Aron_solution-1 |     0.630174 |       152.324  |   16.5689  |