# 2026-10-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.14415  |       2e-06    |   0.390072 |
| barab-szabi-2        |     0.425302 |       0.415016 |   0.411499 |
| k-d_tree_polars      |     0.426471 |       0.402794 |   0.420197 |
| Bori_Aron_solution-1 |     0.419902 |       0.518707 |   0.523227 |
| k-d_tree_pandas      |     0.440326 |       0.370064 |   0.526329 |
| barab-szabi-1        |     7.46681  |       0.494454 |   0.551869 |
| k-d_tree_sklearn     |     2.87493  |       1.20302  |   1.01589  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432473 |       0.413536 |   0.412072 |
| k-d_tree_polars      |     0.443157 |       0.404194 |   0.422422 |
| barab-szabi-1        |     0.436912 |       0.488206 |   0.453993 |
| Bori_Aron_solution-1 |     0.431953 |       0.533684 |   0.525891 |
| k-d_tree_pandas      |     0.440973 |       0.371508 |   0.534347 |
| k-d_tree_sklearn     |     0.438122 |       0.927888 |   1.02103  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430643 |       0.423876 |   0.424341 |
| barab-szabi-1        |     0.432824 |       0.432944 |   0.434191 |
| k-d_tree_polars      |     0.435701 |       0.435746 |   0.449521 |
| Bori_Aron_solution-1 |     0.427618 |       0.563756 |   0.524909 |
| k-d_tree_pandas      |     0.434045 |       0.389838 |   0.566333 |
| k-d_tree_sklearn     |     0.443305 |       0.975481 |   1.03701  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.440568 |       0.492996 |   0.450517 |
| k-d_tree_polars      |     0.446211 |       0.54865  |   0.532962 |
| barab-szabi-1        |     0.435364 |       0.548291 |   0.546618 |
| Bori_Aron_solution-1 |     0.429306 |       0.744926 |   0.554484 |
| k-d_tree_pandas      |     0.444287 |       0.472812 |   0.688675 |
| k-d_tree_sklearn     |     0.441747 |       1.21567  |   1.07998  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449406 |       0.728152 |   0.495776 |
| Bori_Aron_solution-1 |     0.435331 |       1.32437  |   0.560623 |
| k-d_tree_polars      |     0.433177 |       0.861167 |   0.859901 |
| barab-szabi-1        |     0.444831 |       0.854325 |   0.900327 |
| k-d_tree_pandas      |     0.434889 |       0.72949  |   1.10537  |
| k-d_tree_sklearn     |     0.446009 |       1.95262  |   1.13711  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.437653 |        5.05843 |   0.698222 |
| Bori_Aron_solution-1 |     0.430193 |        9.87234 |   0.883379 |
| k-d_tree_sklearn     |     0.447546 |       15.1368  |   1.2829   |
| barab-szabi-1        |     0.435989 |        4.76672 |   6.15925  |
| k-d_tree_polars      |     0.438549 |        4.78397 |   6.33689  |
| k-d_tree_pandas      |     0.434312 |        3.76894 |   6.49902  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.669582 |        69.0208 |    2.75772 |
| k-d_tree_sklearn     |     0.555418 |       180.231  |    3.97747 |
| Bori_Aron_solution-1 |     0.43288  |       143.3    |   15.0637  |