# 2024-11-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7142   |       1e-06    |   0.354642 |
| barab-szabi-2        |     0.621681 |       0.380574 |   0.385642 |
| k-d_tree_polars      |     0.614625 |       0.397255 |   0.386154 |
| barab-szabi-1        |     0.608446 |       0.393539 |   0.388741 |
| Bori_Aron_solution-1 |     0.607259 |       0.516351 |   0.516419 |
| k-d_tree_pandas      |     0.61776  |       0.377513 |   0.537521 |
| k-d_tree_sklearn     |    10.5038   |       1.14434  |   0.956512 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.611461 |       0.403105 |   0.390736 |
| k-d_tree_polars      |     0.61454  |       0.401578 |   0.392589 |
| barab-szabi-2        |     0.612854 |       0.384358 |   0.395466 |
| Bori_Aron_solution-1 |     0.60482  |       0.524204 |   0.524346 |
| k-d_tree_pandas      |     0.609544 |       0.378674 |   0.527839 |
| k-d_tree_sklearn     |     0.625257 |       0.882883 |   0.956075 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606087 |       0.423427 |   0.394255 |
| k-d_tree_polars      |     0.613661 |       0.425118 |   0.417449 |
| barab-szabi-1        |     0.608172 |       0.426112 |   0.420844 |
| Bori_Aron_solution-1 |     0.599465 |       0.561295 |   0.515879 |
| k-d_tree_pandas      |     0.611596 |       0.431126 |   0.569988 |
| k-d_tree_sklearn     |     0.625125 |       0.924235 |   0.980895 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608906 |       0.462363 |   0.425357 |
| k-d_tree_polars      |     0.614923 |       0.53189  |   0.519259 |
| barab-szabi-1        |     0.617411 |       0.531427 |   0.523988 |
| Bori_Aron_solution-1 |     0.600684 |       0.734292 |   0.53322  |
| k-d_tree_pandas      |     0.612996 |       0.476635 |   0.707949 |
| k-d_tree_sklearn     |     0.610779 |       1.14476  |   1.04349  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618324 |       0.715142 |   0.464555 |
| Bori_Aron_solution-1 |     0.608429 |       1.40693  |   0.562594 |
| k-d_tree_polars      |     0.608126 |       0.860328 |   0.863196 |
| barab-szabi-1        |     0.619105 |       0.860964 |   0.905849 |
| k-d_tree_sklearn     |     0.621676 |       1.99499  |   1.12839  |
| k-d_tree_pandas      |     0.61137  |       0.750636 |   1.16095  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621625 |        5.19564 |   0.725526 |
| Bori_Aron_solution-1 |     0.603797 |       10.5116  |   0.813535 |
| k-d_tree_sklearn     |     0.621253 |       15.6739  |   1.24526  |
| barab-szabi-1        |     0.617821 |        4.87964 |   6.41265  |
| k-d_tree_polars      |     0.615852 |        4.89357 |   6.42978  |
| k-d_tree_pandas      |     0.613631 |        3.89151 |   6.92136  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622211 |        69.8479 |    2.84782 |
| k-d_tree_sklearn     |     0.618385 |       222.127  |    4.22288 |
| Bori_Aron_solution-1 |     0.630539 |       148.465  |   18.6759  |