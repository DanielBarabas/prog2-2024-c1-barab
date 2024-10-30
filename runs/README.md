# 2024-10-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.61956  |       1e-06    |   0.367841 |
| barab-szabi-2        |     0.641928 |       0.394876 |   0.396906 |
| k-d_tree_polars      |     0.634336 |       0.411958 |   0.39948  |
| barab-szabi-1        |     0.635741 |       0.413226 |   0.400133 |
| Bori_Aron_solution-1 |     0.627873 |       0.544797 |   0.539873 |
| k-d_tree_pandas      |     0.629888 |       0.387669 |   0.553082 |
| k-d_tree_sklearn     |    10.2279   |       1.14287  |   0.994762 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.644085 |       0.415699 |   0.399642 |
| k-d_tree_polars      |     0.628478 |       0.419656 |   0.409198 |
| barab-szabi-2        |     0.644202 |       0.400111 |   0.410655 |
| Bori_Aron_solution-1 |     0.627756 |       0.551883 |   0.540975 |
| k-d_tree_pandas      |     0.633014 |       0.40512  |   0.550711 |
| k-d_tree_sklearn     |     0.656255 |       0.948774 |   0.998132 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647514 |       0.408823 |   0.413249 |
| k-d_tree_polars      |     0.623826 |       0.436686 |   0.431159 |
| barab-szabi-1        |     0.630064 |       0.440042 |   0.432467 |
| Bori_Aron_solution-1 |     0.626385 |       0.580272 |   0.536756 |
| k-d_tree_pandas      |     0.645111 |       0.416215 |   0.595144 |
| k-d_tree_sklearn     |     0.644188 |       0.963909 |   1.03209  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623642 |       0.473666 |   0.442476 |
| k-d_tree_polars      |     0.644319 |       0.546651 |   0.524678 |
| barab-szabi-1        |     0.628635 |       0.547643 |   0.545007 |
| Bori_Aron_solution-1 |     0.621531 |       0.764647 |   0.554253 |
| k-d_tree_pandas      |     0.629526 |       0.496353 |   0.71559  |
| k-d_tree_sklearn     |     0.639399 |       1.19905  |   1.07309  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626534 |       0.742941 |   0.526969 |
| Bori_Aron_solution-1 |     0.626849 |       1.42472  |   0.582745 |
| k-d_tree_polars      |     0.633798 |       0.881725 |   0.889407 |
| barab-szabi-1        |     0.648056 |       0.871784 |   0.929928 |
| k-d_tree_sklearn     |     0.630644 |       2.0716   |   1.15787  |
| k-d_tree_pandas      |     0.637567 |       0.765685 |   1.18923  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64531  |        5.49718 |   0.755819 |
| Bori_Aron_solution-1 |     0.626833 |       10.9543  |   0.824187 |
| k-d_tree_sklearn     |     0.638738 |       16.9074  |   1.30395  |
| barab-szabi-1        |     0.631162 |        4.90674 |   6.77715  |
| k-d_tree_polars      |     0.636856 |        4.92107 |   6.78754  |
| k-d_tree_pandas      |     0.628033 |        3.91722 |   6.86236  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649974 |        74.2267 |    3.09813 |
| k-d_tree_sklearn     |     0.620704 |       233.757  |    4.26277 |
| Bori_Aron_solution-1 |     0.663534 |       151.868  |   17.1441  |