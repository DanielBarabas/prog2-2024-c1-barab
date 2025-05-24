# 2025-05-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.584336 |       0.48278  |   0.42543  |
| barab-szabi-2        |     0.580745 |       0.497162 |   0.50497  |
| solution-1           |     8.37218  |       2e-06    |   0.539765 |
| Bori_Aron_solution-1 |     0.536028 |       0.579136 |   0.571338 |
| k-d_tree_pandas      |     0.56284  |       0.398786 |   0.582826 |
| barab-szabi-1        |     7.90292  |       0.477219 |   0.613813 |
| k-d_tree_sklearn     |     3.24931  |       1.10953  |   1.07874  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570956 |       0.442305 |   0.436604 |
| barab-szabi-1        |     0.655118 |       0.506631 |   0.449422 |
| k-d_tree_polars      |     0.577498 |       0.429428 |   0.450041 |
| Bori_Aron_solution-1 |     0.564626 |       0.603543 |   0.550148 |
| k-d_tree_pandas      |     0.567195 |       0.414181 |   0.581694 |
| k-d_tree_sklearn     |     0.562943 |       0.994976 |   1.06747  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.583699 |       0.438659 |   0.448728 |
| k-d_tree_polars      |     0.565274 |       0.435199 |   0.45106  |
| barab-szabi-2        |     0.588956 |       0.434521 |   0.458637 |
| Bori_Aron_solution-1 |     0.547163 |       0.589769 |   0.548778 |
| k-d_tree_pandas      |     0.59484  |       0.438057 |   0.657238 |
| k-d_tree_sklearn     |     0.557569 |       1.00428  |   1.10095  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552854 |       0.497603 |   0.458576 |
| k-d_tree_polars      |     0.588211 |       0.542334 |   0.551232 |
| barab-szabi-1        |     0.569155 |       0.545286 |   0.561891 |
| Bori_Aron_solution-1 |     0.543852 |       0.845172 |   0.622582 |
| k-d_tree_pandas      |     0.571476 |       0.496627 |   0.737112 |
| k-d_tree_sklearn     |     0.616313 |       1.285    |   1.17236  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548419 |       0.728233 |   0.490135 |
| Bori_Aron_solution-1 |     0.549272 |       1.41405  |   0.588784 |
| k-d_tree_polars      |     0.556333 |       0.880588 |   0.886588 |
| barab-szabi-1        |     0.552027 |       0.862899 |   0.934916 |
| k-d_tree_pandas      |     0.561893 |       0.756194 |   1.15982  |
| k-d_tree_sklearn     |     0.552304 |       2.0444   |   1.21407  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552368 |        5.27986 |   0.753726 |
| Bori_Aron_solution-1 |     0.542563 |       10.9565  |   0.895292 |
| k-d_tree_sklearn     |     0.585061 |       15.7594  |   1.31305  |
| barab-szabi-1        |     0.549119 |        4.95331 |   6.43683  |
| k-d_tree_polars      |     0.549169 |        5.03526 |   6.7932   |
| k-d_tree_pandas      |     0.549084 |        3.95161 |   6.86585  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632024 |        71.7345 |    2.86594 |
| k-d_tree_sklearn     |     0.782291 |       232.531  |    4.26741 |
| Bori_Aron_solution-1 |     0.546148 |       141.599  |   17.6281  |