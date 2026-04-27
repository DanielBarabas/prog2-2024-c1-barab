# 2026-04-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.448093 |       0.395375 |   0.417149 |
| barab-szabi-2        |     0.453349 |       0.412002 |   0.421133 |
| barab-szabi-1        |     0.44987  |       0.511716 |   0.422549 |
| solution-1           |     7.53552  |       1e-06    |   0.434076 |
| Bori_Aron_solution-1 |     0.446468 |       0.530025 |   0.526811 |
| k-d_tree_pandas      |     0.456691 |       0.37866  |   0.54178  |
| k-d_tree_sklearn     |    10.5447   |       1.32063  |   1.05195  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456415 |       0.423249 |   0.423475 |
| k-d_tree_polars      |     0.448099 |       0.42008  |   0.433762 |
| barab-szabi-1        |     0.457677 |       0.406802 |   0.434218 |
| Bori_Aron_solution-1 |     0.45983  |       0.549118 |   0.536425 |
| k-d_tree_pandas      |     0.457253 |       0.402446 |   0.549235 |
| k-d_tree_sklearn     |     0.457614 |       0.982368 |   1.09405  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448325 |       0.434698 |   0.427217 |
| k-d_tree_polars      |     0.449711 |       0.441897 |   0.445153 |
| barab-szabi-1        |     0.461146 |       0.457731 |   0.457537 |
| Bori_Aron_solution-1 |     0.44555  |       0.585186 |   0.528528 |
| k-d_tree_pandas      |     0.462012 |       0.41007  |   0.595345 |
| k-d_tree_sklearn     |     0.46674  |       1.0017   |   1.07141  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449452 |       0.500372 |   0.459619 |
| k-d_tree_polars      |     0.449222 |       0.545095 |   0.545311 |
| Bori_Aron_solution-1 |     0.444946 |       0.769136 |   0.550402 |
| barab-szabi-1        |     0.452419 |       0.549678 |   0.557933 |
| k-d_tree_pandas      |     0.461376 |       0.489695 |   0.702357 |
| k-d_tree_sklearn     |     0.464541 |       1.23696  |   1.08604  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.450078 |       0.740632 |   0.498259 |
| Bori_Aron_solution-1 |     0.444186 |       1.45961  |   0.566735 |
| k-d_tree_polars      |     0.453352 |       0.918045 |   0.938665 |
| barab-szabi-1        |     0.448777 |       0.8939   |   0.977637 |
| k-d_tree_sklearn     |     0.45264  |       2.11292  |   1.13637  |
| k-d_tree_pandas      |     0.452556 |       0.760368 |   1.163    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.454595 |        5.53733 |   0.70462  |
| Bori_Aron_solution-1 |     0.442308 |       11.2721  |   0.785396 |
| k-d_tree_sklearn     |     0.45068  |       16.8765  |   1.20474  |
| barab-szabi-1        |     0.451    |        5.27613 |   7.41143  |
| k-d_tree_polars      |     0.449438 |        5.32979 |   7.42695  |
| k-d_tree_pandas      |     0.450677 |        4.16386 |   7.77239  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.690017 |         76.114 |    2.45468 |
| k-d_tree_sklearn     |     0.45656  |        254.484 |    3.30343 |
| Bori_Aron_solution-1 |     0.446807 |        158.776 |   16.614   |