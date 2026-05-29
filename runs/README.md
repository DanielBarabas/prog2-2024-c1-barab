# 2026-05-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64085  |       1e-06    |   0.409224 |
| k-d_tree_polars      |     0.449734 |       0.405286 |   0.427508 |
| barab-szabi-2        |     0.449137 |       0.420036 |   0.429976 |
| k-d_tree_pandas      |     0.451671 |       0.378317 |   0.527436 |
| Bori_Aron_solution-1 |     0.446623 |       0.559741 |   0.536226 |
| barab-szabi-1        |     8.00426  |       0.426071 |   0.571323 |
| k-d_tree_sklearn     |     2.91659  |       1.08691  |   1.04468  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456578 |       0.428739 |   0.425835 |
| k-d_tree_polars      |     0.463148 |       0.408883 |   0.434927 |
| barab-szabi-1        |     0.461227 |       0.401834 |   0.443456 |
| Bori_Aron_solution-1 |     0.453459 |       0.535919 |   0.533649 |
| k-d_tree_pandas      |     0.464047 |       0.388392 |   0.541199 |
| k-d_tree_sklearn     |     0.462688 |       0.957154 |   1.03308  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459702 |       0.437369 |   0.442724 |
| k-d_tree_polars      |     0.45742  |       0.430049 |   0.450938 |
| barab-szabi-1        |     0.460655 |       0.436802 |   0.451813 |
| Bori_Aron_solution-1 |     0.452841 |       0.585948 |   0.536419 |
| k-d_tree_pandas      |     0.458766 |       0.403756 |   0.574935 |
| k-d_tree_sklearn     |     0.46287  |       0.997868 |   1.05028  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459793 |       0.500457 |   0.466155 |
| Bori_Aron_solution-1 |     0.451442 |       0.768878 |   0.544999 |
| k-d_tree_polars      |     0.460509 |       0.546251 |   0.551001 |
| barab-szabi-1        |     0.458143 |       0.549121 |   0.561482 |
| k-d_tree_pandas      |     0.460271 |       0.489799 |   0.701865 |
| k-d_tree_sklearn     |     0.462414 |       1.22883  |   1.08114  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458815 |       0.745441 |   0.502717 |
| Bori_Aron_solution-1 |     0.454342 |       1.44793  |   0.566193 |
| k-d_tree_polars      |     0.459138 |       0.907424 |   0.942332 |
| barab-szabi-1        |     0.467993 |       0.889283 |   0.976609 |
| k-d_tree_sklearn     |     0.464687 |       2.10777  |   1.13256  |
| k-d_tree_pandas      |     0.46195  |       0.784478 |   1.15558  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459672 |        5.43921 |   0.700069 |
| Bori_Aron_solution-1 |     0.453227 |       11.3978  |   0.791522 |
| k-d_tree_sklearn     |     0.458811 |       16.714   |   1.21392  |
| k-d_tree_polars      |     0.461031 |        5.13663 |   7.30835  |
| barab-szabi-1        |     0.457212 |        5.16005 |   7.31251  |
| k-d_tree_pandas      |     0.459239 |        4.10395 |   7.65973  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462306 |        74.6082 |     2.4469 |
| k-d_tree_sklearn     |     0.628623 |       253.947  |     3.3288 |
| Bori_Aron_solution-1 |     0.457263 |       151.722  |    24.9931 |