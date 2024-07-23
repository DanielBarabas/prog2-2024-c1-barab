# 2024-07-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.13303  |       1e-06    |   0.368106 |
| k-d_tree_polars      |     0.602227 |       0.414992 |   0.398915 |
| barab-szabi-2        |     0.577742 |       0.396716 |   0.399169 |
| barab-szabi-1        |     0.575134 |       0.415842 |   0.402765 |
| Bori_Aron_solution-1 |     0.571286 |       0.536158 |   0.550871 |
| k-d_tree_pandas      |     0.580339 |       0.395549 |   0.580431 |
| k-d_tree_sklearn     |    10.9734   |       1.06264  |   0.742845 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.580652 |       0.418705 |   0.406107 |
| k-d_tree_polars      |     0.580539 |       0.420343 |   0.407199 |
| barab-szabi-2        |     0.575002 |       0.413114 |   0.421784 |
| Bori_Aron_solution-1 |     0.565922 |       0.561645 |   0.537744 |
| k-d_tree_pandas      |     0.567118 |       0.397859 |   0.578039 |
| k-d_tree_sklearn     |     0.579392 |       0.946066 |   0.72525  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583941 |       0.42152  |   0.418383 |
| k-d_tree_polars      |     0.577745 |       0.447349 |   0.431763 |
| barab-szabi-1        |     0.578454 |       0.4406   |   0.433525 |
| Bori_Aron_solution-1 |     0.566207 |       0.589093 |   0.547892 |
| k-d_tree_pandas      |     0.573317 |       0.417966 |   0.592667 |
| k-d_tree_sklearn     |     0.576337 |       0.983471 |   0.757604 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566036 |       0.476303 |   0.44109  |
| k-d_tree_polars      |     0.572728 |       0.548479 |   0.524373 |
| barab-szabi-1        |     0.573187 |       0.548882 |   0.538829 |
| Bori_Aron_solution-1 |     0.569921 |       0.768061 |   0.563977 |
| k-d_tree_pandas      |     0.578998 |       0.492008 |   0.729602 |
| k-d_tree_sklearn     |     0.58096  |       1.22912  |   0.823167 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573231 |       0.751221 |   0.503574 |
| Bori_Aron_solution-1 |     0.576781 |       1.42638  |   0.588947 |
| k-d_tree_sklearn     |     0.575439 |       2.08986  |   0.894596 |
| k-d_tree_polars      |     0.578874 |       0.870641 |   0.916641 |
| barab-szabi-1        |     0.576811 |       0.877304 |   0.947579 |
| k-d_tree_pandas      |     0.579521 |       0.753584 |   1.18525  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573046 |        5.48817 |   0.746529 |
| Bori_Aron_solution-1 |     0.565005 |       10.7717  |   0.8729   |
| k-d_tree_sklearn     |     0.582714 |       16.4391  |   1.01514  |
| k-d_tree_polars      |     0.574965 |        4.96945 |   6.6252   |
| barab-szabi-1        |     0.573811 |        4.87356 |   6.64483  |
| k-d_tree_pandas      |     0.575948 |        3.91258 |   7.04955  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736484 |        74.6166 |    3.21842 |
| k-d_tree_sklearn     |     0.575226 |       235.066  |    3.9054  |
| Bori_Aron_solution-1 |     0.581227 |       150.673  |   16.9881  |