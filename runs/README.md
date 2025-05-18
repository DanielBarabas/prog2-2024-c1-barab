# 2025-05-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.587662 |       0.439165 |   0.433105 |
| barab-szabi-2        |     0.587078 |       0.434007 |   0.444029 |
| solution-1           |     7.6154   |       1e-06    |   0.466222 |
| Bori_Aron_solution-1 |     0.560329 |       0.600153 |   0.580918 |
| barab-szabi-1        |     8.01075  |       0.532199 |   0.581056 |
| k-d_tree_pandas      |     0.594573 |       0.436436 |   0.617535 |
| k-d_tree_sklearn     |     2.94546  |       1.126    |   1.15213  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587348 |       0.443547 |   0.440046 |
| barab-szabi-1        |     0.582583 |       0.456653 |   0.446675 |
| k-d_tree_polars      |     0.582216 |       0.473114 |   0.460416 |
| Bori_Aron_solution-1 |     0.57882  |       0.60246  |   0.573379 |
| k-d_tree_pandas      |     0.586401 |       0.418616 |   0.596016 |
| k-d_tree_sklearn     |     0.58753  |       1.02621  |   1.12728  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616397 |       0.454665 |   0.450953 |
| k-d_tree_polars      |     0.594897 |       0.475686 |   0.466682 |
| barab-szabi-1        |     0.587045 |       0.462562 |   0.477154 |
| Bori_Aron_solution-1 |     0.574195 |       0.675177 |   0.608263 |
| k-d_tree_pandas      |     0.594452 |       0.44933  |   0.669918 |
| k-d_tree_sklearn     |     0.589422 |       1.10631  |   1.15312  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57423  |       0.52241  |   0.490312 |
| k-d_tree_polars      |     0.598151 |       0.586953 |   0.577792 |
| barab-szabi-1        |     0.599327 |       0.580482 |   0.586296 |
| Bori_Aron_solution-1 |     0.589065 |       0.850097 |   0.610329 |
| k-d_tree_pandas      |     0.611435 |       0.510168 |   0.769172 |
| k-d_tree_sklearn     |     0.590858 |       1.3962   |   1.24118  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586858 |       0.772631 |   0.634848 |
| Bori_Aron_solution-1 |     0.575216 |       1.50369  |   0.636963 |
| k-d_tree_polars      |     0.57574  |       0.905665 |   0.960325 |
| barab-szabi-1        |     0.586918 |       0.906935 |   0.977009 |
| k-d_tree_pandas      |     0.622454 |       0.814783 |   1.29706  |
| k-d_tree_sklearn     |     0.601484 |       2.34158  |   1.35315  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611457 |        6.10274 |   0.784968 |
| Bori_Aron_solution-1 |     0.576959 |       11.5605  |   0.950163 |
| k-d_tree_sklearn     |     0.609472 |       18.1393  |   1.47188  |
| k-d_tree_polars      |     0.6223   |        5.52066 |   7.27108  |
| barab-szabi-1        |     0.606085 |        5.11849 |   7.51937  |
| k-d_tree_pandas      |     0.59089  |        4.05101 |   7.9265   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641792 |        78.4422 |    3.08719 |
| k-d_tree_sklearn     |     0.709261 |       244.612  |    4.44647 |
| Bori_Aron_solution-1 |     0.582431 |       149.539  |   16.7384  |