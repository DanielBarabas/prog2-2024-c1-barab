# 2025-01-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.31842  |       1e-06    |   0.397258 |
| barab-szabi-2        |     8.27686  |       0.537579 |   0.434999 |
| barab-szabi-1        |     0.635579 |       0.450819 |   0.453731 |
| k-d_tree_polars      |     0.624086 |       0.460077 |   0.453941 |
| Bori_Aron_solution-1 |     0.633816 |       0.591027 |   0.577644 |
| k-d_tree_pandas      |     0.626882 |       0.426998 |   0.583284 |
| k-d_tree_sklearn     |     3.23924  |       1.05549  |   1.15673  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630341 |       0.44312  |   0.434255 |
| barab-szabi-1        |     0.630024 |       0.455642 |   0.442685 |
| k-d_tree_polars      |     0.686849 |       0.455319 |   0.452225 |
| Bori_Aron_solution-1 |     0.623767 |       0.595246 |   0.592371 |
| k-d_tree_pandas      |     0.626902 |       0.433582 |   0.616084 |
| k-d_tree_sklearn     |     0.625411 |       1.05651  |   1.11479  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630853 |       0.453547 |   0.449297 |
| barab-szabi-1        |     0.638088 |       0.468029 |   0.470869 |
| k-d_tree_polars      |     0.652135 |       0.474061 |   0.472047 |
| Bori_Aron_solution-1 |     0.614442 |       0.637337 |   0.579749 |
| k-d_tree_pandas      |     0.623402 |       0.45053  |   0.649783 |
| k-d_tree_sklearn     |     0.645002 |       1.08872  |   1.17506  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633911 |       0.511756 |   0.522521 |
| k-d_tree_polars      |     0.636234 |       0.57053  |   0.569938 |
| barab-szabi-1        |     0.634654 |       0.628645 |   0.605508 |
| Bori_Aron_solution-1 |     0.619305 |       0.811812 |   0.634553 |
| k-d_tree_pandas      |     0.638577 |       0.527631 |   0.786098 |
| k-d_tree_sklearn     |     0.631709 |       1.33281  |   1.24998  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.619056 |       1.44936  |   0.604101 |
| barab-szabi-2        |     0.650363 |       0.75564  |   0.648844 |
| k-d_tree_polars      |     0.622766 |       0.91209  |   0.945549 |
| barab-szabi-1        |     0.637558 |       0.917317 |   0.997353 |
| k-d_tree_pandas      |     0.618847 |       0.779825 |   1.2401   |
| k-d_tree_sklearn     |     0.620952 |       2.19159  |   1.2938   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648509 |        5.96039 |   0.799156 |
| Bori_Aron_solution-1 |     0.624404 |       11.4308  |   0.930933 |
| k-d_tree_sklearn     |     0.636506 |       18.6667  |   1.45724  |
| k-d_tree_polars      |     0.634911 |        5.02035 |   7.42494  |
| barab-szabi-1        |     0.629997 |        5.03799 |   7.54224  |
| k-d_tree_pandas      |     0.62153  |        3.914   |   7.77977  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624241 |         81.172 |    3.16079 |
| k-d_tree_sklearn     |     0.636109 |        248.656 |    4.57318 |
| Bori_Aron_solution-1 |     0.668816 |        147.415 |   17.8762  |