# 2025-08-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |      1.04092 |       0.434166 |   0.455886 |
| barab-szabi-2        |      8.95061 |       0.998872 |   0.464007 |
| barab-szabi-1        |      1.02433 |       0.428184 |   0.499124 |
| k-d_tree_pandas      |      1.04628 |       0.418958 |   0.596232 |
| Bori_Aron_solution-1 |      1.03051 |       0.589963 |   0.599815 |
| solution-1           |      8.5479  |       1e-06    |   0.734595 |
| k-d_tree_sklearn     |      3.94672 |       1.58702  |   1.14212  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.591985 |       0.470623 |   0.459997 |
| barab-szabi-2        |     1.05522  |       0.484711 |   0.46478  |
| barab-szabi-1        |     1.06855  |       0.446224 |   0.468486 |
| Bori_Aron_solution-1 |     1.0423   |       0.597873 |   0.591144 |
| k-d_tree_pandas      |     0.600363 |       0.424786 |   0.598376 |
| k-d_tree_sklearn     |     0.874    |       1.05309  |   1.16332  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599875 |       0.474194 |   0.466357 |
| barab-szabi-1        |     0.593285 |       0.462651 |   0.480877 |
| k-d_tree_polars      |     0.600633 |       0.470414 |   0.505422 |
| Bori_Aron_solution-1 |     0.593138 |       0.634669 |   0.609961 |
| k-d_tree_pandas      |     0.601825 |       0.457869 |   0.645621 |
| k-d_tree_sklearn     |     0.605749 |       1.09154  |   1.19205  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592023 |       0.536797 |   0.502003 |
| k-d_tree_polars      |     0.59642  |       0.597111 |   0.593195 |
| barab-szabi-1        |     0.606864 |       0.585936 |   0.607026 |
| Bori_Aron_solution-1 |     0.605711 |       0.816224 |   0.607414 |
| k-d_tree_pandas      |     0.590641 |       0.524549 |   0.780199 |
| k-d_tree_sklearn     |     0.595738 |       1.32705  |   1.25654  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.594133 |       1.47901  |   0.625472 |
| barab-szabi-2        |     0.595271 |       0.833035 |   0.688214 |
| k-d_tree_polars      |     0.594859 |       0.918456 |   0.961819 |
| barab-szabi-1        |     0.614378 |       0.926875 |   1.05182  |
| k-d_tree_pandas      |     0.57982  |       0.809033 |   1.25077  |
| k-d_tree_sklearn     |     0.590497 |       2.23964  |   1.31419  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600352 |        5.60328 |   0.781876 |
| Bori_Aron_solution-1 |     0.596956 |       11.0695  |   0.891604 |
| k-d_tree_sklearn     |     0.620793 |       17.5298  |   1.4387   |
| barab-szabi-1        |     0.60188  |        5.09642 |   6.91742  |
| k-d_tree_polars      |     0.597684 |        5.11175 |   7.04801  |
| k-d_tree_pandas      |     0.59319  |        4.0231  |   7.42647  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60819  |        78.7071 |    2.81473 |
| k-d_tree_sklearn     |     0.877213 |       244.835  |    4.20609 |
| Bori_Aron_solution-1 |     0.596979 |       157.612  |   16.4074  |