# 2025-06-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.560355 |       0.425822 |   0.428657 |
| k-d_tree_polars      |     0.563727 |       0.419881 |   0.435851 |
| solution-1           |     8.13274  |       1e-06    |   0.455926 |
| barab-szabi-2        |     0.571585 |       0.424774 |   0.47376  |
| Bori_Aron_solution-1 |     0.590603 |       0.563967 |   0.558581 |
| k-d_tree_pandas      |     0.560116 |       0.404528 |   0.573994 |
| k-d_tree_sklearn     |    10.5176   |       1.32116  |   1.0837   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.567178 |       0.451573 |   0.439296 |
| barab-szabi-1        |     0.570933 |       0.444402 |   0.440372 |
| barab-szabi-2        |     0.569657 |       0.454705 |   0.469914 |
| Bori_Aron_solution-1 |     0.570642 |       0.589301 |   0.596911 |
| k-d_tree_pandas      |     0.581749 |       0.399829 |   0.598546 |
| k-d_tree_sklearn     |     0.568911 |       1.02065  |   1.11886  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588457 |       0.456218 |   0.456188 |
| k-d_tree_polars      |     0.57313  |       0.450757 |   0.470635 |
| barab-szabi-1        |     0.59727  |       0.453125 |   0.473899 |
| Bori_Aron_solution-1 |     0.571024 |       0.618048 |   0.579228 |
| k-d_tree_pandas      |     0.574656 |       0.427085 |   0.647422 |
| k-d_tree_sklearn     |     0.577847 |       1.0759   |   1.16811  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566207 |       0.508149 |   0.47199  |
| k-d_tree_polars      |     0.562463 |       0.556136 |   0.567653 |
| Bori_Aron_solution-1 |     0.564487 |       0.782504 |   0.571327 |
| barab-szabi-1        |     0.566082 |       0.567297 |   0.57404  |
| k-d_tree_pandas      |     0.569082 |       0.492245 |   0.747964 |
| k-d_tree_sklearn     |     0.581185 |       1.30751  |   1.17734  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573929 |       0.773529 |   0.539649 |
| Bori_Aron_solution-1 |     0.570756 |       1.4283   |   0.606198 |
| k-d_tree_polars      |     0.563459 |       0.893885 |   0.937351 |
| barab-szabi-1        |     0.56833  |       0.897573 |   0.963162 |
| k-d_tree_pandas      |     0.56629  |       0.77032  |   1.20901  |
| k-d_tree_sklearn     |     0.582978 |       2.11613  |   1.23372  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566291 |        5.84555 |   0.795006 |
| Bori_Aron_solution-1 |     0.558697 |       11.2994  |   0.876423 |
| k-d_tree_sklearn     |     0.567199 |       17.6211  |   1.35447  |
| barab-szabi-1        |     0.568515 |        5.03447 |   7.01826  |
| k-d_tree_polars      |     0.584476 |        5.05063 |   7.54481  |
| k-d_tree_pandas      |     0.580325 |        3.98844 |   7.60288  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568137 |        80.7688 |    3.06224 |
| k-d_tree_sklearn     |     0.570329 |       251.543  |    4.1821  |
| Bori_Aron_solution-1 |     0.569199 |       159.426  |   15.8355  |