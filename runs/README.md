# 2024-07-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.00704  |       1e-06    |   0.367518 |
| k-d_tree_polars      |     0.581832 |       0.410426 |   0.406763 |
| barab-szabi-2        |     0.572237 |       0.413059 |   0.40949  |
| barab-szabi-1        |     8.64627  |       0.444318 |   0.509081 |
| k-d_tree_pandas      |     0.606413 |       0.416161 |   0.546208 |
| Bori_Aron_solution-1 |     0.577832 |       0.555655 |   0.54869  |
| k-d_tree_sklearn     |     3.08826  |       1.02572  |   0.739798 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.583013 |       0.422818 |   0.412303 |
| k-d_tree_polars      |     0.578364 |       0.426152 |   0.413355 |
| barab-szabi-2        |     0.581208 |       0.415526 |   0.414787 |
| Bori_Aron_solution-1 |     0.574907 |       0.558607 |   0.54425  |
| k-d_tree_pandas      |     0.59255  |       0.407571 |   0.567942 |
| k-d_tree_sklearn     |     0.582865 |       0.945485 |   0.752603 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585783 |       0.419363 |   0.428414 |
| k-d_tree_polars      |     0.58159  |       0.447571 |   0.436238 |
| barab-szabi-1        |     0.586294 |       0.453236 |   0.449758 |
| Bori_Aron_solution-1 |     0.571726 |       0.589986 |   0.555161 |
| k-d_tree_pandas      |     0.618196 |       0.421462 |   0.618156 |
| k-d_tree_sklearn     |     0.588885 |       1.01869  |   0.77501  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579233 |       0.497208 |   0.442471 |
| k-d_tree_polars      |     0.581732 |       0.55737  |   0.537404 |
| barab-szabi-1        |     0.5844   |       0.554268 |   0.547528 |
| Bori_Aron_solution-1 |     0.572289 |       0.784312 |   0.572128 |
| k-d_tree_pandas      |     0.573418 |       0.505269 |   0.746933 |
| k-d_tree_sklearn     |     0.588097 |       1.23069  |   0.810969 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58437  |       0.751738 |   0.522113 |
| Bori_Aron_solution-1 |     0.572772 |       1.43971  |   0.583416 |
| k-d_tree_polars      |     0.567942 |       0.869393 |   0.898207 |
| k-d_tree_sklearn     |     0.580282 |       2.13457  |   0.904226 |
| barab-szabi-1        |     0.588606 |       0.89428  |   0.949608 |
| k-d_tree_pandas      |     0.570887 |       0.76434  |   1.18186  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579588 |        5.59878 |   0.733207 |
| Bori_Aron_solution-1 |     0.574998 |       11.0677  |   0.873197 |
| k-d_tree_sklearn     |     0.588847 |       17.2826  |   1.02372  |
| barab-szabi-1        |     0.578419 |        4.90558 |   6.92356  |
| k-d_tree_polars      |     0.578009 |        4.85693 |   6.94713  |
| k-d_tree_pandas      |     0.592818 |        3.90931 |   7.25418  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584927 |        74.5264 |    2.98248 |
| k-d_tree_sklearn     |     0.600749 |       235.154  |    3.93101 |
| Bori_Aron_solution-1 |     0.626323 |       145.513  |   17.8261  |