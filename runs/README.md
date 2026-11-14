# 2026-11-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.81651  |       1e-06    |   0.361498 |
| barab-szabi-2        |     0.459825 |       0.433812 |   0.432386 |
| barab-szabi-1        |     0.456718 |       0.410249 |   0.457818 |
| k-d_tree_polars      |     8.77225  |       0.43432  |   0.467707 |
| Bori_Aron_solution-1 |     0.449988 |       0.54738  |   0.549659 |
| k-d_tree_pandas      |     0.447326 |       0.385985 |   0.553143 |
| k-d_tree_sklearn     |     2.92195  |       1.05788  |   1.12606  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480536 |       0.440875 |   0.430532 |
| barab-szabi-1        |     0.455864 |       0.425079 |   0.453092 |
| k-d_tree_polars      |     0.478053 |       0.451973 |   0.470762 |
| Bori_Aron_solution-1 |     0.461189 |       0.555657 |   0.551012 |
| k-d_tree_pandas      |     0.477281 |       0.414927 |   0.56642  |
| k-d_tree_sklearn     |     0.460208 |       1.00234  |   1.09774  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460234 |       0.466807 |   0.453102 |
| barab-szabi-1        |     0.463696 |       0.471948 |   0.470221 |
| k-d_tree_polars      |     0.461485 |       0.462611 |   0.475408 |
| Bori_Aron_solution-1 |     0.448519 |       0.592794 |   0.574976 |
| k-d_tree_pandas      |     0.456065 |       0.411335 |   0.604182 |
| k-d_tree_sklearn     |     0.47353  |       1.06811  |   1.1069   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473298 |       0.540402 |   0.496696 |
| k-d_tree_polars      |     0.460613 |       0.612874 |   0.579786 |
| Bori_Aron_solution-1 |     0.484248 |       0.806054 |   0.58017  |
| barab-szabi-1        |     0.459313 |       0.579974 |   0.597081 |
| k-d_tree_pandas      |     0.474532 |       0.53827  |   0.784739 |
| k-d_tree_sklearn     |     0.468916 |       1.33153  |   1.21399  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451116 |       0.77534  |   0.534872 |
| Bori_Aron_solution-1 |     0.45621  |       1.47448  |   0.609681 |
| k-d_tree_polars      |     0.465533 |       0.937655 |   0.960332 |
| barab-szabi-1        |     0.450617 |       0.911401 |   1.02697  |
| k-d_tree_pandas      |     0.463944 |       0.813414 |   1.19928  |
| k-d_tree_sklearn     |     0.462003 |       2.16399  |   1.28423  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452227 |        5.72086 |   0.895819 |
| Bori_Aron_solution-1 |     0.458169 |       11.3734  |   1.13065  |
| k-d_tree_sklearn     |     0.480306 |       18.1094  |   1.44666  |
| barab-szabi-1        |     0.463196 |        5.26837 |   7.11728  |
| k-d_tree_polars      |     0.471132 |        5.32038 |   7.1632   |
| k-d_tree_pandas      |     0.463348 |        4.41418 |   7.34024  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.613256 |       244.556  |    4.46397 |
| barab-szabi-2        |     0.858096 |        79.3069 |    4.59419 |
| Bori_Aron_solution-1 |     0.480312 |       152.378  |   24.5856  |