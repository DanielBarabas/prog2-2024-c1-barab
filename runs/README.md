# 2025-06-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.519771 |       0.385524 |   0.408083 |
| barab-szabi-2        |     0.54574  |       0.411024 |   0.409094 |
| solution-1           |     7.81019  |       1e-06    |   0.458003 |
| k-d_tree_pandas      |     0.535787 |       0.38089  |   0.535368 |
| Bori_Aron_solution-1 |     0.529648 |       0.528825 |   0.536039 |
| barab-szabi-1        |     8.12866  |       0.436151 |   0.59804  |
| k-d_tree_sklearn     |     3.10196  |       1.06499  |   1.02652  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.545976 |       0.398499 |   0.413801 |
| barab-szabi-2        |     0.528301 |       0.405642 |   0.414186 |
| barab-szabi-1        |     0.564823 |       0.403979 |   0.417482 |
| Bori_Aron_solution-1 |     0.536556 |       0.538115 |   0.531371 |
| k-d_tree_pandas      |     0.545375 |       0.369428 |   0.549719 |
| k-d_tree_sklearn     |     0.544941 |       0.975934 |   1.02003  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54493  |       0.421753 |   0.429767 |
| k-d_tree_polars      |     0.544287 |       0.426932 |   0.44357  |
| barab-szabi-1        |     0.542097 |       0.425595 |   0.445828 |
| Bori_Aron_solution-1 |     0.533899 |       0.581963 |   0.53278  |
| k-d_tree_pandas      |     0.538888 |       0.392818 |   0.583998 |
| k-d_tree_sklearn     |     0.544317 |       0.993692 |   1.05243  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534369 |       0.487397 |   0.45393  |
| Bori_Aron_solution-1 |     0.543829 |       0.744061 |   0.536862 |
| barab-szabi-1        |     0.546462 |       0.534388 |   0.545193 |
| k-d_tree_polars      |     0.545119 |       0.53507  |   0.556133 |
| k-d_tree_pandas      |     0.535088 |       0.473374 |   0.718157 |
| k-d_tree_sklearn     |     0.550595 |       1.20497  |   1.11199  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534636 |       0.728352 |   0.481065 |
| Bori_Aron_solution-1 |     0.543712 |       1.38063  |   0.583308 |
| k-d_tree_polars      |     0.542453 |       0.874393 |   0.887334 |
| barab-szabi-1        |     0.544863 |       0.858172 |   0.923675 |
| k-d_tree_pandas      |     0.544521 |       0.750287 |   1.15971  |
| k-d_tree_sklearn     |     0.559466 |       2.01859  |   1.18294  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543959 |        5.29199 |   0.727932 |
| Bori_Aron_solution-1 |     0.528842 |       10.2968  |   0.826208 |
| k-d_tree_sklearn     |     0.549024 |       16.832   |   1.27548  |
| k-d_tree_polars      |     0.539835 |        4.92846 |   6.4624   |
| barab-szabi-1        |     0.54359  |        4.79872 |   6.50495  |
| k-d_tree_pandas      |     0.540709 |        3.81085 |   7.03673  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577541 |         71.128 |    2.74242 |
| k-d_tree_sklearn     |     0.67703  |        227.827 |    3.9707  |
| Bori_Aron_solution-1 |     0.53515  |        137.427 |   18.3284  |