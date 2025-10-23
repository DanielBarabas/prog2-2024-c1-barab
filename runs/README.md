# 2025-10-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59342  |       0.616388 |   0.44947  |
| k-d_tree_polars      |     0.57839  |       0.446243 |   0.468339 |
| barab-szabi-1        |     0.601708 |       0.477519 |   0.48787  |
| solution-1           |     8.62965  |       1e-06    |   0.541031 |
| Bori_Aron_solution-1 |     0.585594 |       0.585903 |   0.590498 |
| k-d_tree_pandas      |     9.45598  |       0.586128 |   0.82299  |
| k-d_tree_sklearn     |     3.22826  |       1.30048  |   1.22643  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577396 |       0.463698 |   0.463729 |
| barab-szabi-1        |     0.581381 |       0.443964 |   0.466182 |
| k-d_tree_polars      |     0.585901 |       0.476058 |   0.476072 |
| Bori_Aron_solution-1 |     0.580734 |       0.606746 |   0.577642 |
| k-d_tree_pandas      |     0.590747 |       0.427846 |   0.603779 |
| k-d_tree_sklearn     |     0.584995 |       1.06381  |   1.17028  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598424 |       0.453068 |   0.458023 |
| barab-szabi-1        |     0.555157 |       0.47241  |   0.51509  |
| k-d_tree_polars      |     0.592846 |       0.489493 |   0.516648 |
| Bori_Aron_solution-1 |     0.566528 |       0.629893 |   0.595766 |
| k-d_tree_pandas      |     0.614424 |       0.451559 |   0.692013 |
| k-d_tree_sklearn     |     0.577427 |       1.18447  |   1.19377  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565854 |       0.561233 |   0.523115 |
| k-d_tree_polars      |     0.570112 |       0.618716 |   0.597232 |
| barab-szabi-1        |     0.579044 |       0.605369 |   0.605152 |
| Bori_Aron_solution-1 |     0.56252  |       0.840946 |   0.642256 |
| k-d_tree_pandas      |     0.586638 |       0.534714 |   0.765094 |
| k-d_tree_sklearn     |     0.591312 |       1.41054  |   1.27595  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586203 |       0.834951 |   0.518533 |
| Bori_Aron_solution-1 |     0.56716  |       1.60397  |   0.680848 |
| k-d_tree_polars      |     0.578892 |       0.994415 |   0.96554  |
| barab-szabi-1        |     0.565928 |       1.01915  |   1.02666  |
| k-d_tree_pandas      |     0.589234 |       0.826359 |   1.28497  |
| k-d_tree_sklearn     |     0.585064 |       2.40561  |   1.33676  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578694 |        5.99811 |   0.841918 |
| Bori_Aron_solution-1 |     0.56772  |       11.9918  |   0.908853 |
| k-d_tree_sklearn     |     0.579868 |       19.1382  |   1.4593   |
| k-d_tree_polars      |     0.567639 |        5.76026 |   7.20813  |
| barab-szabi-1        |     0.602538 |        5.80021 |   7.263    |
| k-d_tree_pandas      |     0.59149  |        4.63428 |   7.65822  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606905 |        75.3891 |    2.75217 |
| k-d_tree_sklearn     |     0.573576 |       242.04   |    4.3304  |
| Bori_Aron_solution-1 |     0.793073 |       155.085  |   18.3655  |