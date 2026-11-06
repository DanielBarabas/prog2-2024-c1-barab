# 2026-11-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.59919  |       1e-06    |   0.344048 |
| barab-szabi-2        |     0.384617 |       0.401038 |   0.394376 |
| barab-szabi-1        |     0.388711 |       0.41913  |   0.406473 |
| k-d_tree_polars      |     7.66233  |       0.390141 |   0.42675  |
| Bori_Aron_solution-1 |     0.385161 |       0.495124 |   0.493656 |
| k-d_tree_pandas      |     0.387775 |       0.357491 |   0.513293 |
| k-d_tree_sklearn     |     2.70149  |       0.935097 |   0.976079 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.39286  |       0.401805 |   0.39661  |
| barab-szabi-1        |     0.397476 |       0.391518 |   0.421751 |
| k-d_tree_polars      |     0.413499 |       0.429045 |   0.474325 |
| Bori_Aron_solution-1 |     0.397485 |       0.515544 |   0.509876 |
| k-d_tree_pandas      |     0.420901 |       0.36981  |   0.538693 |
| k-d_tree_sklearn     |     0.403528 |       0.920418 |   0.995736 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.404039 |       0.415603 |   0.406287 |
| k-d_tree_polars      |     0.406446 |       0.431452 |   0.432541 |
| barab-szabi-1        |     0.408342 |       0.42867  |   0.442404 |
| Bori_Aron_solution-1 |     0.40521  |       0.552977 |   0.514917 |
| k-d_tree_pandas      |     0.404525 |       0.387945 |   0.54721  |
| k-d_tree_sklearn     |     0.413268 |       0.978634 |   1.00034  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.395097 |       0.474601 |   0.433492 |
| k-d_tree_polars      |     0.401405 |       0.544724 |   0.515047 |
| barab-szabi-1        |     0.399703 |       0.529561 |   0.521818 |
| Bori_Aron_solution-1 |     0.395426 |       0.713365 |   0.524972 |
| k-d_tree_pandas      |     0.406237 |       0.466132 |   0.683375 |
| k-d_tree_sklearn     |     0.404866 |       1.20224  |   1.02903  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.396457 |       0.722692 |   0.493348 |
| Bori_Aron_solution-1 |     0.393327 |       1.31544  |   0.565156 |
| k-d_tree_polars      |     0.398195 |       0.842507 |   0.816425 |
| barab-szabi-1        |     0.403113 |       0.859758 |   0.876746 |
| k-d_tree_pandas      |     0.389798 |       0.720243 |   1.04868  |
| k-d_tree_sklearn     |     0.403452 |       1.90456  |   1.12435  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.400281 |        4.73035 |   0.756121 |
| Bori_Aron_solution-1 |     0.39372  |        9.71695 |   0.988188 |
| k-d_tree_sklearn     |     0.41139  |       13.2839  |   1.24028  |
| k-d_tree_polars      |     0.402564 |        4.75827 |   5.89857  |
| barab-szabi-1        |     0.396911 |        4.6909  |   5.99953  |
| k-d_tree_pandas      |     0.394653 |        3.78094 |   6.33414  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534063 |        66.9512 |    3.75642 |
| k-d_tree_sklearn     |     0.466615 |       173.726  |    4.00032 |
| Bori_Aron_solution-1 |     0.391155 |       135.176  |   22.0964  |