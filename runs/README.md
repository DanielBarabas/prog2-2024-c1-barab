# 2025-12-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.983778 |       0.532196 |   0.437881 |
| k-d_tree_polars      |     0.557504 |       0.425613 |   0.456839 |
| barab-szabi-1        |     0.55197  |       0.425606 |   0.471519 |
| solution-1           |     8.22557  |       1e-06    |   0.475782 |
| Bori_Aron_solution-1 |     0.557332 |       0.596547 |   0.59907  |
| k-d_tree_pandas      |     8.66514  |       0.419114 |   0.682445 |
| k-d_tree_sklearn     |     8.37635  |       1.14627  |   1.12041  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.553205 |       0.426114 |   0.449246 |
| barab-szabi-2        |     0.546514 |       0.449472 |   0.450572 |
| barab-szabi-1        |     0.54767  |       0.430243 |   0.466631 |
| k-d_tree_pandas      |     0.546335 |       0.407381 |   0.574242 |
| Bori_Aron_solution-1 |     0.530717 |       0.568762 |   0.581862 |
| k-d_tree_sklearn     |     0.563874 |       1.02094  |   1.11869  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.532613 |       0.453859 |   0.463869 |
| barab-szabi-1        |     0.560364 |       0.450564 |   0.466    |
| barab-szabi-2        |     0.566452 |       0.461718 |   0.47051  |
| Bori_Aron_solution-1 |     0.527289 |       0.605916 |   0.548233 |
| k-d_tree_pandas      |     0.542629 |       0.428377 |   0.655316 |
| k-d_tree_sklearn     |     0.552149 |       1.0495   |   1.12014  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530621 |       0.511314 |   0.484575 |
| k-d_tree_polars      |     0.544232 |       0.566641 |   0.560498 |
| barab-szabi-1        |     0.54862  |       0.572128 |   0.57578  |
| Bori_Aron_solution-1 |     0.53722  |       0.79574  |   0.580834 |
| k-d_tree_pandas      |     0.533229 |       0.50137  |   0.735211 |
| k-d_tree_sklearn     |     0.540182 |       1.27592  |   1.20625  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534374 |       0.747849 |   0.521686 |
| Bori_Aron_solution-1 |     0.538052 |       1.46844  |   0.597822 |
| k-d_tree_polars      |     0.554882 |       0.946177 |   0.91867  |
| barab-szabi-1        |     0.538942 |       0.942065 |   0.973973 |
| k-d_tree_pandas      |     0.540928 |       0.820753 |   1.19507  |
| k-d_tree_sklearn     |     0.54363  |       2.18085  |   1.25914  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558972 |        5.25389 |   0.752492 |
| Bori_Aron_solution-1 |     0.531678 |       11.4327  |   0.877285 |
| k-d_tree_sklearn     |     0.539526 |       17.1438  |   1.34551  |
| barab-szabi-1        |     0.539958 |        5.42913 |   6.68436  |
| k-d_tree_polars      |     0.536956 |        5.38257 |   6.8021   |
| k-d_tree_pandas      |     0.54035  |        4.44499 |   7.24862  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571564 |        80.2405 |    2.76151 |
| k-d_tree_sklearn     |     0.56098  |       239.215  |    4.45332 |
| Bori_Aron_solution-1 |     0.661787 |       156.043  |   17.9898  |