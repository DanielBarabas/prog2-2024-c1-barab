# 2024-04-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.700115 |       0.397783 |   0.334104 |
| barab-szabi-2        |     0.69691  |       0.346255 |   0.346057 |
| barab-szabi-1        |     8.61524  |       0.413949 |   0.361891 |
| solution-1           |     8.18535  |       1e-06    |   0.369722 |
| Bori_Aron_solution-1 |     0.69259  |       0.465415 |   0.467403 |
| k-d_tree_pandas      |     0.706257 |       0.376076 |   0.46983  |
| k-d_tree_sklearn     |     3.36188  |       0.866241 |   0.676737 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738554 |       0.35638  |   0.346702 |
| barab-szabi-1        |     0.748047 |       0.406675 |   0.347616 |
| k-d_tree_polars      |     0.736228 |       0.428812 |   0.353134 |
| Bori_Aron_solution-1 |     0.721311 |       0.478503 |   0.474776 |
| k-d_tree_pandas      |     0.738204 |       0.391854 |   0.495356 |
| k-d_tree_sklearn     |     0.746624 |       0.838831 |   0.666311 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725885 |       0.358041 |   0.350502 |
| barab-szabi-1        |     0.732572 |       0.427537 |   0.373857 |
| k-d_tree_polars      |     0.725964 |       0.434277 |   0.376626 |
| Bori_Aron_solution-1 |     0.720589 |       0.512151 |   0.47755  |
| k-d_tree_pandas      |     0.733217 |       0.399756 |   0.520541 |
| k-d_tree_sklearn     |     0.731119 |       0.883914 |   0.690386 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732037 |       0.428857 |   0.387515 |
| k-d_tree_polars      |     0.727346 |       0.547219 |   0.473464 |
| barab-szabi-1        |     0.730991 |       0.538367 |   0.483273 |
| Bori_Aron_solution-1 |     0.720931 |       0.689434 |   0.484473 |
| k-d_tree_pandas      |     0.728197 |       0.491121 |   0.661186 |
| k-d_tree_sklearn     |     0.744731 |       1.11818  |   0.750165 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730345 |       0.683466 |   0.428865 |
| Bori_Aron_solution-1 |     0.716323 |       1.33272  |   0.508217 |
| k-d_tree_polars      |     0.739819 |       0.850829 |   0.823083 |
| k-d_tree_sklearn     |     0.731584 |       1.89867  |   0.844935 |
| barab-szabi-1        |     0.733822 |       0.866144 |   0.856702 |
| k-d_tree_pandas      |     0.734919 |       0.748482 |   1.08816  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723457 |        5.10386 |   0.709861 |
| Bori_Aron_solution-1 |     0.718047 |       10.3998  |   0.762071 |
| k-d_tree_sklearn     |     0.738324 |       15.2011  |   1.03374  |
| k-d_tree_polars      |     0.727858 |        4.81115 |   6.34995  |
| barab-szabi-1        |     0.7299   |        4.88567 |   6.37057  |
| k-d_tree_pandas      |     0.727072 |        3.89874 |   6.69284  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.994983 |        73.3817 |    3.8968  |
| k-d_tree_sklearn     |     0.981003 |       226.511  |    4.89802 |
| Bori_Aron_solution-1 |     0.72143  |       147.152  |   17.0237  |