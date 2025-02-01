# 2025-02-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.61513  |       0.529089 |   0.409914 |
| k-d_tree_polars      |     0.586578 |       0.409528 |   0.414943 |
| barab-szabi-1        |     0.608346 |       0.413246 |   0.416055 |
| solution-1           |     7.27349  |       1e-06    |   0.425946 |
| k-d_tree_pandas      |     0.603052 |       0.390457 |   0.55344  |
| Bori_Aron_solution-1 |     0.622001 |       0.540959 |   0.556054 |
| k-d_tree_sklearn     |     2.97094  |       1.04044  |   1.06167  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60626  |       0.412091 |   0.406552 |
| k-d_tree_polars      |     0.612062 |       0.414275 |   0.409796 |
| barab-szabi-1        |     0.61783  |       0.421128 |   0.415653 |
| Bori_Aron_solution-1 |     0.581337 |       0.551386 |   0.550219 |
| k-d_tree_pandas      |     0.595277 |       0.403695 |   0.564263 |
| k-d_tree_sklearn     |     0.615956 |       0.969637 |   1.05501  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59976  |       0.425501 |   0.422165 |
| k-d_tree_polars      |     0.601523 |       0.438289 |   0.439518 |
| barab-szabi-1        |     0.59597  |       0.4465   |   0.455064 |
| Bori_Aron_solution-1 |     0.588824 |       0.606594 |   0.55078  |
| k-d_tree_pandas      |     0.601636 |       0.42024  |   0.614676 |
| k-d_tree_sklearn     |     0.593561 |       1.02036  |   1.0736   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594737 |       0.482884 |   0.458444 |
| k-d_tree_polars      |     0.594938 |       0.539472 |   0.545644 |
| barab-szabi-1        |     0.598399 |       0.544232 |   0.548039 |
| Bori_Aron_solution-1 |     0.585794 |       0.752798 |   0.554466 |
| k-d_tree_pandas      |     0.588335 |       0.481824 |   0.739689 |
| k-d_tree_sklearn     |     0.597842 |       1.24673  |   1.12862  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598806 |       0.763769 |   0.4854   |
| Bori_Aron_solution-1 |     0.591605 |       1.41105  |   0.589826 |
| k-d_tree_polars      |     0.593029 |       0.875611 |   0.904058 |
| barab-szabi-1        |     0.596861 |       0.878646 |   0.939893 |
| k-d_tree_pandas      |     0.608025 |       0.752204 |   1.19093  |
| k-d_tree_sklearn     |     0.594314 |       2.1112   |   1.24324  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600158 |        5.618   |   0.766753 |
| Bori_Aron_solution-1 |     0.598937 |       10.8455  |   0.880372 |
| k-d_tree_sklearn     |     0.603808 |       16.9288  |   1.33969  |
| barab-szabi-1        |     0.598252 |        4.93716 |   6.77322  |
| k-d_tree_polars      |     0.604799 |        4.91732 |   6.84767  |
| k-d_tree_pandas      |     0.591723 |        3.84505 |   7.22278  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599435 |        78.5048 |    3.18001 |
| k-d_tree_sklearn     |     0.622909 |       240.661  |    4.40138 |
| Bori_Aron_solution-1 |     0.639088 |       146.016  |   18.1606  |