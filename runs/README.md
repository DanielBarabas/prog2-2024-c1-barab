# 2025-01-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573838 |       0.455375 |   0.398932 |
| k-d_tree_polars      |     0.5833   |       0.39926  |   0.399096 |
| barab-szabi-1        |     0.577769 |       0.402805 |   0.407893 |
| solution-1           |     9.12643  |       1e-06    |   0.422076 |
| Bori_Aron_solution-1 |     0.574846 |       0.52141  |   0.522217 |
| k-d_tree_pandas      |     8.19808  |       0.415834 |   0.668492 |
| k-d_tree_sklearn     |     3.95157  |       1.06076  |   1.0091   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58006  |       0.402837 |   0.397208 |
| k-d_tree_polars      |     0.586611 |       0.406849 |   0.401009 |
| barab-szabi-1        |     0.582651 |       0.403303 |   0.403178 |
| Bori_Aron_solution-1 |     0.572443 |       0.527047 |   0.525831 |
| k-d_tree_pandas      |     0.579321 |       0.383841 |   0.535783 |
| k-d_tree_sklearn     |     0.584224 |       0.931645 |   1.01532  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593209 |       0.410304 |   0.404624 |
| k-d_tree_polars      |     0.585523 |       0.424284 |   0.425365 |
| barab-szabi-1        |     0.614275 |       0.426623 |   0.432006 |
| Bori_Aron_solution-1 |     0.581937 |       0.571142 |   0.530234 |
| k-d_tree_pandas      |     0.578622 |       0.39799  |   0.578799 |
| k-d_tree_sklearn     |     0.579895 |       0.976787 |   1.06471  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579922 |       0.468997 |   0.434177 |
| k-d_tree_polars      |     0.57857  |       0.535906 |   0.5233   |
| barab-szabi-1        |     0.58071  |       0.532547 |   0.530661 |
| Bori_Aron_solution-1 |     0.574788 |       0.734366 |   0.539349 |
| k-d_tree_pandas      |     0.577758 |       0.517044 |   0.758242 |
| k-d_tree_sklearn     |     0.587259 |       1.19364  |   1.08433  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575295 |       0.708737 |   0.470224 |
| Bori_Aron_solution-1 |     0.577191 |       1.44024  |   0.599849 |
| k-d_tree_polars      |     0.588725 |       0.863324 |   0.87278  |
| barab-szabi-1        |     0.582341 |       0.866292 |   0.915941 |
| k-d_tree_pandas      |     0.579177 |       0.733504 |   1.15884  |
| k-d_tree_sklearn     |     0.591048 |       2.04256  |   1.17639  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57899  |        5.2182  |   0.724295 |
| Bori_Aron_solution-1 |     0.574167 |       10.4751  |   0.859251 |
| k-d_tree_sklearn     |     0.59406  |       15.6796  |   1.2976   |
| k-d_tree_polars      |     0.581275 |        4.89048 |   6.45432  |
| barab-szabi-1        |     0.587152 |        4.96685 |   6.73053  |
| k-d_tree_pandas      |     0.596804 |        3.79511 |   6.85849  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575338 |        71.8956 |    2.85399 |
| k-d_tree_sklearn     |     0.590374 |       223.813  |    4.43764 |
| Bori_Aron_solution-1 |     0.687052 |       151.272  |   17.5485  |