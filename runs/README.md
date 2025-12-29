# 2025-12-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.535605 |       0.404752 |   0.430692 |
| barab-szabi-2        |     0.553009 |       0.614384 |   0.43511  |
| barab-szabi-1        |     0.525507 |       0.405878 |   0.440416 |
| Bori_Aron_solution-1 |     0.52317  |       0.548    |   0.549345 |
| k-d_tree_pandas      |     8.70313  |       0.446855 |   0.67131  |
| solution-1           |     7.74049  |       1e-06    |   0.850276 |
| k-d_tree_sklearn     |     3.08033  |       1.34836  |   1.06097  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577768 |       0.436945 |   0.439601 |
| k-d_tree_polars      |     0.533334 |       0.41113  |   0.446748 |
| barab-szabi-1        |     0.532351 |       0.417399 |   0.452571 |
| Bori_Aron_solution-1 |     0.536408 |       0.55436  |   0.557799 |
| k-d_tree_pandas      |     0.525354 |       0.394827 |   0.559819 |
| k-d_tree_sklearn     |     0.547822 |       0.975859 |   1.078    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539212 |       0.447143 |   0.447812 |
| k-d_tree_polars      |     0.5319   |       0.442677 |   0.466238 |
| barab-szabi-1        |     0.551334 |       0.453479 |   0.467582 |
| Bori_Aron_solution-1 |     0.527816 |       0.607918 |   0.560271 |
| k-d_tree_pandas      |     0.546512 |       0.415241 |   0.611481 |
| k-d_tree_sklearn     |     0.533425 |       1.02655  |   1.11949  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528526 |       0.500946 |   0.478888 |
| k-d_tree_polars      |     0.541769 |       0.5652   |   0.558326 |
| Bori_Aron_solution-1 |     0.519173 |       0.781588 |   0.567885 |
| barab-szabi-1        |     0.531947 |       0.564404 |   0.569488 |
| k-d_tree_pandas      |     0.534456 |       0.508548 |   0.745187 |
| k-d_tree_sklearn     |     0.536741 |       1.2716   |   1.16237  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53059  |       0.728347 |   0.510546 |
| Bori_Aron_solution-1 |     0.521083 |       1.439    |   0.593596 |
| k-d_tree_polars      |     0.527686 |       0.928097 |   0.911279 |
| barab-szabi-1        |     0.533503 |       0.924228 |   0.9439   |
| k-d_tree_pandas      |     0.528723 |       0.811787 |   1.17268  |
| k-d_tree_sklearn     |     0.540726 |       2.1658   |   1.23104  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532325 |        5.47209 |   0.804713 |
| Bori_Aron_solution-1 |     0.530442 |       11.5476  |   0.874443 |
| k-d_tree_sklearn     |     0.549894 |       17.0965  |   1.34465  |
| k-d_tree_polars      |     0.529379 |        5.41871 |   6.67663  |
| barab-szabi-1        |     0.546052 |        6.1864  |   6.91423  |
| k-d_tree_pandas      |     0.531334 |        4.47532 |   7.04726  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551443 |        80.8243 |    2.73605 |
| k-d_tree_sklearn     |     0.545843 |       235.383  |    4.33756 |
| Bori_Aron_solution-1 |     0.715151 |       149.347  |   18.1773  |