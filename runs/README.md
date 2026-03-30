# 2026-03-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.410921 |       0.400631 |   0.397365 |
| k-d_tree_polars      |     0.41306  |       0.367424 |   0.401323 |
| solution-1           |     7.22788  |       1e-06    |   0.431821 |
| barab-szabi-1        |     8.77427  |       0.403658 |   0.444831 |
| Bori_Aron_solution-1 |     0.401487 |       0.4974   |   0.497143 |
| k-d_tree_pandas      |     0.412037 |       0.351846 |   0.49912  |
| k-d_tree_sklearn     |     2.86667  |       0.949262 |   0.949184 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.407914 |       0.401863 |   0.401807 |
| barab-szabi-1        |     0.408255 |       0.37084  |   0.405278 |
| k-d_tree_polars      |     0.409116 |       0.3723   |   0.405612 |
| Bori_Aron_solution-1 |     0.403076 |       0.508909 |   0.497312 |
| k-d_tree_pandas      |     0.40853  |       0.358685 |   0.507536 |
| k-d_tree_sklearn     |     0.413533 |       0.876718 |   0.973795 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.412262 |       0.413769 |   0.410962 |
| k-d_tree_polars      |     0.408583 |       0.400376 |   0.425941 |
| barab-szabi-1        |     0.407072 |       0.436062 |   0.446344 |
| Bori_Aron_solution-1 |     0.402335 |       0.543535 |   0.511246 |
| k-d_tree_pandas      |     0.407498 |       0.376527 |   0.541478 |
| k-d_tree_sklearn     |     0.415554 |       0.933813 |   0.969173 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.423559 |       0.477737 |   0.458792 |
| barab-szabi-1        |     0.408589 |       0.51829  |   0.518172 |
| k-d_tree_polars      |     0.414167 |       0.533613 |   0.520694 |
| Bori_Aron_solution-1 |     0.413684 |       0.715324 |   0.533595 |
| k-d_tree_pandas      |     0.421378 |       0.463366 |   0.677317 |
| k-d_tree_sklearn     |     0.41955  |       1.17441  |   1.02991  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.415783 |       0.71738  |   0.478386 |
| Bori_Aron_solution-1 |     0.408576 |       1.32824  |   0.551934 |
| k-d_tree_polars      |     0.424716 |       0.846431 |   0.837765 |
| barab-szabi-1        |     0.418554 |       0.84631  |   0.874199 |
| k-d_tree_pandas      |     0.412038 |       0.719288 |   1.05163  |
| k-d_tree_sklearn     |     0.420231 |       1.92487  |   1.10904  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.405637 |        4.90262 |   0.685102 |
| Bori_Aron_solution-1 |     0.40291  |        9.74864 |   0.829887 |
| k-d_tree_sklearn     |     0.419949 |       13.7036  |   1.21302  |
| k-d_tree_polars      |     0.410719 |        4.8478  |   5.8932   |
| barab-szabi-1        |     0.408526 |        4.81192 |   5.91123  |
| k-d_tree_pandas      |     0.411066 |        3.82566 |   6.36287  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622498 |        67.0104 |    2.57093 |
| k-d_tree_sklearn     |     0.418507 |       185.888  |    3.84528 |
| Bori_Aron_solution-1 |     0.418786 |       134.373  |   23.4701  |