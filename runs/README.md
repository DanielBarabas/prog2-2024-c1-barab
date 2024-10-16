# 2024-10-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.32944  |       1e-06    |   0.377238 |
| barab-szabi-1        |     0.667301 |       0.443882 |   0.411185 |
| k-d_tree_polars      |     0.664313 |       0.446343 |   0.411813 |
| barab-szabi-2        |     0.663491 |       0.421082 |   0.415367 |
| k-d_tree_pandas      |     0.656399 |       0.422092 |   0.560043 |
| Bori_Aron_solution-1 |     0.654965 |       0.583982 |   0.589071 |
| k-d_tree_sklearn     |    11.7105   |       1.11498  |   1.07969  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.676459 |       0.444201 |   0.427289 |
| barab-szabi-2        |     0.679186 |       0.448225 |   0.428114 |
| k-d_tree_polars      |     0.685791 |       0.467639 |   0.440151 |
| Bori_Aron_solution-1 |     0.656339 |       0.576365 |   0.590113 |
| k-d_tree_pandas      |     0.668987 |       0.438659 |   0.600572 |
| k-d_tree_sklearn     |     0.705308 |       1.02341  |   1.10409  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.694742 |       0.431804 |   0.429639 |
| k-d_tree_polars      |     0.663114 |       0.465812 |   0.437537 |
| barab-szabi-1        |     0.649789 |       0.47094  |   0.455    |
| Bori_Aron_solution-1 |     0.662733 |       0.625353 |   0.572808 |
| k-d_tree_pandas      |     0.685757 |       0.443431 |   0.633601 |
| k-d_tree_sklearn     |     0.686219 |       1.04686  |   1.10098  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.664168 |       0.500492 |   0.467934 |
| k-d_tree_polars      |     0.662993 |       0.575377 |   0.55153  |
| barab-szabi-1        |     0.663029 |       0.570345 |   0.562217 |
| Bori_Aron_solution-1 |     0.656175 |       0.800531 |   0.603771 |
| k-d_tree_pandas      |     0.67679  |       0.507544 |   0.757705 |
| k-d_tree_sklearn     |     0.667378 |       1.28783  |   1.17189  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.660955 |       1.5075   |   0.628725 |
| barab-szabi-2        |     0.667368 |       0.793883 |   0.65869  |
| k-d_tree_polars      |     0.66282  |       0.901559 |   0.936065 |
| barab-szabi-1        |     0.692401 |       0.924125 |   1.00569  |
| k-d_tree_pandas      |     0.67473  |       0.786705 |   1.24248  |
| k-d_tree_sklearn     |     0.654838 |       2.21471  |   1.25886  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.655537 |        5.92857 |   0.777993 |
| Bori_Aron_solution-1 |     0.659034 |       11.4968  |   0.876023 |
| k-d_tree_sklearn     |     0.650274 |       18.0278  |   1.38523  |
| barab-szabi-1        |     0.667925 |        4.8981  |   7.24603  |
| k-d_tree_polars      |     0.663346 |        4.96308 |   7.30569  |
| k-d_tree_pandas      |     0.663503 |        3.92444 |   7.59272  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631025 |        76.0835 |    3.1845  |
| k-d_tree_sklearn     |     0.657194 |       246.848  |    4.24035 |
| Bori_Aron_solution-1 |     0.656309 |       146.975  |   17.5151  |