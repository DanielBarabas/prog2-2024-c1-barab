# 2025-09-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.38395  |       0.907331 |   0.425589 |
| k-d_tree_polars      |     0.545097 |       0.415941 |   0.432308 |
| barab-szabi-1        |     0.52925  |       0.413275 |   0.433461 |
| Bori_Aron_solution-1 |     0.522298 |       0.546766 |   0.546882 |
| k-d_tree_pandas      |     0.5327   |       0.385095 |   0.561854 |
| solution-1           |     7.76065  |       1e-06    |   0.570408 |
| k-d_tree_sklearn     |     3.15203  |       1.21751  |   1.06721  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545033 |       0.436222 |   0.431428 |
| barab-szabi-1        |     0.555154 |       0.412008 |   0.438039 |
| k-d_tree_polars      |     0.547474 |       0.416493 |   0.439952 |
| Bori_Aron_solution-1 |     0.546171 |       0.555344 |   0.560728 |
| k-d_tree_pandas      |     0.549474 |       0.399041 |   0.565177 |
| k-d_tree_sklearn     |     0.552263 |       0.976038 |   1.08083  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546854 |       0.441297 |   0.44216  |
| k-d_tree_polars      |     0.559372 |       0.441088 |   0.464352 |
| barab-szabi-1        |     0.547807 |       0.446323 |   0.46721  |
| Bori_Aron_solution-1 |     0.542148 |       0.5996   |   0.553349 |
| k-d_tree_pandas      |     0.551855 |       0.419437 |   0.605994 |
| k-d_tree_sklearn     |     0.559216 |       1.02572  |   1.1034   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549279 |       0.499318 |   0.468012 |
| k-d_tree_polars      |     0.545809 |       0.551859 |   0.552481 |
| barab-szabi-1        |     0.543996 |       0.553959 |   0.570559 |
| Bori_Aron_solution-1 |     0.538033 |       0.772792 |   0.578393 |
| k-d_tree_pandas      |     0.543612 |       0.492946 |   0.738854 |
| k-d_tree_sklearn     |     0.549955 |       1.25958  |   1.14459  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541718 |       0.764424 |   0.504327 |
| Bori_Aron_solution-1 |     0.541056 |       1.41201  |   0.591161 |
| k-d_tree_polars      |     0.54499  |       0.890954 |   0.928449 |
| barab-szabi-1        |     0.545947 |       0.893153 |   0.96104  |
| k-d_tree_pandas      |     0.543712 |       0.770648 |   1.19041  |
| k-d_tree_sklearn     |     0.550055 |       2.10393  |   1.23483  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55133  |        5.44189 |   0.735034 |
| Bori_Aron_solution-1 |     0.539045 |       10.7116  |   0.843967 |
| k-d_tree_sklearn     |     0.566161 |       16.552   |   1.3389   |
| k-d_tree_polars      |     0.547988 |        5.06827 |   6.71702  |
| barab-szabi-1        |     0.538288 |        5.04962 |   6.75354  |
| k-d_tree_pandas      |     0.548815 |        3.95132 |   7.16691  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544335 |        73.1938 |    2.72905 |
| k-d_tree_sklearn     |     1.16823  |       231.522  |    4.05399 |
| Bori_Aron_solution-1 |     0.551909 |       144.119  |   17.643   |