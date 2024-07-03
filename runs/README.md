# 2024-07-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54635  |       0.380682 |   0.372832 |
| barab-szabi-1        |     0.554636 |       0.386452 |   0.382515 |
| k-d_tree_polars      |     0.540257 |       0.397846 |   0.394563 |
| Bori_Aron_solution-1 |     0.532484 |       0.508472 |   0.508357 |
| solution-1           |     7.84379  |       1e-06    |   0.573852 |
| k-d_tree_sklearn     |     3.07949  |       1.07154  |   0.689785 |
| k-d_tree_pandas      |     8.20778  |       0.405524 |   0.740918 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566625 |       0.387374 |   0.378895 |
| barab-szabi-1        |     0.555874 |       0.40214  |   0.383212 |
| k-d_tree_polars      |     0.555098 |       0.393955 |   0.390893 |
| Bori_Aron_solution-1 |     0.543992 |       0.521061 |   0.509592 |
| k-d_tree_pandas      |     0.552158 |       0.377226 |   0.518613 |
| k-d_tree_sklearn     |     0.55253  |       0.880611 |   0.693748 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55315  |       0.401125 |   0.390624 |
| k-d_tree_polars      |     0.547775 |       0.418761 |   0.412473 |
| barab-szabi-1        |     0.548615 |       0.416587 |   0.416059 |
| Bori_Aron_solution-1 |     0.54288  |       0.556561 |   0.516596 |
| k-d_tree_pandas      |     0.548923 |       0.4066   |   0.56795  |
| k-d_tree_sklearn     |     0.553339 |       0.929628 |   0.717603 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549241 |       0.461279 |   0.422586 |
| k-d_tree_polars      |     0.561111 |       0.539995 |   0.510098 |
| barab-szabi-1        |     0.552224 |       0.526473 |   0.520617 |
| Bori_Aron_solution-1 |     0.540963 |       0.729268 |   0.526926 |
| k-d_tree_pandas      |     0.577018 |       0.477739 |   0.715477 |
| k-d_tree_sklearn     |     0.555238 |       1.15256  |   0.774508 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551307 |       0.701217 |   0.459569 |
| Bori_Aron_solution-1 |     0.543833 |       1.37078  |   0.556773 |
| k-d_tree_polars      |     0.549756 |       0.848033 |   0.855415 |
| k-d_tree_sklearn     |     0.556133 |       1.93862  |   0.877904 |
| barab-szabi-1        |     0.553855 |       0.848743 |   0.898481 |
| k-d_tree_pandas      |     0.552146 |       0.734159 |   1.13052  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569859 |        5.60849 |   0.770114 |
| Bori_Aron_solution-1 |     0.548355 |       10.8975  |   0.875031 |
| k-d_tree_sklearn     |     0.5768   |       17.2721  |   1.08718  |
| k-d_tree_polars      |     0.549744 |        4.75962 |   6.4789   |
| k-d_tree_pandas      |     0.55062  |        3.864   |   6.84834  |
| barab-szabi-1        |     0.568752 |        4.92345 |   6.99536  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703773 |        74.8296 |    4.0208  |
| k-d_tree_sklearn     |     0.613166 |       222.206  |    4.16922 |
| Bori_Aron_solution-1 |     0.557261 |       149.034  |   15.6354  |