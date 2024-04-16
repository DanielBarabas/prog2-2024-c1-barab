# 2024-04-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721312 |       0.335334 |   0.331407 |
| barab-szabi-1        |     0.727238 |       0.394532 |   0.337076 |
| k-d_tree_polars      |     8.0093   |       0.493473 |   0.354337 |
| solution-1           |     7.81548  |       1e-06    |   0.424293 |
| Bori_Aron_solution-1 |     0.711614 |       0.467046 |   0.470711 |
| k-d_tree_pandas      |     0.70332  |       0.381814 |   0.477099 |
| k-d_tree_sklearn     |     3.1511   |       0.964501 |   0.651562 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723445 |       0.341744 |   0.332325 |
| barab-szabi-1        |     0.774791 |       0.402414 |   0.346456 |
| k-d_tree_polars      |     0.724821 |       0.402771 |   0.347569 |
| Bori_Aron_solution-1 |     0.712953 |       0.482333 |   0.475926 |
| k-d_tree_pandas      |     0.737648 |       0.380174 |   0.479337 |
| k-d_tree_sklearn     |     0.732841 |       0.835896 |   0.656384 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.72898  |       0.427    |   0.367423 |
| barab-szabi-1        |     0.733808 |       0.437718 |   0.3731   |
| barab-szabi-2        |     0.731306 |       0.358517 |   0.417825 |
| Bori_Aron_solution-1 |     0.718414 |       0.518814 |   0.474755 |
| k-d_tree_pandas      |     0.734894 |       0.406644 |   0.525045 |
| k-d_tree_sklearn     |     0.736856 |       0.879256 |   0.687732 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.7236   |       0.424439 |   0.389353 |
| k-d_tree_polars      |     0.726004 |       0.54536  |   0.480188 |
| barab-szabi-1        |     0.731648 |       0.53405  |   0.484231 |
| Bori_Aron_solution-1 |     0.715412 |       0.706722 |   0.485601 |
| k-d_tree_pandas      |     0.730534 |       0.482084 |   0.65829  |
| k-d_tree_sklearn     |     0.742532 |       1.09912  |   0.74309  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726303 |       0.673562 |   0.424465 |
| Bori_Aron_solution-1 |     0.717859 |       1.3416   |   0.511183 |
| k-d_tree_polars      |     0.731924 |       0.849766 |   0.823511 |
| k-d_tree_sklearn     |     0.733079 |       1.89909  |   0.84303  |
| barab-szabi-1        |     0.728166 |       0.842785 |   0.849117 |
| k-d_tree_pandas      |     0.733512 |       0.750298 |   1.08635  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726141 |        5.51411 |   0.736915 |
| Bori_Aron_solution-1 |     0.715265 |       10.8309  |   0.767611 |
| k-d_tree_sklearn     |     0.735195 |       16.2372  |   1.04064  |
| k-d_tree_polars      |     0.72408  |        4.84945 |   6.70176  |
| barab-szabi-1        |     0.730515 |        4.83137 |   6.72117  |
| k-d_tree_pandas      |     0.738966 |        3.82667 |   6.98503  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.853546 |         74.892 |    3.70664 |
| k-d_tree_sklearn     |     0.733235 |        231.818 |    5.20225 |
| Bori_Aron_solution-1 |     0.813559 |        142.075 |   18.2686  |