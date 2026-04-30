# 2026-04-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.466959 |       0.403468 |   0.433139 |
| k-d_tree_polars      |     0.452545 |       0.401487 |   0.436296 |
| barab-szabi-2        |     0.462008 |       0.489572 |   0.440512 |
| Bori_Aron_solution-1 |     0.454732 |       0.541676 |   0.549773 |
| k-d_tree_pandas      |     0.4632   |       0.393887 |   0.55002  |
| solution-1           |     7.58915  |       1e-06    |   0.564085 |
| k-d_tree_sklearn     |    10.4602   |       4.71959  |   1.09016  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457052 |       0.43353  |   0.437273 |
| barab-szabi-1        |     0.457505 |       0.409878 |   0.438365 |
| k-d_tree_polars      |     0.454767 |       0.420858 |   0.445658 |
| Bori_Aron_solution-1 |     0.452673 |       0.55016  |   0.552323 |
| k-d_tree_pandas      |     0.4838   |       0.390565 |   0.562555 |
| k-d_tree_sklearn     |     0.456515 |       0.97481  |   1.09451  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.462105 |       0.442432 |   0.46776  |
| k-d_tree_polars      |     0.457105 |       0.437022 |   0.472408 |
| barab-szabi-2        |     0.462805 |       0.449754 |   0.478431 |
| Bori_Aron_solution-1 |     0.449237 |       0.596291 |   0.554776 |
| k-d_tree_pandas      |     0.455927 |       0.414488 |   0.59927  |
| k-d_tree_sklearn     |     0.463532 |       1.03999  |   1.09946  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453522 |       0.508503 |   0.476804 |
| k-d_tree_polars      |     0.458528 |       0.560153 |   0.555848 |
| Bori_Aron_solution-1 |     0.449795 |       0.783266 |   0.556425 |
| barab-szabi-1        |     0.466996 |       0.569069 |   0.583345 |
| k-d_tree_pandas      |     0.455146 |       0.509501 |   0.742103 |
| k-d_tree_sklearn     |     0.458407 |       1.2732   |   1.1296   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457641 |       0.737603 |   0.518443 |
| Bori_Aron_solution-1 |     0.451634 |       1.45523  |   0.585809 |
| k-d_tree_polars      |     0.461277 |       0.94004  |   0.927842 |
| barab-szabi-1        |     0.458885 |       0.9335   |   0.962135 |
| k-d_tree_pandas      |     0.456518 |       0.81896  |   1.17887  |
| k-d_tree_sklearn     |     0.466818 |       2.1394   |   1.20819  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456805 |        5.25519 |   0.754226 |
| Bori_Aron_solution-1 |     0.452753 |       11.1754  |   0.813562 |
| k-d_tree_sklearn     |     0.461598 |       17.4323  |   1.30083  |
| k-d_tree_polars      |     0.457397 |        5.45719 |   6.82187  |
| barab-szabi-1        |     0.457297 |        5.43317 |   7.05511  |
| k-d_tree_pandas      |     0.4595   |        4.48063 |   7.18889  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.715016 |        73.9392 |    2.74031 |
| k-d_tree_sklearn     |     0.464754 |       243.369  |    3.72888 |
| Bori_Aron_solution-1 |     0.457373 |       154.236  |   18.0825  |