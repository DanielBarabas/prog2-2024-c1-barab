# 2026-01-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.898554 |       0.505588 |   0.425578 |
| barab-szabi-1        |     0.521174 |       0.396717 |   0.432557 |
| k-d_tree_polars      |     0.517992 |       0.39898  |   0.435267 |
| solution-1           |     8.65213  |       1e-06    |   0.509084 |
| Bori_Aron_solution-1 |     0.51461  |       0.542092 |   0.539945 |
| k-d_tree_pandas      |     9.47926  |       0.43153  |   0.677464 |
| k-d_tree_sklearn     |     3.15502  |       1.12147  |   1.06286  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517225 |       0.43847  |   0.431737 |
| k-d_tree_polars      |     0.533387 |       0.402756 |   0.434418 |
| barab-szabi-1        |     0.540148 |       0.410286 |   0.435882 |
| Bori_Aron_solution-1 |     0.510823 |       0.549958 |   0.537894 |
| k-d_tree_pandas      |     0.523816 |       0.390426 |   0.550226 |
| k-d_tree_sklearn     |     0.531291 |       0.98664  |   1.06788  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521328 |       0.44627  |   0.449703 |
| barab-szabi-1        |     0.535217 |       0.435704 |   0.463411 |
| k-d_tree_polars      |     0.520257 |       0.439011 |   0.474984 |
| Bori_Aron_solution-1 |     0.520263 |       0.596553 |   0.550634 |
| k-d_tree_pandas      |     0.524871 |       0.406698 |   0.593953 |
| k-d_tree_sklearn     |     0.529579 |       1.02007  |   1.11666  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518676 |       0.508731 |   0.48434  |
| Bori_Aron_solution-1 |     0.510283 |       0.777047 |   0.555338 |
| k-d_tree_polars      |     0.523235 |       0.552314 |   0.566099 |
| barab-szabi-1        |     0.520122 |       0.553686 |   0.566992 |
| k-d_tree_pandas      |     0.523236 |       0.498438 |   0.734552 |
| k-d_tree_sklearn     |     0.528893 |       1.26088  |   1.13144  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518847 |       0.728307 |   0.50198  |
| Bori_Aron_solution-1 |     0.511073 |       1.45332  |   0.585553 |
| k-d_tree_polars      |     0.529541 |       0.918509 |   0.91355  |
| barab-szabi-1        |     0.523922 |       0.917996 |   0.943977 |
| k-d_tree_pandas      |     0.518329 |       0.812473 |   1.17641  |
| k-d_tree_sklearn     |     0.526942 |       2.10131  |   1.20665  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52597  |        5.19727 |   0.782192 |
| Bori_Aron_solution-1 |     0.516583 |       11.7902  |   0.890432 |
| k-d_tree_sklearn     |     0.54069  |       16.8619  |   1.30985  |
| k-d_tree_polars      |     0.523264 |        5.52077 |   6.74808  |
| barab-szabi-1        |     0.526152 |        5.67529 |   6.7866   |
| k-d_tree_pandas      |     0.522041 |        4.44383 |   7.15074  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552507 |        72.0853 |    2.78229 |
| k-d_tree_sklearn     |     0.556215 |       234.572  |    4.13123 |
| Bori_Aron_solution-1 |     0.647298 |       147.903  |   18.0123  |