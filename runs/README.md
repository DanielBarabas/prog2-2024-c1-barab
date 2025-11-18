# 2025-11-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525102 |       0.509057 |   0.439937 |
| k-d_tree_polars      |     0.54357  |       0.420588 |   0.441212 |
| barab-szabi-1        |     0.537689 |       0.426272 |   0.44658  |
| solution-1           |     8.39834  |       1e-06    |   0.459546 |
| Bori_Aron_solution-1 |     0.534769 |       0.573632 |   0.562241 |
| k-d_tree_pandas      |     8.90286  |       0.41766  |   0.650544 |
| k-d_tree_sklearn     |     3.45216  |       1.13041  |   1.09989  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.546915 |       0.43673  |   0.446457 |
| barab-szabi-2        |     0.550978 |       0.437733 |   0.447212 |
| barab-szabi-1        |     0.548967 |       0.474512 |   0.449134 |
| k-d_tree_pandas      |     0.53957  |       0.400194 |   0.570665 |
| Bori_Aron_solution-1 |     0.532793 |       0.57191  |   0.581012 |
| k-d_tree_sklearn     |     0.553393 |       1.02656  |   1.1099   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534744 |       0.457402 |   0.451957 |
| barab-szabi-1        |     0.540992 |       0.450114 |   0.471381 |
| k-d_tree_polars      |     0.540668 |       0.453574 |   0.475266 |
| Bori_Aron_solution-1 |     0.542575 |       0.622348 |   0.566869 |
| k-d_tree_pandas      |     0.541825 |       0.423394 |   0.616755 |
| k-d_tree_sklearn     |     0.544268 |       1.04277  |   1.14994  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543459 |       0.524331 |   0.487997 |
| Bori_Aron_solution-1 |     0.542422 |       0.79855  |   0.573568 |
| k-d_tree_polars      |     0.546813 |       0.582134 |   0.576852 |
| barab-szabi-1        |     0.545853 |       0.577391 |   0.592759 |
| k-d_tree_pandas      |     0.552418 |       0.518239 |   0.757304 |
| k-d_tree_sklearn     |     0.54396  |       1.29343  |   1.17861  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537351 |       0.769782 |   0.563605 |
| Bori_Aron_solution-1 |     0.53231  |       1.51121  |   0.60717  |
| k-d_tree_polars      |     0.540661 |       0.937453 |   0.93903  |
| barab-szabi-1        |     0.538694 |       0.933299 |   0.969267 |
| k-d_tree_pandas      |     0.549808 |       0.829863 |   1.21298  |
| k-d_tree_sklearn     |     0.548497 |       2.1979   |   1.26205  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546022 |        5.45377 |   0.765265 |
| Bori_Aron_solution-1 |     0.530243 |       11.4558  |   0.864766 |
| k-d_tree_sklearn     |     0.540398 |       17.449   |   1.33494  |
| k-d_tree_polars      |     0.539253 |        5.16828 |   6.76759  |
| barab-szabi-1        |     0.533817 |        5.47261 |   6.80288  |
| k-d_tree_pandas      |     0.541945 |        4.51934 |   7.28117  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53699  |        80.0534 |     2.8448 |
| k-d_tree_sklearn     |     0.560821 |       254.394  |     4.5007 |
| Bori_Aron_solution-1 |     0.761124 |       157.269  |    16.6901 |