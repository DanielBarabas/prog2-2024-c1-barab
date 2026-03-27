# 2026-03-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.477814 |       0.420034 |   0.446794 |
| barab-szabi-2        |     0.474224 |       0.449463 |   0.452245 |
| solution-1           |     8.3846   |       1e-06    |   0.536746 |
| k-d_tree_pandas      |     0.486031 |       0.395274 |   0.566628 |
| Bori_Aron_solution-1 |     0.490847 |       0.572946 |   0.571093 |
| barab-szabi-1        |     7.99107  |       0.507623 |   0.641392 |
| k-d_tree_sklearn     |     3.00209  |       1.22282  |   1.11434  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.477674 |       0.420624 |   0.452257 |
| barab-szabi-2        |     0.473879 |       0.445527 |   0.454985 |
| k-d_tree_polars      |     0.48616  |       0.425137 |   0.46113  |
| Bori_Aron_solution-1 |     0.47082  |       0.591742 |   0.573133 |
| k-d_tree_pandas      |     0.487965 |       0.420316 |   0.586964 |
| k-d_tree_sklearn     |     0.484465 |       1.02357  |   1.11385  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47428  |       0.475484 |   0.466495 |
| k-d_tree_polars      |     0.483134 |       0.450468 |   0.480664 |
| barab-szabi-1        |     0.476505 |       0.46033  |   0.486796 |
| Bori_Aron_solution-1 |     0.472592 |       0.605969 |   0.566345 |
| k-d_tree_pandas      |     0.473077 |       0.420981 |   0.615535 |
| k-d_tree_sklearn     |     0.490811 |       1.08432  |   1.15278  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473147 |       0.521141 |   0.499265 |
| k-d_tree_polars      |     0.484502 |       0.56942  |   0.583667 |
| barab-szabi-1        |     0.481759 |       0.581824 |   0.583782 |
| Bori_Aron_solution-1 |     0.472479 |       0.799031 |   0.590588 |
| k-d_tree_pandas      |     0.4806   |       0.520237 |   0.781471 |
| k-d_tree_sklearn     |     0.494344 |       1.32167  |   1.20469  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475023 |       0.747512 |   0.551952 |
| Bori_Aron_solution-1 |     0.474696 |       1.48733  |   0.613874 |
| k-d_tree_polars      |     0.481922 |       0.954373 |   0.958367 |
| barab-szabi-1        |     0.47938  |       0.96725  |   0.990745 |
| k-d_tree_pandas      |     0.481207 |       0.832995 |   1.21292  |
| k-d_tree_sklearn     |     0.483823 |       2.22593  |   1.27879  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497882 |        5.25634 |   0.77438  |
| Bori_Aron_solution-1 |     0.471121 |       11.4054  |   0.840647 |
| k-d_tree_sklearn     |     0.482383 |       17.6722  |   1.3378   |
| k-d_tree_polars      |     0.481515 |        5.61681 |   6.91729  |
| barab-szabi-1        |     0.473004 |        5.56701 |   6.92725  |
| k-d_tree_pandas      |     0.486095 |        4.41781 |   7.27415  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.694768 |        75.4185 |    2.85186 |
| k-d_tree_sklearn     |     0.483215 |       252.464  |    3.89938 |
| Bori_Aron_solution-1 |     0.497922 |       162.192  |   16.4007  |