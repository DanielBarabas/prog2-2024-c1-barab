# 2025-10-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.82979  |       0.642548 |   0.423898 |
| barab-szabi-1        |     0.541803 |       0.40027  |   0.424967 |
| k-d_tree_polars      |     0.540643 |       0.401819 |   0.425581 |
| Bori_Aron_solution-1 |     0.534848 |       0.539043 |   0.539606 |
| solution-1           |     7.78592  |       1e-06    |   0.677444 |
| k-d_tree_pandas      |     8.29081  |       0.46092  |   0.801996 |
| k-d_tree_sklearn     |     3.08065  |       1.20291  |   1.05952  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.538674 |       0.406898 |   0.428636 |
| barab-szabi-2        |     0.542058 |       0.421596 |   0.433684 |
| k-d_tree_polars      |     0.539126 |       0.410987 |   0.433807 |
| Bori_Aron_solution-1 |     0.535312 |       0.554215 |   0.539407 |
| k-d_tree_pandas      |     0.542212 |       0.389621 |   0.555428 |
| k-d_tree_sklearn     |     0.544748 |       0.955528 |   1.05712  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542472 |       0.435932 |   0.441399 |
| k-d_tree_polars      |     0.540181 |       0.43348  |   0.452431 |
| barab-szabi-1        |     0.545754 |       0.435147 |   0.456418 |
| Bori_Aron_solution-1 |     0.535964 |       0.610017 |   0.54512  |
| k-d_tree_pandas      |     0.549349 |       0.407024 |   0.599027 |
| k-d_tree_sklearn     |     0.54715  |       1.00362  |   1.12929  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542044 |       0.502696 |   0.468966 |
| k-d_tree_polars      |     0.537587 |       0.563246 |   0.552515 |
| Bori_Aron_solution-1 |     0.533052 |       0.776485 |   0.560324 |
| barab-szabi-1        |     0.542977 |       0.557845 |   0.562129 |
| k-d_tree_pandas      |     0.544042 |       0.503019 |   0.732927 |
| k-d_tree_sklearn     |     0.541553 |       1.25563  |   1.12751  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540232 |       0.752694 |   0.498578 |
| Bori_Aron_solution-1 |     0.534747 |       1.47503  |   0.585263 |
| k-d_tree_polars      |     0.5378   |       0.924906 |   0.907058 |
| barab-szabi-1        |     0.541711 |       0.94695  |   0.941785 |
| k-d_tree_pandas      |     0.541528 |       0.821388 |   1.17276  |
| k-d_tree_sklearn     |     0.54361  |       2.12963  |   1.21206  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543873 |        5.37197 |   0.735051 |
| Bori_Aron_solution-1 |     0.542191 |       11.3403  |   0.843206 |
| k-d_tree_sklearn     |     0.541418 |       17.3727  |   1.35086  |
| k-d_tree_polars      |     0.545428 |        5.65344 |   6.62525  |
| barab-szabi-1        |     0.553011 |        5.64337 |   6.71785  |
| k-d_tree_pandas      |     0.553686 |        4.52573 |   7.06631  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542031 |        73.8322 |    2.65213 |
| k-d_tree_sklearn     |     0.551702 |       239.36   |    4.08769 |
| Bori_Aron_solution-1 |     0.798233 |       151.322  |   18.0832  |