# 2026-03-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460382 |       0.429087 |   0.432778 |
| k-d_tree_polars      |     0.565195 |       0.405307 |   0.434442 |
| solution-1           |     8.15297  |       1e-06    |   0.4805   |
| Bori_Aron_solution-1 |     0.465465 |       0.560162 |   0.543567 |
| k-d_tree_pandas      |     0.465687 |       0.377597 |   0.546247 |
| barab-szabi-1        |     8.61371  |       0.449636 |   0.580251 |
| k-d_tree_sklearn     |     3.52612  |       1.27406  |   1.09251  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.458719 |       0.405634 |   0.435411 |
| k-d_tree_polars      |     0.469222 |       0.412061 |   0.443627 |
| barab-szabi-2        |     0.462156 |       0.434994 |   0.445846 |
| Bori_Aron_solution-1 |     0.470209 |       0.574677 |   0.554378 |
| k-d_tree_pandas      |     0.473133 |       0.391385 |   0.563641 |
| k-d_tree_sklearn     |     0.460921 |       0.967934 |   1.07107  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463702 |       0.442277 |   0.439956 |
| barab-szabi-1        |     0.464838 |       0.430145 |   0.463043 |
| k-d_tree_polars      |     0.457994 |       0.437927 |   0.467681 |
| Bori_Aron_solution-1 |     0.455578 |       0.603827 |   0.554744 |
| k-d_tree_pandas      |     0.458176 |       0.406978 |   0.597139 |
| k-d_tree_sklearn     |     0.465434 |       1.00415  |   1.07495  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458032 |       0.506239 |   0.467653 |
| Bori_Aron_solution-1 |     0.450174 |       0.776003 |   0.556766 |
| k-d_tree_polars      |     0.455514 |       0.554935 |   0.567764 |
| barab-szabi-1        |     0.45724  |       0.556597 |   0.58706  |
| k-d_tree_pandas      |     0.454948 |       0.498386 |   0.7353   |
| k-d_tree_sklearn     |     0.462683 |       1.24457  |   1.13006  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465005 |       0.725397 |   0.517635 |
| Bori_Aron_solution-1 |     0.455887 |       1.4432   |   0.581254 |
| k-d_tree_polars      |     0.460956 |       0.918091 |   0.911805 |
| barab-szabi-1        |     0.454893 |       0.923652 |   0.947824 |
| k-d_tree_pandas      |     0.459004 |       0.81274  |   1.17559  |
| k-d_tree_sklearn     |     0.459946 |       2.09046  |   1.21513  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461236 |        5.21771 |   0.757906 |
| Bori_Aron_solution-1 |     0.457383 |       10.9491  |   0.800429 |
| k-d_tree_sklearn     |     0.457713 |       16.6785  |   1.27772  |
| k-d_tree_polars      |     0.455112 |        5.45604 |   6.60534  |
| barab-szabi-1        |     0.465818 |        5.60025 |   6.61317  |
| k-d_tree_pandas      |     0.459506 |        4.47159 |   6.97425  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78108  |        68.8237 |    2.63233 |
| k-d_tree_sklearn     |     0.460442 |       233.279  |    3.84511 |
| Bori_Aron_solution-1 |     0.453851 |       150.754  |   28.147   |