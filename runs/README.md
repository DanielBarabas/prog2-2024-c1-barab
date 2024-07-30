# 2024-07-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584482 |       0.408794 |   0.393729 |
| k-d_tree_polars      |     0.581599 |       0.416331 |   0.397823 |
| solution-1           |     8.23652  |       1e-06    |   0.520802 |
| k-d_tree_pandas      |     0.581303 |       0.429483 |   0.545497 |
| barab-szabi-1        |     8.47263  |       0.478529 |   0.558754 |
| Bori_Aron_solution-1 |     0.576408 |       0.547965 |   0.564712 |
| k-d_tree_sklearn     |     3.07023  |       1.12657  |   0.73622  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574039 |       0.405821 |   0.398489 |
| k-d_tree_polars      |     0.577085 |       0.43778  |   0.412345 |
| barab-szabi-1        |     0.585856 |       0.432151 |   0.417375 |
| Bori_Aron_solution-1 |     0.575951 |       0.564549 |   0.534723 |
| k-d_tree_pandas      |     0.582651 |       0.399873 |   0.578599 |
| k-d_tree_sklearn     |     0.593893 |       0.962299 |   0.754657 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579412 |       0.42032  |   0.424461 |
| barab-szabi-1        |     0.575272 |       0.432946 |   0.43266  |
| k-d_tree_polars      |     0.576896 |       0.444021 |   0.434609 |
| Bori_Aron_solution-1 |     0.583619 |       0.577305 |   0.554133 |
| k-d_tree_pandas      |     0.592465 |       0.423942 |   0.608389 |
| k-d_tree_sklearn     |     0.579286 |       1.0043   |   0.772944 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580365 |       0.483425 |   0.443517 |
| k-d_tree_polars      |     0.579367 |       0.564853 |   0.532899 |
| barab-szabi-1        |     0.571373 |       0.56187  |   0.542124 |
| Bori_Aron_solution-1 |     0.579618 |       0.760698 |   0.566589 |
| k-d_tree_pandas      |     0.58037  |       0.483222 |   0.725301 |
| k-d_tree_sklearn     |     0.613572 |       1.21647  |   0.820421 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593526 |       0.766531 |   0.513157 |
| Bori_Aron_solution-1 |     0.578827 |       1.45795  |   0.593171 |
| k-d_tree_polars      |     0.574841 |       0.86525  |   0.904393 |
| k-d_tree_sklearn     |     0.590451 |       2.12925  |   0.911453 |
| barab-szabi-1        |     0.580807 |       0.871273 |   0.945925 |
| k-d_tree_pandas      |     0.583163 |       0.768817 |   1.18728  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566373 |        5.43107 |   0.746335 |
| Bori_Aron_solution-1 |     0.57579  |       10.854   |   0.843593 |
| k-d_tree_sklearn     |     0.566241 |       16.7632  |   0.981901 |
| k-d_tree_polars      |     0.5597   |        4.84065 |   6.7809   |
| barab-szabi-1        |     0.577938 |        4.84534 |   6.81826  |
| k-d_tree_pandas      |     0.561764 |        3.90557 |   7.14877  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560375 |        75.9297 |    3.11836 |
| k-d_tree_sklearn     |     0.584671 |       236.297  |    4.00255 |
| Bori_Aron_solution-1 |     0.669495 |       150.791  |   17.441   |