# 2026-10-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.64315  |       1e-06    |   0.462696 |
| k-d_tree_polars      |     0.48915  |       0.467577 |   0.467118 |
| barab-szabi-2        |     0.501518 |       0.468739 |   0.478276 |
| k-d_tree_pandas      |     0.472579 |       0.404074 |   0.568076 |
| barab-szabi-1        |     9.15433  |       0.489759 |   0.571496 |
| Bori_Aron_solution-1 |     0.473012 |       0.58642  |   0.603796 |
| k-d_tree_sklearn     |     3.39167  |       1.36155  |   1.21832  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476946 |       0.427239 |   0.431034 |
| k-d_tree_polars      |     0.470409 |       0.430691 |   0.443512 |
| barab-szabi-1        |     0.468189 |       0.422582 |   0.443513 |
| Bori_Aron_solution-1 |     0.472659 |       0.565046 |   0.538466 |
| k-d_tree_pandas      |     0.485351 |       0.395453 |   0.554787 |
| k-d_tree_sklearn     |     0.472303 |       0.981576 |   1.05651  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468659 |       0.450623 |   0.443898 |
| k-d_tree_polars      |     0.470248 |       0.458579 |   0.461796 |
| barab-szabi-1        |     0.465336 |       0.458145 |   0.46343  |
| Bori_Aron_solution-1 |     0.4654   |       0.592206 |   0.553118 |
| k-d_tree_pandas      |     0.466509 |       0.40973  |   0.596375 |
| k-d_tree_sklearn     |     0.484498 |       1.06354  |   1.08896  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493488 |       0.554464 |   0.496918 |
| Bori_Aron_solution-1 |     0.515405 |       0.836657 |   0.592288 |
| k-d_tree_polars      |     0.499687 |       0.597472 |   0.596328 |
| barab-szabi-1        |     0.503368 |       0.587451 |   0.61731  |
| k-d_tree_pandas      |     0.496888 |       0.518155 |   0.782501 |
| k-d_tree_sklearn     |     0.509178 |       1.35406  |   1.27144  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472917 |       0.742693 |   0.498341 |
| Bori_Aron_solution-1 |     0.514745 |       1.47284  |   0.606663 |
| k-d_tree_polars      |     0.500097 |       0.929275 |   0.904098 |
| barab-szabi-1        |     0.503488 |       0.9567   |   1.01383  |
| k-d_tree_sklearn     |     0.470695 |       2.12487  |   1.2129   |
| k-d_tree_pandas      |     0.517677 |       0.839611 |   1.28969  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468768 |        5.29348 |   0.746202 |
| Bori_Aron_solution-1 |     0.460561 |       10.7478  |   0.809245 |
| k-d_tree_sklearn     |     0.49677  |       17.7686  |   1.40183  |
| k-d_tree_polars      |     0.473907 |        5.26656 |   6.53947  |
| barab-szabi-1        |     0.479685 |        5.36458 |   6.8672   |
| k-d_tree_pandas      |     0.523555 |        4.34108 |   6.9021   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.834968 |        72.8978 |    2.82398 |
| k-d_tree_sklearn     |     0.619612 |       237.337  |    3.89405 |
| Bori_Aron_solution-1 |     0.503942 |       152.625  |   26.0158  |