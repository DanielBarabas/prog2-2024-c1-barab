# 2025-04-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.73053  |       1e-06    |   0.359297 |
| k-d_tree_polars      |     0.549989 |       0.405526 |   0.413148 |
| barab-szabi-1        |     0.546178 |       0.401797 |   0.420267 |
| barab-szabi-2        |     0.546612 |       0.406816 |   0.424864 |
| Bori_Aron_solution-1 |     0.545552 |       0.55035  |   0.54594  |
| k-d_tree_pandas      |     7.98508  |       0.461949 |   0.675509 |
| k-d_tree_sklearn     |     3.01289  |       1.06035  |   1.01577  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587361 |       0.409874 |   0.407457 |
| barab-szabi-1        |     0.565765 |       0.408468 |   0.409101 |
| k-d_tree_polars      |     0.566247 |       0.410202 |   0.415759 |
| Bori_Aron_solution-1 |     0.554752 |       0.554901 |   0.54148  |
| k-d_tree_pandas      |     0.567546 |       0.423199 |   0.549674 |
| k-d_tree_sklearn     |     0.567311 |       0.94784  |   1.03375  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567254 |       0.426704 |   0.419754 |
| k-d_tree_polars      |     0.573256 |       0.444205 |   0.440585 |
| barab-szabi-1        |     0.566071 |       0.430239 |   0.443642 |
| Bori_Aron_solution-1 |     0.559192 |       0.583661 |   0.547934 |
| k-d_tree_pandas      |     0.56633  |       0.40673  |   0.597859 |
| k-d_tree_sklearn     |     0.570083 |       1.0017   |   1.06625  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563244 |       0.485634 |   0.448353 |
| k-d_tree_polars      |     0.562264 |       0.538041 |   0.535068 |
| barab-szabi-1        |     0.559699 |       0.535544 |   0.549658 |
| Bori_Aron_solution-1 |     0.55656  |       0.753237 |   0.595202 |
| k-d_tree_pandas      |     0.574992 |       0.480429 |   0.730021 |
| k-d_tree_sklearn     |     0.572344 |       1.21614  |   1.09966  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561027 |       0.721903 |   0.486038 |
| Bori_Aron_solution-1 |     0.557857 |       1.3879   |   0.583552 |
| k-d_tree_polars      |     0.560912 |       0.867674 |   0.892674 |
| barab-szabi-1        |     0.562976 |       0.865795 |   0.923614 |
| k-d_tree_pandas      |     0.567206 |       0.74548  |   1.16924  |
| k-d_tree_sklearn     |     0.565795 |       2.04908  |   1.20534  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567564 |        5.08934 |   0.707201 |
| Bori_Aron_solution-1 |     0.562563 |       10.5739  |   0.882994 |
| k-d_tree_sklearn     |     0.570285 |       15.57    |   1.30045  |
| k-d_tree_polars      |     0.56539  |        4.91813 |   6.38412  |
| barab-szabi-1        |     0.572143 |        4.85712 |   6.4069   |
| k-d_tree_pandas      |     0.559138 |        3.79537 |   6.75384  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747658 |        70.6096 |    2.89131 |
| k-d_tree_sklearn     |     0.651599 |       223.836  |    4.2415  |
| Bori_Aron_solution-1 |     0.559453 |       150.775  |   16.6343  |