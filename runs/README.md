# 2025-05-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.537982 |       0.400104 |   0.41223  |
| barab-szabi-2        |     0.541949 |       0.413205 |   0.415674 |
| solution-1           |     7.38667  |       1e-06    |   0.525826 |
| Bori_Aron_solution-1 |     0.526931 |       0.539851 |   0.533667 |
| k-d_tree_pandas      |     0.550744 |       0.3847   |   0.546946 |
| barab-szabi-1        |     8.12549  |       0.477994 |   0.628928 |
| k-d_tree_sklearn     |     2.99647  |       1.17485  |   1.04608  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551264 |       0.436327 |   0.418706 |
| barab-szabi-1        |     0.546074 |       0.41508  |   0.423384 |
| k-d_tree_polars      |     0.543178 |       0.404761 |   0.423744 |
| Bori_Aron_solution-1 |     0.542384 |       0.546669 |   0.551928 |
| k-d_tree_pandas      |     0.546162 |       0.385942 |   0.552451 |
| k-d_tree_sklearn     |     0.549097 |       0.948265 |   1.03858  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550753 |       0.429361 |   0.430454 |
| k-d_tree_polars      |     0.550287 |       0.428617 |   0.448046 |
| barab-szabi-1        |     0.543786 |       0.438514 |   0.467072 |
| Bori_Aron_solution-1 |     0.542892 |       0.582085 |   0.542128 |
| k-d_tree_pandas      |     0.54728  |       0.404236 |   0.59345  |
| k-d_tree_sklearn     |     0.552918 |       1.01903  |   1.06309  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544284 |       0.491474 |   0.459737 |
| k-d_tree_polars      |     0.555018 |       0.541224 |   0.54727  |
| Bori_Aron_solution-1 |     0.543982 |       0.760535 |   0.555366 |
| barab-szabi-1        |     0.546363 |       0.538236 |   0.55752  |
| k-d_tree_pandas      |     0.552179 |       0.484914 |   0.731452 |
| k-d_tree_sklearn     |     0.552538 |       1.22295  |   1.12967  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545433 |       0.73563  |   0.490803 |
| Bori_Aron_solution-1 |     0.539202 |       1.39628  |   0.583746 |
| k-d_tree_polars      |     0.551921 |       0.876432 |   0.888778 |
| barab-szabi-1        |     0.553558 |       0.879583 |   0.934052 |
| k-d_tree_pandas      |     0.548038 |       0.764613 |   1.16509  |
| k-d_tree_sklearn     |     0.554548 |       2.04727  |   1.20433  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548821 |        5.23028 |   0.742421 |
| Bori_Aron_solution-1 |     0.538659 |       10.6332  |   0.875361 |
| k-d_tree_sklearn     |     0.551623 |       15.9939  |   1.31614  |
| k-d_tree_polars      |     0.551003 |        4.94451 |   6.54962  |
| barab-szabi-1        |     0.548693 |        4.98894 |   6.57351  |
| k-d_tree_pandas      |     0.548293 |        3.94563 |   6.97104  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587626 |         74.784 |    2.77244 |
| k-d_tree_sklearn     |     0.739211 |        235.73  |    4.15515 |
| Bori_Aron_solution-1 |     0.54697  |        143.515 |   17.4242  |