# 2025-05-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35265  |       1e-06    |   0.360281 |
| barab-szabi-2        |     0.525145 |       0.416164 |   0.412874 |
| barab-szabi-1        |     0.509494 |       0.407208 |   0.422685 |
| k-d_tree_polars      |     3.9859   |       0.404509 |   0.4244   |
| Bori_Aron_solution-1 |     4.45892  |       0.535143 |   0.483152 |
| k-d_tree_pandas      |     0.525535 |       0.393229 |   0.544899 |
| k-d_tree_sklearn     |     2.91971  |       1.00398  |   1.04164  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.520498 |       0.416088 |   0.4159   |
| k-d_tree_polars      |     0.57358  |       0.422985 |   0.425197 |
| barab-szabi-1        |     0.532223 |       0.422894 |   0.430347 |
| Bori_Aron_solution-1 |     0.517397 |       0.564128 |   0.555056 |
| k-d_tree_pandas      |     0.532896 |       0.392996 |   0.568194 |
| k-d_tree_sklearn     |     0.532384 |       0.98716  |   1.03657  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523941 |       0.426118 |   0.431216 |
| k-d_tree_polars      |     0.526641 |       0.463856 |   0.44743  |
| barab-szabi-1        |     0.522226 |       0.437631 |   0.45052  |
| Bori_Aron_solution-1 |     0.519562 |       0.599464 |   0.552665 |
| k-d_tree_pandas      |     0.535068 |       0.412908 |   0.600872 |
| k-d_tree_sklearn     |     0.525271 |       1.03059  |   1.06267  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525997 |       0.486377 |   0.455401 |
| k-d_tree_polars      |     0.524638 |       0.549448 |   0.544991 |
| barab-szabi-1        |     0.519465 |       0.552819 |   0.561673 |
| Bori_Aron_solution-1 |     0.525346 |       0.766205 |   0.571023 |
| k-d_tree_pandas      |     0.529667 |       0.493132 |   0.74022  |
| k-d_tree_sklearn     |     0.529031 |       1.23928  |   1.13435  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522207 |       0.722706 |   0.486434 |
| Bori_Aron_solution-1 |     0.515707 |       1.39072  |   0.593616 |
| k-d_tree_polars      |     0.522709 |       0.88209  |   0.888167 |
| barab-szabi-1        |     0.52176  |       0.890562 |   0.931793 |
| k-d_tree_pandas      |     0.522917 |       0.7624   |   1.16993  |
| k-d_tree_sklearn     |     0.52753  |       2.06577  |   1.2183   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525939 |        5.37157 |   0.719391 |
| Bori_Aron_solution-1 |     0.514    |       10.9534  |   0.890327 |
| k-d_tree_sklearn     |     0.531137 |       16.4278  |   1.31688  |
| k-d_tree_polars      |     0.531246 |        5.11013 |   6.63756  |
| barab-szabi-1        |     0.528319 |        5.10418 |   6.74601  |
| k-d_tree_pandas      |     0.531334 |        3.96119 |   7.09158  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606669 |        74.9374 |    2.92431 |
| k-d_tree_sklearn     |     0.79233  |       234.869  |    4.46991 |
| Bori_Aron_solution-1 |     0.524085 |       154.088  |   17.0705  |