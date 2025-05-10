# 2025-05-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.504234 |       0.408442 |   0.428481 |
| solution-1           |     7.58121  |       1e-06    |   0.453427 |
| k-d_tree_polars      |     3.84328  |       0.411128 |   0.462604 |
| Bori_Aron_solution-1 |     4.53786  |       0.658478 |   0.475343 |
| barab-szabi-2        |     0.521205 |       0.411228 |   0.481465 |
| k-d_tree_pandas      |     0.505417 |       0.379699 |   0.540569 |
| k-d_tree_sklearn     |     2.93475  |       1.12126  |   1.02821  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518891 |       0.408412 |   0.412234 |
| k-d_tree_polars      |     0.519773 |       0.40996  |   0.41724  |
| barab-szabi-1        |     0.521581 |       0.408145 |   0.423834 |
| Bori_Aron_solution-1 |     0.51357  |       0.552644 |   0.539924 |
| k-d_tree_pandas      |     0.514783 |       0.402461 |   0.549613 |
| k-d_tree_sklearn     |     0.520025 |       0.963551 |   1.03844  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5163   |       0.417341 |   0.445837 |
| barab-szabi-1        |     0.519168 |       0.43183  |   0.44765  |
| k-d_tree_polars      |     0.522536 |       0.429413 |   0.447764 |
| Bori_Aron_solution-1 |     0.533141 |       0.585223 |   0.5439   |
| k-d_tree_pandas      |     0.548839 |       0.401973 |   0.600194 |
| k-d_tree_sklearn     |     0.519826 |       0.997794 |   1.05631  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516149 |       0.487589 |   0.455428 |
| Bori_Aron_solution-1 |     0.51242  |       0.768643 |   0.556039 |
| barab-szabi-1        |     0.518147 |       0.541533 |   0.556798 |
| k-d_tree_polars      |     0.521327 |       0.561501 |   0.568546 |
| k-d_tree_pandas      |     0.515018 |       0.485571 |   0.73166  |
| k-d_tree_sklearn     |     0.519353 |       1.23446  |   1.11891  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526278 |       0.734033 |   0.498378 |
| Bori_Aron_solution-1 |     0.520021 |       1.40894  |   0.591149 |
| k-d_tree_polars      |     0.522942 |       0.887407 |   0.897771 |
| barab-szabi-1        |     0.523225 |       0.877502 |   0.936632 |
| k-d_tree_pandas      |     0.51953  |       0.762843 |   1.1821   |
| k-d_tree_sklearn     |     0.522796 |       2.09102  |   1.23986  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519052 |        5.24212 |   0.719755 |
| Bori_Aron_solution-1 |     0.516637 |       10.6561  |   0.889524 |
| k-d_tree_sklearn     |     0.519248 |       15.8748  |   1.30593  |
| k-d_tree_polars      |     0.526113 |        5.11805 |   6.56081  |
| barab-szabi-1        |     0.522012 |        5.04488 |   6.60217  |
| k-d_tree_pandas      |     0.520576 |        4.00653 |   6.99322  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598609 |        72.6269 |    2.85569 |
| k-d_tree_sklearn     |     0.728807 |       231.109  |    4.49647 |
| Bori_Aron_solution-1 |     0.511287 |       150.314  |   16.3095  |