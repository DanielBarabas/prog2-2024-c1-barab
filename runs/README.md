# 2026-04-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.464774 |       0.409225 |   0.429594 |
| solution-1           |     7.08444  |       1e-06    |   0.436133 |
| barab-szabi-1        |     0.468925 |       0.40348  |   0.436606 |
| barab-szabi-2        |     0.45789  |       0.431722 |   0.43886  |
| Bori_Aron_solution-1 |     0.456849 |       0.543158 |   0.554026 |
| k-d_tree_pandas      |     0.457836 |       0.374103 |   0.570856 |
| k-d_tree_sklearn     |     9.63518  |       1.39577  |   1.07875  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.54969  |       0.418002 |   0.430319 |
| barab-szabi-2        |     0.450507 |       0.430022 |   0.4315   |
| barab-szabi-1        |     0.468798 |       0.408828 |   0.440899 |
| Bori_Aron_solution-1 |     0.452105 |       0.559342 |   0.554872 |
| k-d_tree_pandas      |     0.459052 |       0.38588  |   0.567866 |
| k-d_tree_sklearn     |     0.465355 |       1.00461  |   1.06966  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470436 |       0.456389 |   0.460874 |
| barab-szabi-1        |     0.467637 |       0.44401  |   0.477052 |
| k-d_tree_polars      |     0.466948 |       0.444076 |   0.48247  |
| Bori_Aron_solution-1 |     0.457024 |       0.597517 |   0.559511 |
| k-d_tree_pandas      |     0.465033 |       0.412628 |   0.605992 |
| k-d_tree_sklearn     |     0.45381  |       1.02102  |   1.08506  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474149 |       0.504116 |   0.466674 |
| k-d_tree_polars      |     0.47401  |       0.574158 |   0.570982 |
| Bori_Aron_solution-1 |     0.447582 |       0.798614 |   0.580477 |
| barab-szabi-1        |     0.461158 |       0.566503 |   0.583472 |
| k-d_tree_pandas      |     0.455217 |       0.498703 |   0.726525 |
| k-d_tree_sklearn     |     0.474916 |       1.27212  |   1.1422   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455807 |       0.724272 |   0.507752 |
| Bori_Aron_solution-1 |     0.4568   |       1.44732  |   0.576713 |
| k-d_tree_polars      |     0.457777 |       0.937755 |   0.912495 |
| barab-szabi-1        |     0.451384 |       0.92398  |   0.96222  |
| k-d_tree_pandas      |     0.458383 |       0.795381 |   1.16294  |
| k-d_tree_sklearn     |     0.480133 |       2.1083   |   1.22588  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45806  |        4.86449 |   0.723159 |
| Bori_Aron_solution-1 |     0.453781 |       11.0362  |   0.79457  |
| k-d_tree_sklearn     |     0.464104 |       16.7783  |   1.29142  |
| barab-szabi-1        |     0.450287 |        5.48109 |   6.38314  |
| k-d_tree_polars      |     0.454326 |        5.59882 |   6.51945  |
| k-d_tree_pandas      |     0.462117 |        4.45986 |   6.92564  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72365  |        69.2632 |    2.6296  |
| k-d_tree_sklearn     |     0.452028 |       232.824  |    3.70586 |
| Bori_Aron_solution-1 |     0.451516 |       149.85   |   16.2208  |