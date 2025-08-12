# 2025-08-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533964 |       0.431533 |   0.432674 |
| solution-1           |     7.33388  |       1e-06    |   0.441172 |
| k-d_tree_polars      |     0.555097 |       0.4149   |   0.450397 |
| barab-szabi-1        |     0.529086 |       0.419102 |   0.466049 |
| Bori_Aron_solution-1 |     0.556945 |       0.566456 |   0.56762  |
| k-d_tree_pandas      |     7.75874  |       0.413066 |   0.674672 |
| k-d_tree_sklearn     |     2.94909  |       1.09326  |   1.11634  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575354 |       0.468345 |   0.455743 |
| k-d_tree_polars      |     0.555792 |       0.420904 |   0.462218 |
| barab-szabi-1        |     0.561179 |       0.440515 |   0.473031 |
| Bori_Aron_solution-1 |     0.541148 |       0.569887 |   0.573155 |
| k-d_tree_pandas      |     0.571871 |       0.403612 |   0.582128 |
| k-d_tree_sklearn     |     0.58194  |       1.06865  |   1.10608  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566485 |       0.451145 |   0.458493 |
| k-d_tree_polars      |     0.559982 |       0.443245 |   0.463733 |
| barab-szabi-1        |     0.549074 |       0.448235 |   0.485986 |
| Bori_Aron_solution-1 |     0.551072 |       0.605085 |   0.555443 |
| k-d_tree_pandas      |     0.542907 |       0.424746 |   0.613069 |
| k-d_tree_sklearn     |     0.553801 |       1.04831  |   1.11676  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564683 |       0.514949 |   0.47772  |
| k-d_tree_polars      |     0.548309 |       0.562005 |   0.567374 |
| barab-szabi-1        |     0.561177 |       0.574019 |   0.580937 |
| Bori_Aron_solution-1 |     0.548512 |       0.801923 |   0.581939 |
| k-d_tree_pandas      |     0.547365 |       0.506328 |   0.7605   |
| k-d_tree_sklearn     |     0.554017 |       1.30501  |   1.1916   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557929 |       0.783162 |   0.534396 |
| Bori_Aron_solution-1 |     0.559523 |       1.42473  |   0.59875  |
| k-d_tree_polars      |     0.55143  |       0.908077 |   0.967384 |
| barab-szabi-1        |     0.568378 |       0.905937 |   0.984615 |
| k-d_tree_pandas      |     0.56274  |       0.791986 |   1.23728  |
| k-d_tree_sklearn     |     0.551311 |       2.17898  |   1.29224  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545399 |        5.28285 |   0.741887 |
| Bori_Aron_solution-1 |     0.540248 |       10.7608  |   0.848767 |
| k-d_tree_sklearn     |     0.554616 |       16.2677  |   1.34553  |
| k-d_tree_polars      |     0.546563 |        5.04199 |   6.51597  |
| barab-szabi-1        |     0.546615 |        5.10174 |   6.61594  |
| k-d_tree_pandas      |     0.543195 |        3.97379 |   6.96483  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545036 |        75.7472 |    2.79238 |
| k-d_tree_sklearn     |     0.597536 |       241.288  |    4.202   |
| Bori_Aron_solution-1 |     0.63387  |       143.892  |   18.4524  |