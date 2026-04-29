# 2026-04-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359939 |       0.345851 |   0.346746 |
| k-d_tree_polars      |     0.356019 |       0.324034 |   0.347711 |
| barab-szabi-1        |     0.355031 |       0.318733 |   0.348808 |
| Bori_Aron_solution-1 |     0.6919   |       0.44014  |   0.432437 |
| k-d_tree_pandas      |     0.364824 |       0.306343 |   0.436589 |
| solution-1           |     7.3361   |       1e-06    |   0.804643 |
| k-d_tree_sklearn     |    11.8225   |       2.10018  |   0.941974 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.358312 |       0.325243 |   0.345833 |
| k-d_tree_polars      |     0.357302 |       0.327744 |   0.350696 |
| barab-szabi-2        |     0.356489 |       0.367494 |   0.362356 |
| Bori_Aron_solution-1 |     0.350376 |       0.446856 |   0.434326 |
| k-d_tree_pandas      |     0.3607   |       0.325938 |   0.449849 |
| k-d_tree_sklearn     |     0.357144 |       0.779892 |   0.835031 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356375 |       0.351083 |   0.349423 |
| k-d_tree_polars      |     0.355776 |       0.349202 |   0.36077  |
| barab-szabi-1        |     0.358316 |       0.347626 |   0.367145 |
| Bori_Aron_solution-1 |     0.348676 |       0.468907 |   0.433636 |
| k-d_tree_pandas      |     0.35653  |       0.324305 |   0.47156  |
| k-d_tree_sklearn     |     0.357646 |       0.80609  |   0.85231  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.370599 |       0.409997 |   0.373974 |
| barab-szabi-1        |     0.366319 |       0.446176 |   0.453112 |
| k-d_tree_polars      |     0.36066  |       0.446107 |   0.461973 |
| k-d_tree_pandas      |     0.35664  |       0.398445 |   0.583976 |
| Bori_Aron_solution-1 |     0.352171 |       0.633998 |   0.591698 |
| k-d_tree_sklearn     |     0.361907 |       1.0195   |   0.913591 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364027 |       0.59689  |   0.406953 |
| Bori_Aron_solution-1 |     0.350621 |       1.20015  |   0.498224 |
| k-d_tree_polars      |     0.368839 |       0.720822 |   0.756675 |
| barab-szabi-1        |     0.35527  |       0.714149 |   0.795299 |
| k-d_tree_pandas      |     0.353256 |       0.616697 |   0.921908 |
| k-d_tree_sklearn     |     0.361369 |       1.7174   |   0.930758 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.351241 |        9.14736 |   0.642313 |
| barab-szabi-2        |     0.370187 |        4.82709 |   0.647906 |
| k-d_tree_sklearn     |     0.370431 |       15.325   |   0.978259 |
| k-d_tree_polars      |     0.360057 |        4.91181 |   6.13902  |
| barab-szabi-1        |     0.365153 |        5.33953 |   6.27327  |
| k-d_tree_pandas      |     0.385571 |        3.26181 |   6.29678  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.365185 |       235.641  |    3.88585 |
| barab-szabi-2        |     4.17679  |        76.0922 |    4.21559 |
| Bori_Aron_solution-1 |     0.369179 |       165.355  |   50.8523  |