# 2026-10-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.30061  |       1e-06    |   0.420668 |
| barab-szabi-2        |     0.457428 |       0.42299  |   0.426166 |
| k-d_tree_polars      |     0.476631 |       0.423959 |   0.433614 |
| barab-szabi-1        |     9.14691  |       0.458182 |   0.525411 |
| Bori_Aron_solution-1 |     0.467579 |       0.564536 |   0.553575 |
| k-d_tree_pandas      |     0.455319 |       0.383909 |   0.558457 |
| k-d_tree_sklearn     |     3.80507  |       1.19252  |   1.12537  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47495  |       0.434433 |   0.435176 |
| barab-szabi-1        |     0.475719 |       0.43496  |   0.44316  |
| k-d_tree_polars      |     0.470028 |       0.418916 |   0.478156 |
| Bori_Aron_solution-1 |     0.470843 |       0.54884  |   0.536687 |
| k-d_tree_pandas      |     0.474886 |       0.412143 |   0.558474 |
| k-d_tree_sklearn     |     0.480857 |       1.03513  |   1.0885   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486224 |       0.445208 |   0.432354 |
| barab-szabi-1        |     0.473057 |       0.463664 |   0.465164 |
| k-d_tree_polars      |     0.469356 |       0.461572 |   0.475723 |
| Bori_Aron_solution-1 |     0.468343 |       0.597368 |   0.555796 |
| k-d_tree_pandas      |     0.483738 |       0.419658 |   0.594901 |
| k-d_tree_sklearn     |     0.477708 |       1.07448  |   1.13132  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473957 |       0.521615 |   0.46359  |
| k-d_tree_polars      |     0.466574 |       0.572058 |   0.558291 |
| Bori_Aron_solution-1 |     0.465543 |       0.80041  |   0.569532 |
| barab-szabi-1        |     0.473997 |       0.567683 |   0.570608 |
| k-d_tree_pandas      |     0.476621 |       0.500337 |   0.751334 |
| k-d_tree_sklearn     |     0.48479  |       1.33641  |   1.18542  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483676 |       0.761774 |   0.510561 |
| Bori_Aron_solution-1 |     0.47929  |       1.47559  |   0.606714 |
| k-d_tree_polars      |     0.479856 |       0.90647  |   0.941003 |
| barab-szabi-1        |     0.476629 |       0.906309 |   1.00654  |
| k-d_tree_sklearn     |     0.478703 |       2.16508  |   1.16101  |
| k-d_tree_pandas      |     0.476388 |       0.788049 |   1.19314  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474276 |        5.56948 |   0.696193 |
| Bori_Aron_solution-1 |     0.459375 |       11.2564  |   0.801639 |
| k-d_tree_sklearn     |     0.474083 |       17.3362  |   1.26687  |
| barab-szabi-1        |     0.472406 |        5.13764 |   7.45635  |
| k-d_tree_polars      |     0.464826 |        5.05124 |   7.46523  |
| k-d_tree_pandas      |     0.466256 |        4.02293 |   7.80818  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603704 |        79.2525 |    2.5296  |
| k-d_tree_sklearn     |     0.550862 |       260.13   |    3.28122 |
| Bori_Aron_solution-1 |     0.464476 |       157.308  |   22.1707  |