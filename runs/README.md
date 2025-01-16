# 2025-01-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.30291  |       1e-06    |   0.375894 |
| barab-szabi-2        |     0.57744  |       0.414507 |   0.408085 |
| k-d_tree_polars      |     0.595694 |       0.404424 |   0.441035 |
| barab-szabi-1        |     0.577258 |       0.406029 |   0.450207 |
| Bori_Aron_solution-1 |     0.594774 |       0.541819 |   0.540592 |
| k-d_tree_pandas      |     8.65277  |       0.406736 |   0.577477 |
| k-d_tree_sklearn     |     3.12583  |       0.983995 |   1.02609  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602028 |       0.408315 |   0.403893 |
| k-d_tree_polars      |     0.588743 |       0.408775 |   0.406322 |
| barab-szabi-1        |     0.597718 |       0.442288 |   0.413688 |
| Bori_Aron_solution-1 |     0.614019 |       0.55712  |   0.544104 |
| k-d_tree_pandas      |     0.590578 |       0.392865 |   0.557953 |
| k-d_tree_sklearn     |     0.597008 |       0.966696 |   1.04303  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589696 |       0.4182   |   0.41564  |
| barab-szabi-1        |     0.612096 |       0.439931 |   0.441058 |
| k-d_tree_polars      |     0.588813 |       0.441122 |   0.450069 |
| Bori_Aron_solution-1 |     0.588405 |       0.5812   |   0.540497 |
| k-d_tree_pandas      |     0.592923 |       0.408652 |   0.584207 |
| k-d_tree_sklearn     |     0.595298 |       1.00974  |   1.06305  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595428 |       0.485773 |   0.461058 |
| k-d_tree_polars      |     0.59577  |       0.547367 |   0.537865 |
| Bori_Aron_solution-1 |     0.586093 |       0.744495 |   0.552266 |
| barab-szabi-1        |     0.594424 |       0.540841 |   0.556222 |
| k-d_tree_pandas      |     0.591274 |       0.488801 |   0.746562 |
| k-d_tree_sklearn     |     0.595585 |       1.23319  |   1.11018  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593266 |       0.725169 |   0.480454 |
| Bori_Aron_solution-1 |     0.582302 |       1.37862  |   0.575798 |
| k-d_tree_polars      |     0.589035 |       0.868526 |   0.877303 |
| barab-szabi-1        |     0.590988 |       0.871659 |   0.918479 |
| k-d_tree_pandas      |     0.590482 |       0.741667 |   1.2005   |
| k-d_tree_sklearn     |     0.591772 |       2.05361  |   1.21998  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5909   |        5.4778  |   0.767955 |
| Bori_Aron_solution-1 |     0.599605 |       10.9228  |   0.894812 |
| k-d_tree_sklearn     |     0.593453 |       17.2271  |   1.34699  |
| barab-szabi-1        |     0.595935 |        4.95782 |   6.85408  |
| k-d_tree_polars      |     0.60344  |        4.89127 |   7.06446  |
| k-d_tree_pandas      |     0.591451 |        3.86358 |   7.13955  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602119 |        78.5768 |    3.21044 |
| k-d_tree_sklearn     |     0.616155 |       239.195  |    4.64472 |
| Bori_Aron_solution-1 |     0.712036 |       157.069  |   18.6426  |