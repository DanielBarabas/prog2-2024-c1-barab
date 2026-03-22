# 2026-03-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.945122 |       0.439172 |   0.436499 |
| k-d_tree_polars      |     0.94056  |       0.406143 |   0.440668 |
| k-d_tree_pandas      |     0.94169  |       0.387179 |   0.553135 |
| Bori_Aron_solution-1 |     0.935427 |       0.584745 |   0.575657 |
| solution-1           |     7.96076  |       1e-06    |   0.692054 |
| barab-szabi-1        |     8.95944  |       0.55083  |   0.896272 |
| k-d_tree_sklearn     |     3.12796  |       1.15669  |   1.087    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489642 |       0.443299 |   0.444443 |
| barab-szabi-1        |     0.490255 |       0.412666 |   0.449232 |
| k-d_tree_polars      |     0.492652 |       0.412369 |   0.449467 |
| Bori_Aron_solution-1 |     0.485894 |       0.567024 |   0.551752 |
| k-d_tree_pandas      |     0.493704 |       0.39297  |   0.566644 |
| k-d_tree_sklearn     |     0.508158 |       0.969168 |   1.07631  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493523 |       0.451806 |   0.450542 |
| barab-szabi-1        |     0.492608 |       0.441139 |   0.472505 |
| k-d_tree_polars      |     0.495169 |       0.439655 |   0.474238 |
| Bori_Aron_solution-1 |     0.488537 |       0.601103 |   0.555812 |
| k-d_tree_pandas      |     0.493869 |       0.420691 |   0.600517 |
| k-d_tree_sklearn     |     0.492703 |       1.02114  |   1.09432  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491309 |       0.508676 |   0.479075 |
| Bori_Aron_solution-1 |     0.497251 |       0.788086 |   0.562388 |
| k-d_tree_polars      |     0.490412 |       0.565534 |   0.566449 |
| barab-szabi-1        |     0.494085 |       0.567755 |   0.583874 |
| k-d_tree_pandas      |     0.500613 |       0.50906  |   0.737179 |
| k-d_tree_sklearn     |     0.500933 |       1.26605  |   1.13179  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496245 |       0.734944 |   0.509753 |
| Bori_Aron_solution-1 |     0.486844 |       1.50389  |   0.589256 |
| k-d_tree_polars      |     0.493897 |       0.945626 |   0.91735  |
| barab-szabi-1        |     0.491146 |       0.947313 |   0.944905 |
| k-d_tree_pandas      |     0.502435 |       0.823327 |   1.17484  |
| k-d_tree_sklearn     |     0.497917 |       2.13919  |   1.22412  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490913 |        4.92367 |   0.743589 |
| Bori_Aron_solution-1 |     0.490521 |       11.0383  |   0.843879 |
| k-d_tree_sklearn     |     0.501434 |       16.2655  |   1.30927  |
| k-d_tree_polars      |     0.493095 |        5.61465 |   6.37434  |
| barab-szabi-1        |     0.492048 |        5.696   |   6.37832  |
| k-d_tree_pandas      |     0.498348 |        4.5843  |   6.75212  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489856 |        71.7204 |    2.67475 |
| k-d_tree_sklearn     |     0.916755 |       236.098  |    3.87699 |
| Bori_Aron_solution-1 |     0.493203 |       148.693  |   19.5601  |