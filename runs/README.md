# 2024-03-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.693437 |       0.374396 |   0.35153  |
| solution-1           |     8.0714   |       1e-06    |   0.357933 |
| barab-szabi-1        |     0.722553 |       0.403021 |   0.361609 |
| k-d_tree_polars      |     0.718183 |       0.396391 |   0.363298 |
| Bori_Aron_solution-1 |     0.683267 |       0.500699 |   0.499664 |
| k-d_tree_pandas      |     8.0917   |       0.394189 |   0.534724 |
| k-d_tree_sklearn     |     3.17988  |       0.917429 |   0.675109 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725454 |       0.363098 |   0.359024 |
| barab-szabi-1        |     0.723436 |       0.405928 |   0.368195 |
| k-d_tree_polars      |     0.727771 |       0.406977 |   0.373909 |
| Bori_Aron_solution-1 |     0.713633 |       0.512733 |   0.509116 |
| k-d_tree_pandas      |     0.722379 |       0.387012 |   0.517914 |
| k-d_tree_sklearn     |     0.730561 |       0.871961 |   0.702203 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.719189 |       0.379201 |   0.370505 |
| k-d_tree_polars      |     0.725925 |       0.4315   |   0.392664 |
| barab-szabi-1        |     0.719335 |       0.432801 |   0.400221 |
| Bori_Aron_solution-1 |     0.709852 |       0.556096 |   0.499902 |
| k-d_tree_pandas      |     0.73109  |       0.404968 |   0.553061 |
| k-d_tree_sklearn     |     0.721929 |       0.937099 |   0.733644 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727316 |       0.449654 |   0.405126 |
| k-d_tree_polars      |     0.729705 |       0.542071 |   0.491251 |
| barab-szabi-1        |     0.716101 |       0.543973 |   0.503749 |
| Bori_Aron_solution-1 |     0.714548 |       0.732616 |   0.514727 |
| k-d_tree_pandas      |     0.724865 |       0.484973 |   0.688192 |
| k-d_tree_sklearn     |     0.730615 |       1.12803  |   0.765184 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.715292 |       0.690711 |   0.444278 |
| Bori_Aron_solution-1 |     0.703483 |       1.3818   |   0.540249 |
| k-d_tree_polars      |     0.722441 |       0.873283 |   0.84776  |
| k-d_tree_sklearn     |     0.728999 |       1.93918  |   0.873868 |
| barab-szabi-1        |     0.731447 |       0.867748 |   0.875562 |
| k-d_tree_pandas      |     0.721744 |       0.7617   |   1.12189  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728564 |        5.58421 |   0.776735 |
| Bori_Aron_solution-1 |     0.741996 |       11.0047  |   0.805903 |
| k-d_tree_sklearn     |     0.72442  |       16.7048  |   1.08127  |
| k-d_tree_polars      |     0.724187 |        5.00143 |   6.7494   |
| barab-szabi-1        |     0.720299 |        4.97858 |   6.85015  |
| k-d_tree_pandas      |     0.729187 |        3.95751 |   7.23577  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.716766 |        74.3067 |    3.73247 |
| k-d_tree_sklearn     |     0.921881 |       236.909  |    4.87937 |
| Bori_Aron_solution-1 |     0.80985  |       153.037  |   13.7199  |