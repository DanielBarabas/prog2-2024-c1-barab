# 2025-06-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.32202  |       1e-06    |   0.349808 |
| barab-szabi-2        |     0.587107 |       0.425595 |   0.419672 |
| k-d_tree_polars      |     0.590764 |       0.402534 |   0.42493  |
| barab-szabi-1        |     0.549773 |       0.40959  |   0.428248 |
| Bori_Aron_solution-1 |     0.556657 |       0.549035 |   0.556253 |
| k-d_tree_pandas      |     0.554413 |       0.395471 |   0.560736 |
| k-d_tree_sklearn     |     9.84803  |       1.0899   |   1.04744  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56013  |       0.423443 |   0.428142 |
| k-d_tree_polars      |     0.555315 |       0.421792 |   0.438309 |
| barab-szabi-1        |     0.591175 |       0.416441 |   0.438472 |
| Bori_Aron_solution-1 |     0.556372 |       0.55799  |   0.54591  |
| k-d_tree_pandas      |     0.557003 |       0.391845 |   0.583686 |
| k-d_tree_sklearn     |     0.56522  |       0.999939 |   1.16207  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552519 |       0.426959 |   0.434814 |
| k-d_tree_polars      |     0.550643 |       0.432348 |   0.449885 |
| barab-szabi-1        |     0.553562 |       0.430745 |   0.455441 |
| Bori_Aron_solution-1 |     0.541572 |       0.59207  |   0.544903 |
| k-d_tree_pandas      |     0.551219 |       0.401957 |   0.594461 |
| k-d_tree_sklearn     |     0.557348 |       1.02584  |   1.08204  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56609  |       0.505626 |   0.478789 |
| k-d_tree_polars      |     0.568259 |       0.543983 |   0.550252 |
| Bori_Aron_solution-1 |     0.552988 |       0.774222 |   0.571838 |
| barab-szabi-1        |     0.571291 |       0.55477  |   0.5804   |
| k-d_tree_pandas      |     0.572657 |       0.500307 |   0.749616 |
| k-d_tree_sklearn     |     0.552745 |       1.23299  |   1.14808  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552989 |       0.732053 |   0.48863  |
| Bori_Aron_solution-1 |     0.540987 |       1.39187  |   0.583151 |
| k-d_tree_polars      |     0.56231  |       0.876743 |   0.928456 |
| barab-szabi-1        |     0.547076 |       0.89205  |   0.956365 |
| k-d_tree_pandas      |     0.566045 |       0.762857 |   1.19127  |
| k-d_tree_sklearn     |     0.559624 |       2.03828  |   1.19806  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55671  |        5.4768  |   0.750581 |
| Bori_Aron_solution-1 |     0.564083 |       10.7085  |   0.853842 |
| k-d_tree_sklearn     |     0.558373 |       16.4148  |   1.28933  |
| barab-szabi-1        |     0.545585 |        4.9858  |   6.63043  |
| k-d_tree_polars      |     0.552204 |        4.95756 |   6.6464   |
| k-d_tree_pandas      |     0.559821 |        3.90881 |   7.11034  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563024 |        71.1515 |    2.61124 |
| k-d_tree_sklearn     |     0.556448 |       228.076  |    3.90463 |
| Bori_Aron_solution-1 |     0.547183 |       140.232  |   17.2394  |