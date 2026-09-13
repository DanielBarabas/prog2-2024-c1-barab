# 2026-09-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.46242  |       1e-06    |   0.345838 |
| barab-szabi-2        |     0.432585 |       0.423531 |   0.43122  |
| k-d_tree_polars      |     0.424001 |       0.404592 |   0.439889 |
| barab-szabi-1        |     8.09402  |       0.410194 |   0.466303 |
| k-d_tree_pandas      |     0.425944 |       0.365257 |   0.523488 |
| Bori_Aron_solution-1 |     0.419531 |       0.528659 |   0.524544 |
| k-d_tree_sklearn     |     2.77989  |       0.972869 |   1.00839  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.440023 |       0.431451 |   0.42243  |
| barab-szabi-1        |     0.43894  |       0.40809  |   0.437015 |
| k-d_tree_polars      |     0.442479 |       0.404804 |   0.448677 |
| Bori_Aron_solution-1 |     0.443168 |       0.544502 |   0.515124 |
| k-d_tree_pandas      |     0.438186 |       0.420135 |   0.574609 |
| k-d_tree_sklearn     |     0.442565 |       0.956938 |   1.01252  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.43018  |       0.438463 |   0.434079 |
| k-d_tree_polars      |     0.435343 |       0.431252 |   0.455097 |
| barab-szabi-1        |     0.43493  |       0.434643 |   0.467684 |
| Bori_Aron_solution-1 |     0.429653 |       0.575829 |   0.525826 |
| k-d_tree_pandas      |     0.439501 |       0.394577 |   0.565011 |
| k-d_tree_sklearn     |     0.43783  |       0.97193  |   1.02867  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432936 |       0.495956 |   0.463743 |
| k-d_tree_polars      |     0.439698 |       0.554492 |   0.531539 |
| Bori_Aron_solution-1 |     0.437238 |       0.724741 |   0.53865  |
| barab-szabi-1        |     0.443444 |       0.539578 |   0.5532   |
| k-d_tree_pandas      |     0.438313 |       0.468095 |   0.683721 |
| k-d_tree_sklearn     |     0.441038 |       1.20352  |   1.07569  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.437616 |       0.727612 |   0.507989 |
| Bori_Aron_solution-1 |     0.426337 |       1.32195  |   0.560534 |
| k-d_tree_polars      |     0.432964 |       0.85184  |   0.857572 |
| barab-szabi-1        |     0.440753 |       0.8578   |   0.899859 |
| k-d_tree_pandas      |     0.440132 |       0.728462 |   1.07628  |
| k-d_tree_sklearn     |     0.441564 |       1.93477  |   1.12315  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.436113 |        4.91607 |   0.707427 |
| Bori_Aron_solution-1 |     0.428951 |        9.77579 |   0.878308 |
| k-d_tree_sklearn     |     0.438208 |       14.6919  |   1.27439  |
| barab-szabi-1        |     0.439016 |        4.69095 |   6.05776  |
| k-d_tree_polars      |     0.43683  |        4.79962 |   6.14905  |
| k-d_tree_pandas      |     0.433119 |        3.78245 |   6.53129  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527533 |        68.2976 |    2.62039 |
| k-d_tree_sklearn     |     0.676641 |       180.005  |    4.30756 |
| Bori_Aron_solution-1 |     0.436749 |       140.636  |   14.9488  |