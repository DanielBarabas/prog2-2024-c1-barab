# 2025-08-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.37908  |       1e-06    |   0.389575 |
| k-d_tree_polars      |     0.556782 |       0.404194 |   0.42615  |
| barab-szabi-2        |     8.1286   |       0.523118 |   0.430281 |
| barab-szabi-1        |     0.568876 |       0.410119 |   0.439859 |
| k-d_tree_pandas      |     0.558692 |       0.39321  |   0.559    |
| Bori_Aron_solution-1 |     0.552556 |       0.562324 |   0.56928  |
| k-d_tree_sklearn     |     2.99756  |       1.05455  |   1.06847  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.558004 |       0.415897 |   0.431628 |
| barab-szabi-2        |     0.551881 |       0.456478 |   0.432397 |
| k-d_tree_polars      |     0.555926 |       0.415452 |   0.433516 |
| Bori_Aron_solution-1 |     0.548698 |       0.557257 |   0.555717 |
| k-d_tree_pandas      |     0.557161 |       0.409896 |   0.56568  |
| k-d_tree_sklearn     |     0.559163 |       0.964021 |   1.09842  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55351  |       0.443406 |   0.448106 |
| barab-szabi-1        |     0.557585 |       0.442238 |   0.45878  |
| k-d_tree_polars      |     0.556403 |       0.441257 |   0.462449 |
| Bori_Aron_solution-1 |     0.547343 |       0.593124 |   0.550626 |
| k-d_tree_pandas      |     0.555147 |       0.407133 |   0.59671  |
| k-d_tree_sklearn     |     0.557447 |       1.06126  |   1.09058  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552979 |       0.502694 |   0.470488 |
| k-d_tree_polars      |     0.555089 |       0.55185  |   0.554611 |
| Bori_Aron_solution-1 |     0.563687 |       0.770999 |   0.569276 |
| barab-szabi-1        |     0.562248 |       0.55213  |   0.574541 |
| k-d_tree_pandas      |     0.557026 |       0.495398 |   0.736735 |
| k-d_tree_sklearn     |     0.561987 |       1.24466  |   1.13552  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557051 |       0.745865 |   0.505267 |
| Bori_Aron_solution-1 |     0.553613 |       1.41719  |   0.593677 |
| k-d_tree_polars      |     0.551696 |       0.893328 |   0.911386 |
| barab-szabi-1        |     0.556982 |       0.895772 |   0.949938 |
| k-d_tree_pandas      |     0.554068 |       0.768473 |   1.17729  |
| k-d_tree_sklearn     |     0.559952 |       2.08766  |   1.21722  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554835 |        5.31538 |   0.747961 |
| Bori_Aron_solution-1 |     0.56296  |       10.8119  |   0.873795 |
| k-d_tree_sklearn     |     0.565038 |       16.8431  |   1.35087  |
| barab-szabi-1        |     0.558163 |        5.09298 |   6.80221  |
| k-d_tree_polars      |     0.573712 |        5.01078 |   6.85449  |
| k-d_tree_pandas      |     0.558595 |        3.95209 |   7.10491  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557589 |        74.5965 |    2.88216 |
| k-d_tree_sklearn     |     0.796223 |       234.658  |    4.09353 |
| Bori_Aron_solution-1 |     0.577957 |       145.912  |   18.361   |