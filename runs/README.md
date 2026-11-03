# 2026-11-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.67009  |       1e-06    |   0.348393 |
| barab-szabi-2        |     0.436806 |       0.424506 |   0.420575 |
| k-d_tree_polars      |     0.453208 |       0.412647 |   0.4317   |
| barab-szabi-1        |    11.1579   |       0.436091 |   0.458316 |
| Bori_Aron_solution-1 |     0.477381 |       0.574464 |   0.546158 |
| k-d_tree_pandas      |     0.43713  |       0.382906 |   0.54931  |
| k-d_tree_sklearn     |     3.41057  |       1.01208  |   1.08258  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.446852 |       0.430305 |   0.427231 |
| k-d_tree_polars      |     0.446382 |       0.427515 |   0.439871 |
| barab-szabi-1        |     0.4515   |       0.428818 |   0.445298 |
| Bori_Aron_solution-1 |     0.446476 |       0.562979 |   0.556308 |
| k-d_tree_pandas      |     0.449606 |       0.397994 |   0.570606 |
| k-d_tree_sklearn     |     0.450108 |       0.983862 |   1.06681  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.454422 |       0.459159 |   0.439654 |
| k-d_tree_polars      |     0.448985 |       0.446338 |   0.464275 |
| barab-szabi-1        |     0.455672 |       0.442083 |   0.475336 |
| Bori_Aron_solution-1 |     0.446449 |       0.597175 |   0.549796 |
| k-d_tree_pandas      |     0.44967  |       0.409792 |   0.604391 |
| k-d_tree_sklearn     |     0.456605 |       1.03387  |   1.08805  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467504 |       0.519852 |   0.472885 |
| Bori_Aron_solution-1 |     0.445527 |       0.784693 |   0.559445 |
| barab-szabi-1        |     0.450902 |       0.569665 |   0.573313 |
| k-d_tree_polars      |     0.443954 |       0.576167 |   0.57461  |
| k-d_tree_pandas      |     0.454284 |       0.503506 |   0.739994 |
| k-d_tree_sklearn     |     0.448907 |       1.27171  |   1.14712  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.443758 |       0.822624 |   0.532164 |
| Bori_Aron_solution-1 |     0.446403 |       1.47904  |   0.611102 |
| k-d_tree_polars      |     0.446111 |       0.915705 |   0.93273  |
| barab-szabi-1        |     0.454395 |       0.927145 |   0.990583 |
| k-d_tree_pandas      |     0.450449 |       0.812216 |   1.183    |
| k-d_tree_sklearn     |     0.450336 |       2.11439  |   1.24103  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452793 |        5.44536 |   0.912628 |
| Bori_Aron_solution-1 |     0.442085 |       11.4285  |   1.11732  |
| k-d_tree_sklearn     |     0.458935 |       16.7074  |   1.35824  |
| barab-szabi-1        |     0.45729  |        5.13432 |   6.91478  |
| k-d_tree_polars      |     0.44955  |        5.18149 |   6.9284   |
| k-d_tree_pandas      |     0.448438 |        4.39615 |   7.28988  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.456903 |       241.055  |    4.25799 |
| barab-szabi-2        |     0.446376 |        77.2294 |    4.39692 |
| Bori_Aron_solution-1 |     0.453946 |       159.117  |   23.537   |