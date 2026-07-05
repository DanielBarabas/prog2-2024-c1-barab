# 2026-07-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.467955 |       0.421452 |   0.442842 |
| barab-szabi-2        |     9.32141  |       0.687969 |   0.447409 |
| solution-1           |     8.06977  |       1e-06    |   0.448753 |
| barab-szabi-1        |     0.795878 |       0.414795 |   0.450224 |
| Bori_Aron_solution-1 |     0.461985 |       0.553675 |   0.551216 |
| k-d_tree_pandas      |     0.473294 |       0.380427 |   0.571078 |
| k-d_tree_sklearn     |     3.10992  |       1.18938  |   1.07989  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479724 |       0.45153  |   0.451259 |
| k-d_tree_polars      |     0.467209 |       0.429229 |   0.456296 |
| barab-szabi-1        |     0.475738 |       0.426728 |   0.458102 |
| Bori_Aron_solution-1 |     0.464905 |       0.545677 |   0.54336  |
| k-d_tree_pandas      |     0.471606 |       0.391009 |   0.553589 |
| k-d_tree_sklearn     |     0.480984 |       0.989632 |   1.06448  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46805  |       0.457978 |   0.453312 |
| barab-szabi-1        |     0.467311 |       0.446483 |   0.477428 |
| k-d_tree_polars      |     0.473014 |       0.494012 |   0.480802 |
| Bori_Aron_solution-1 |     0.464987 |       0.590515 |   0.550366 |
| k-d_tree_pandas      |     0.473142 |       0.408396 |   0.611139 |
| k-d_tree_sklearn     |     0.485644 |       1.04675  |   1.10308  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478246 |       0.513582 |   0.481332 |
| Bori_Aron_solution-1 |     0.464176 |       0.7749   |   0.555259 |
| barab-szabi-1        |     0.472122 |       0.574721 |   0.579059 |
| k-d_tree_polars      |     0.476513 |       0.575903 |   0.580904 |
| k-d_tree_pandas      |     0.471668 |       0.499676 |   0.734538 |
| k-d_tree_sklearn     |     0.473348 |       1.28028  |   1.1516   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47038  |       0.734304 |   0.512457 |
| Bori_Aron_solution-1 |     0.464423 |       1.42218  |   0.588533 |
| k-d_tree_polars      |     0.473436 |       0.93469  |   0.922761 |
| barab-szabi-1        |     0.469474 |       0.930028 |   0.959551 |
| k-d_tree_pandas      |     0.469592 |       0.803783 |   1.18518  |
| k-d_tree_sklearn     |     0.477041 |       2.18328  |   1.225    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471284 |        5.02717 |   0.747641 |
| Bori_Aron_solution-1 |     0.464335 |       10.8357  |   0.814925 |
| k-d_tree_sklearn     |     0.472614 |       16.2288  |   1.30655  |
| barab-szabi-1        |     0.469945 |        5.35996 |   6.52404  |
| k-d_tree_polars      |     0.471204 |        5.36036 |   6.59229  |
| k-d_tree_pandas      |     0.473187 |        4.36271 |   6.90869  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471725 |         70.196 |    2.69507 |
| k-d_tree_sklearn     |     0.753121 |        234.379 |    3.97044 |
| Bori_Aron_solution-1 |     0.469725 |        146.936 |   17.9963  |