# 2026-11-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.44543  |       1e-06    |   0.275983 |
| barab-szabi-1        |     0.345761 |       0.32911  |   0.337669 |
| barab-szabi-2        |     0.3465   |       0.34753  |   0.342464 |
| k-d_tree_polars      |     8.03414  |       0.345258 |   0.369538 |
| k-d_tree_pandas      |     0.345015 |       0.300282 |   0.425058 |
| Bori_Aron_solution-1 |     0.347797 |       0.436228 |   0.432285 |
| k-d_tree_sklearn     |     3.16508  |       0.824086 |   0.837654 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.349896 |       0.336338 |   0.340187 |
| k-d_tree_polars      |     0.352045 |       0.336623 |   0.351979 |
| barab-szabi-1        |     0.351814 |       0.341368 |   0.353229 |
| Bori_Aron_solution-1 |     0.350025 |       0.433466 |   0.424754 |
| k-d_tree_pandas      |     0.353992 |       0.315291 |   0.445222 |
| k-d_tree_sklearn     |     0.356426 |       0.786385 |   0.875273 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.352273 |       0.358276 |   0.34485  |
| barab-szabi-1        |     0.351589 |       0.367292 |   0.364766 |
| k-d_tree_polars      |     0.353811 |       0.357    |   0.382279 |
| Bori_Aron_solution-1 |     0.349862 |       0.464395 |   0.433506 |
| k-d_tree_pandas      |     0.355757 |       0.325742 |   0.472518 |
| k-d_tree_sklearn     |     0.351386 |       0.842898 |   0.876669 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.374641 |       0.421062 |   0.368888 |
| k-d_tree_polars      |     0.35173  |       0.458782 |   0.446602 |
| Bori_Aron_solution-1 |     0.355656 |       0.623185 |   0.449864 |
| barab-szabi-1        |     0.354601 |       0.452843 |   0.462359 |
| k-d_tree_pandas      |     0.362843 |       0.409324 |   0.614436 |
| k-d_tree_sklearn     |     0.363391 |       1.06019  |   0.948771 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.348936 |       0.6483   |   0.426022 |
| Bori_Aron_solution-1 |     0.346111 |       1.17625  |   0.48347  |
| k-d_tree_polars      |     0.381893 |       0.702042 |   0.77765  |
| barab-szabi-1        |     0.348934 |       0.76016  |   0.807446 |
| k-d_tree_sklearn     |     0.351115 |       1.7446   |   0.938729 |
| k-d_tree_pandas      |     0.355002 |       0.613681 |   0.945322 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.346867 |        4.73937 |   0.713805 |
| Bori_Aron_solution-1 |     0.346725 |        9.25624 |   0.898946 |
| k-d_tree_sklearn     |     0.351588 |       14.4835  |   1.10847  |
| k-d_tree_polars      |     0.350115 |        4.77261 |   6.11892  |
| barab-szabi-1        |     0.361827 |        4.5367  |   6.20481  |
| k-d_tree_pandas      |     0.348829 |        3.1605  |   6.40679  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.707551 |       216.493  |    3.4026  |
| barab-szabi-2        |     0.696719 |        71.7495 |    3.54903 |
| Bori_Aron_solution-1 |     0.349096 |       150.047  |   28.813   |