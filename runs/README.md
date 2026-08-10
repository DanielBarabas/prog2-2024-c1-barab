# 2026-08-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.03105  |       1e-06    |   0.450504 |
| barab-szabi-2        |     0.493664 |       0.451861 |   0.458573 |
| barab-szabi-1        |     0.482307 |       0.43977  |   0.464348 |
| Bori_Aron_solution-1 |     0.478851 |       0.601292 |   0.585419 |
| k-d_tree_pandas      |     0.51624  |       0.395476 |   0.591105 |
| k-d_tree_polars      |     8.63735  |       0.503463 |   0.62504  |
| k-d_tree_sklearn     |     3.16594  |       1.18198  |   1.10885  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491894 |       0.45438  |   0.461567 |
| k-d_tree_polars      |     0.491074 |       0.434173 |   0.467213 |
| barab-szabi-1        |     0.482313 |       0.434975 |   0.470014 |
| k-d_tree_pandas      |     0.494565 |       0.401676 |   0.57971  |
| Bori_Aron_solution-1 |     0.482314 |       0.58497  |   0.593888 |
| k-d_tree_sklearn     |     0.498852 |       1.03005  |   1.1311   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461611 |       0.450125 |   0.450328 |
| barab-szabi-1        |     0.462877 |       0.442706 |   0.470158 |
| k-d_tree_polars      |     0.480485 |       0.455481 |   0.473162 |
| Bori_Aron_solution-1 |     0.461583 |       0.587487 |   0.545314 |
| k-d_tree_pandas      |     0.46564  |       0.406418 |   0.60099  |
| k-d_tree_sklearn     |     0.471411 |       1.02303  |   1.08361  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465366 |       0.518755 |   0.477953 |
| Bori_Aron_solution-1 |     0.460214 |       0.769376 |   0.551714 |
| k-d_tree_polars      |     0.465779 |       0.575332 |   0.572217 |
| barab-szabi-1        |     0.465924 |       0.566934 |   0.575036 |
| k-d_tree_pandas      |     0.469222 |       0.494837 |   0.737348 |
| k-d_tree_sklearn     |     0.469385 |       1.25871  |   1.1294   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460064 |       0.728391 |   0.513875 |
| Bori_Aron_solution-1 |     0.474635 |       1.449    |   0.583219 |
| k-d_tree_polars      |     0.464545 |       0.900955 |   0.950737 |
| barab-szabi-1        |     0.465871 |       0.923837 |   0.957432 |
| k-d_tree_pandas      |     0.472287 |       0.799281 |   1.16827  |
| k-d_tree_sklearn     |     0.472417 |       2.129    |   1.21452  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465096 |        5.27642 |   0.752865 |
| Bori_Aron_solution-1 |     0.467244 |       11.4618  |   0.862299 |
| k-d_tree_sklearn     |     0.514159 |       17.0902  |   1.31161  |
| k-d_tree_polars      |     0.464803 |        5.33903 |   6.73382  |
| barab-szabi-1        |     0.473956 |        5.29326 |   6.90792  |
| k-d_tree_pandas      |     0.492516 |        4.35228 |   7.13755  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.663042 |        73.0262 |    2.92819 |
| k-d_tree_sklearn     |     0.944455 |       239.786  |    4.21157 |
| Bori_Aron_solution-1 |     0.456197 |       154.487  |   29.0917  |