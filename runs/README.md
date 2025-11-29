# 2025-11-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553517 |       0.503407 |   0.437179 |
| k-d_tree_polars      |     0.536708 |       0.409454 |   0.437908 |
| barab-szabi-1        |     0.539358 |       0.409717 |   0.444618 |
| solution-1           |     8.19046  |       1e-06    |   0.45239  |
| Bori_Aron_solution-1 |     0.528261 |       0.568191 |   0.558882 |
| k-d_tree_pandas      |     9.08445  |       0.441927 |   0.693609 |
| k-d_tree_sklearn     |     3.10811  |       1.09864  |   1.13045  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535196 |       0.435659 |   0.435158 |
| barab-szabi-1        |     0.539804 |       0.412764 |   0.438887 |
| k-d_tree_polars      |     0.534063 |       0.416185 |   0.441765 |
| Bori_Aron_solution-1 |     0.53304  |       0.572084 |   0.551775 |
| k-d_tree_pandas      |     0.533693 |       0.393548 |   0.562251 |
| k-d_tree_sklearn     |     0.541906 |       0.985317 |   1.11126  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547427 |       0.454074 |   0.457772 |
| barab-szabi-1        |     0.531421 |       0.439927 |   0.468933 |
| k-d_tree_polars      |     0.542143 |       0.440902 |   0.470151 |
| Bori_Aron_solution-1 |     0.532527 |       0.60549  |   0.553996 |
| k-d_tree_pandas      |     0.541634 |       0.423042 |   0.615591 |
| k-d_tree_sklearn     |     0.543929 |       1.04943  |   1.10181  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534494 |       0.514077 |   0.477105 |
| k-d_tree_polars      |     0.531524 |       0.569532 |   0.563155 |
| Bori_Aron_solution-1 |     0.533654 |       0.79088  |   0.576576 |
| barab-szabi-1        |     0.547382 |       0.572321 |   0.579751 |
| k-d_tree_pandas      |     0.541988 |       0.50634  |   0.74172  |
| k-d_tree_sklearn     |     0.543296 |       1.27039  |   1.16999  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542039 |       0.760113 |   0.51127  |
| Bori_Aron_solution-1 |     0.53383  |       1.48132  |   0.605149 |
| k-d_tree_polars      |     0.540742 |       0.935066 |   0.926236 |
| barab-szabi-1        |     0.537413 |       0.934645 |   0.973482 |
| k-d_tree_pandas      |     0.539175 |       0.821843 |   1.2134   |
| k-d_tree_sklearn     |     0.539045 |       2.15346  |   1.23715  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534609 |        5.35223 |   0.76224  |
| Bori_Aron_solution-1 |     0.532125 |       11.0766  |   0.848984 |
| k-d_tree_sklearn     |     0.546906 |       17.323   |   1.35032  |
| k-d_tree_polars      |     0.542697 |        5.453   |   6.67853  |
| barab-szabi-1        |     0.534948 |        5.50318 |   6.70011  |
| k-d_tree_pandas      |     0.534294 |        4.48646 |   7.08872  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541273 |        79.6714 |    2.79288 |
| k-d_tree_sklearn     |     0.54897  |       240.51   |    4.18532 |
| Bori_Aron_solution-1 |     0.676026 |       151.295  |   17.5156  |