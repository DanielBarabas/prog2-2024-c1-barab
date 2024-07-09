# 2024-07-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555839 |       0.399304 |   0.390788 |
| barab-szabi-1        |     0.568073 |       0.413035 |   0.39301  |
| k-d_tree_polars      |     0.561612 |       0.434884 |   0.420272 |
| solution-1           |     7.84079  |       1e-06    |   0.457542 |
| Bori_Aron_solution-1 |     0.567249 |       0.538715 |   0.605192 |
| k-d_tree_pandas      |     8.25975  |       0.415205 |   0.675697 |
| k-d_tree_sklearn     |     3.04091  |       1.06907  |   0.723457 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566727 |       0.401713 |   0.392457 |
| k-d_tree_polars      |     0.570714 |       0.420845 |   0.398917 |
| barab-szabi-1        |     0.567102 |       0.423913 |   0.414511 |
| Bori_Aron_solution-1 |     0.566448 |       0.534121 |   0.537697 |
| k-d_tree_pandas      |     0.568166 |       0.392701 |   0.544488 |
| k-d_tree_sklearn     |     0.57857  |       0.937705 |   0.713221 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57596  |       0.417468 |   0.410836 |
| k-d_tree_polars      |     0.56345  |       0.439336 |   0.422197 |
| barab-szabi-1        |     0.568933 |       0.439692 |   0.454943 |
| Bori_Aron_solution-1 |     0.569697 |       0.57739  |   0.526615 |
| k-d_tree_pandas      |     0.582598 |       0.409923 |   0.64954  |
| k-d_tree_sklearn     |     0.749943 |       1.01562  |   0.765728 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566468 |       0.476976 |   0.447475 |
| k-d_tree_polars      |     0.568532 |       0.573533 |   0.528957 |
| barab-szabi-1        |     0.583263 |       0.551506 |   0.540316 |
| Bori_Aron_solution-1 |     0.576061 |       0.764357 |   0.555113 |
| k-d_tree_pandas      |     0.574702 |       0.492745 |   0.737066 |
| k-d_tree_sklearn     |     0.580338 |       1.20035  |   0.80447  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584407 |       0.740033 |   0.496898 |
| Bori_Aron_solution-1 |     0.575733 |       1.44688  |   0.597663 |
| k-d_tree_polars      |     0.572428 |       0.883855 |   0.89284  |
| k-d_tree_sklearn     |     0.576344 |       2.06116  |   0.907605 |
| barab-szabi-1        |     0.576066 |       0.886158 |   0.953492 |
| k-d_tree_pandas      |     0.567849 |       0.758993 |   1.1645   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.575449 |       12.3024  |   0.971036 |
| barab-szabi-2        |     0.589145 |        7.00879 |   0.981602 |
| k-d_tree_sklearn     |     0.581629 |       20.1221  |   1.12293  |
| k-d_tree_polars      |     0.573903 |        5.06422 |   7.77277  |
| k-d_tree_pandas      |     0.571781 |        3.92445 |   7.9845   |
| barab-szabi-1        |     0.603246 |        5.07114 |   8.18439  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.632755 |       285.979  |    4.73637 |
| barab-szabi-2        |     0.756277 |        90.8047 |    4.80905 |
| Bori_Aron_solution-1 |     0.576454 |       177.513  |   17.4145  |