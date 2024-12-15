# 2024-12-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50335  |       1e-06    |   0.351821 |
| barab-szabi-2        |     0.621478 |       0.391633 |   0.384511 |
| barab-szabi-1        |     0.613091 |       0.391911 |   0.389395 |
| k-d_tree_polars      |     0.609468 |       0.395123 |   0.394611 |
| k-d_tree_pandas      |     0.606194 |       0.375479 |   0.523822 |
| Bori_Aron_solution-1 |     0.60831  |       0.5216   |   0.529296 |
| k-d_tree_sklearn     |    10.2272   |       0.967784 |   0.95675  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607378 |       0.391395 |   0.385607 |
| k-d_tree_polars      |     0.611682 |       0.397313 |   0.390123 |
| barab-szabi-1        |     0.606302 |       0.404018 |   0.430153 |
| Bori_Aron_solution-1 |     0.598853 |       0.52485  |   0.515859 |
| k-d_tree_pandas      |     0.60921  |       0.382432 |   0.53036  |
| k-d_tree_sklearn     |     0.654997 |       0.890421 |   0.962906 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603816 |       0.400533 |   0.401213 |
| k-d_tree_polars      |     0.613548 |       0.425132 |   0.413361 |
| barab-szabi-1        |     0.606025 |       0.434334 |   0.421253 |
| Bori_Aron_solution-1 |     0.607864 |       0.563783 |   0.519261 |
| k-d_tree_pandas      |     0.608323 |       0.398692 |   0.568439 |
| k-d_tree_sklearn     |     0.612602 |       0.933877 |   0.981281 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605865 |       0.479621 |   0.429908 |
| k-d_tree_polars      |     0.61534  |       0.53559  |   0.516645 |
| barab-szabi-1        |     0.608488 |       0.536826 |   0.525422 |
| Bori_Aron_solution-1 |     0.606788 |       0.741226 |   0.531324 |
| k-d_tree_pandas      |     0.608164 |       0.477809 |   0.706672 |
| k-d_tree_sklearn     |     0.615318 |       1.15043  |   1.02684  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602798 |       0.717926 |   0.465897 |
| Bori_Aron_solution-1 |     0.598886 |       1.38329  |   0.553565 |
| k-d_tree_polars      |     0.609142 |       0.852196 |   0.854064 |
| barab-szabi-1        |     0.610341 |       0.859566 |   0.896595 |
| k-d_tree_sklearn     |     0.611741 |       1.95902  |   1.12273  |
| k-d_tree_pandas      |     0.609742 |       0.742478 |   1.12878  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605768 |        5.16788 |   0.715694 |
| Bori_Aron_solution-1 |     0.599323 |       10.4496  |   0.806377 |
| k-d_tree_sklearn     |     0.615232 |       15.4487  |   1.2313   |
| k-d_tree_polars      |     0.616342 |        4.83416 |   6.33304  |
| barab-szabi-1        |     0.605122 |        4.85526 |   6.33769  |
| k-d_tree_pandas      |     0.613774 |        3.90144 |   6.75415  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620742 |        68.9216 |    2.93701 |
| k-d_tree_sklearn     |     0.614091 |       219.86   |    4.18061 |
| Bori_Aron_solution-1 |     0.61989  |       138.354  |   18.545   |