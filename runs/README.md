# 2024-08-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.56197  |       1e-06    |   0.359995 |
| k-d_tree_polars      |     0.616039 |       0.402237 |   0.390721 |
| barab-szabi-2        |     7.80681  |       0.499007 |   0.390974 |
| barab-szabi-1        |     0.607826 |       0.399326 |   0.394445 |
| Bori_Aron_solution-1 |     0.616253 |       0.536908 |   0.534916 |
| k-d_tree_pandas      |     0.6075   |       0.40011  |   0.556743 |
| k-d_tree_sklearn     |     2.96608  |       0.933423 |   0.719943 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61564  |       0.398913 |   0.395112 |
| k-d_tree_polars      |     0.62648  |       0.411791 |   0.403768 |
| barab-szabi-1        |     0.618414 |       0.407702 |   0.409322 |
| Bori_Aron_solution-1 |     0.613203 |       0.53984  |   0.525636 |
| k-d_tree_pandas      |     0.621543 |       0.386583 |   0.559712 |
| k-d_tree_sklearn     |     0.615871 |       0.918221 |   0.718059 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620635 |       0.407083 |   0.412694 |
| barab-szabi-1        |     0.6272   |       0.4326   |   0.42705  |
| k-d_tree_polars      |     0.619203 |       0.428445 |   0.431466 |
| Bori_Aron_solution-1 |     0.627294 |       0.573362 |   0.535985 |
| k-d_tree_pandas      |     0.622706 |       0.406514 |   0.579915 |
| k-d_tree_sklearn     |     0.658011 |       0.964104 |   0.741866 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624647 |       0.472658 |   0.432037 |
| k-d_tree_polars      |     0.629626 |       0.545622 |   0.528135 |
| barab-szabi-1        |     0.624098 |       0.548959 |   0.545228 |
| Bori_Aron_solution-1 |     0.619764 |       0.764925 |   0.560788 |
| k-d_tree_pandas      |     0.625706 |       0.489814 |   0.72548  |
| k-d_tree_sklearn     |     0.642139 |       1.21649  |   0.812948 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629471 |       0.743699 |   0.485904 |
| Bori_Aron_solution-1 |     0.633625 |       1.4736   |   0.604703 |
| k-d_tree_polars      |     0.65094  |       0.885675 |   0.915092 |
| k-d_tree_sklearn     |     0.642945 |       2.13354  |   0.918191 |
| barab-szabi-1        |     0.644342 |       0.881906 |   0.951076 |
| k-d_tree_pandas      |     0.638647 |       0.787547 |   1.22218  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648274 |        5.6486  |   0.74623  |
| Bori_Aron_solution-1 |     0.622483 |       11.1356  |   0.843396 |
| k-d_tree_sklearn     |     0.637718 |       17.1949  |   1.02955  |
| k-d_tree_polars      |     0.630779 |        4.88159 |   6.78242  |
| barab-szabi-1        |     0.627606 |        4.85123 |   6.93982  |
| k-d_tree_pandas      |     0.634815 |        3.88638 |   7.28051  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63034  |        71.9236 |    2.85869 |
| k-d_tree_sklearn     |     0.639451 |       231.156  |    3.96432 |
| Bori_Aron_solution-1 |     0.667057 |       149.362  |   18.2499  |