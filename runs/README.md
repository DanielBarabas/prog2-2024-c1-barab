# 2024-09-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611373 |       0.386026 |   0.3886   |
| barab-szabi-1        |     0.613146 |       0.400774 |   0.388837 |
| k-d_tree_polars      |     4.25143  |       0.429814 |   0.398406 |
| solution-1           |     7.71498  |       1e-06    |   0.416993 |
| Bori_Aron_solution-1 |     4.51357  |       0.538924 |   0.451426 |
| k-d_tree_pandas      |     0.599973 |       0.379611 |   0.531433 |
| k-d_tree_sklearn     |     3.13732  |       0.966094 |   0.710172 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613536 |       0.391451 |   0.386365 |
| barab-szabi-1        |     0.65078  |       0.557946 |   0.38891  |
| k-d_tree_polars      |     0.601559 |       0.413186 |   0.393058 |
| Bori_Aron_solution-1 |     0.598114 |       0.524236 |   0.518087 |
| k-d_tree_pandas      |     0.632639 |       0.382776 |   0.540314 |
| k-d_tree_sklearn     |     0.617738 |       0.889093 |   0.712941 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603356 |       0.404658 |   0.40057  |
| barab-szabi-1        |     0.61645  |       0.428103 |   0.419064 |
| k-d_tree_polars      |     0.607831 |       0.426089 |   0.422088 |
| Bori_Aron_solution-1 |     0.610046 |       0.566007 |   0.52552  |
| k-d_tree_pandas      |     0.611213 |       0.413272 |   0.577769 |
| k-d_tree_sklearn     |     0.614067 |       0.925636 |   0.728625 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619494 |       0.470316 |   0.426266 |
| barab-szabi-1        |     0.612662 |       0.534462 |   0.531275 |
| k-d_tree_polars      |     0.604932 |       0.531096 |   0.546878 |
| Bori_Aron_solution-1 |     0.610504 |       0.753129 |   0.549252 |
| k-d_tree_pandas      |     0.613535 |       0.494903 |   0.708938 |
| k-d_tree_sklearn     |     0.616728 |       1.18819  |   0.788321 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610137 |       0.748784 |   0.468399 |
| Bori_Aron_solution-1 |     0.600193 |       1.39113  |   0.568963 |
| k-d_tree_polars      |     0.610514 |       0.85017  |   0.861641 |
| k-d_tree_sklearn     |     0.607955 |       1.97734  |   0.865029 |
| barab-szabi-1        |     0.613677 |       0.852231 |   0.914472 |
| k-d_tree_pandas      |     0.610516 |       0.743023 |   1.14158  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615016 |        5.39246 |   0.74234  |
| Bori_Aron_solution-1 |     0.604034 |       10.7875  |   0.822088 |
| k-d_tree_sklearn     |     0.612463 |       16.101   |   1.00163  |
| k-d_tree_polars      |     0.610624 |        4.84832 |   6.56347  |
| barab-szabi-1        |     0.609137 |        4.89839 |   6.59969  |
| k-d_tree_pandas      |     0.612085 |        3.88748 |   6.94422  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.693593 |        69.9441 |    3.11509 |
| k-d_tree_sklearn     |     0.894063 |       231.416  |    3.91129 |
| Bori_Aron_solution-1 |     0.603805 |       156.771  |   18.5587  |