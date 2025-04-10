# 2025-04-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     9.65963  |       1e-06    |   0.35634  |
| barab-szabi-2        |     0.541751 |       0.406774 |   0.400255 |
| k-d_tree_polars      |     0.54284  |       0.402186 |   0.406408 |
| barab-szabi-1        |     0.546797 |       0.397448 |   0.410496 |
| Bori_Aron_solution-1 |     0.541347 |       0.538019 |   0.53754  |
| k-d_tree_pandas      |     8.0644   |       0.401306 |   0.633482 |
| k-d_tree_sklearn     |     3.12705  |       1.00508  |   1.0057   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562654 |       0.407564 |   0.402951 |
| k-d_tree_polars      |     0.568958 |       0.404835 |   0.41058  |
| barab-szabi-1        |     0.564834 |       0.407171 |   0.414615 |
| Bori_Aron_solution-1 |     0.556241 |       0.546979 |   0.535777 |
| k-d_tree_pandas      |     0.5825   |       0.392372 |   0.547997 |
| k-d_tree_sklearn     |     0.561983 |       0.941753 |   1.0333   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557615 |       0.424373 |   0.415807 |
| k-d_tree_polars      |     0.559732 |       0.42615  |   0.431489 |
| barab-szabi-1        |     0.561623 |       0.44828  |   0.440106 |
| Bori_Aron_solution-1 |     0.54999  |       0.579892 |   0.540395 |
| k-d_tree_pandas      |     0.556993 |       0.3982   |   0.587834 |
| k-d_tree_sklearn     |     0.571378 |       0.985546 |   1.05348  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556185 |       0.480377 |   0.446277 |
| k-d_tree_polars      |     0.558077 |       0.532308 |   0.536452 |
| barab-szabi-1        |     0.563606 |       0.530939 |   0.545044 |
| Bori_Aron_solution-1 |     0.552829 |       0.751421 |   0.550557 |
| k-d_tree_pandas      |     0.556065 |       0.475179 |   0.725349 |
| k-d_tree_sklearn     |     0.564534 |       1.20669  |   1.10345  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560374 |       0.723789 |   0.476012 |
| Bori_Aron_solution-1 |     0.551858 |       1.37689  |   0.584584 |
| k-d_tree_polars      |     0.557076 |       0.852251 |   0.878686 |
| barab-szabi-1        |     0.561133 |       0.863586 |   0.916761 |
| k-d_tree_pandas      |     0.57198  |       0.739888 |   1.15448  |
| k-d_tree_sklearn     |     0.558931 |       2.01744  |   1.1916   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561285 |        5.27288 |   0.717045 |
| Bori_Aron_solution-1 |     0.569906 |       10.5269  |   0.874002 |
| k-d_tree_sklearn     |     0.590767 |       15.8884  |   1.29037  |
| barab-szabi-1        |     0.563373 |        4.84506 |   6.51111  |
| k-d_tree_polars      |     0.565267 |        4.93263 |   6.792    |
| k-d_tree_pandas      |     0.557082 |        3.81371 |   6.99093  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.758527 |        71.5665 |    2.761   |
| k-d_tree_sklearn     |     0.630583 |       229.438  |    4.38944 |
| Bori_Aron_solution-1 |     0.551648 |       148.116  |   16.223   |