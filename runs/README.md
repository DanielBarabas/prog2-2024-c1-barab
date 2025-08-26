# 2025-08-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.562725 |       0.444486 |   0.447849 |
| barab-szabi-2        |     0.559199 |       0.470852 |   0.501121 |
| Bori_Aron_solution-1 |     0.576343 |       0.582528 |   0.573297 |
| barab-szabi-1        |     0.548779 |       0.523964 |   0.618811 |
| solution-1           |     7.61277  |       1e-06    |   0.810282 |
| k-d_tree_pandas      |     8.11705  |       0.490399 |   1.13392  |
| k-d_tree_sklearn     |     3.39303  |       1.28992  |   1.13537  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.565852 |       0.43143  |   0.456127 |
| barab-szabi-2        |     0.605717 |       0.465096 |   0.478838 |
| barab-szabi-1        |     0.597586 |       0.460406 |   0.497612 |
| Bori_Aron_solution-1 |     0.553128 |       0.597388 |   0.605513 |
| k-d_tree_pandas      |     0.582149 |       0.422868 |   0.631948 |
| k-d_tree_sklearn     |     0.607844 |       1.09756  |   1.14447  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558288 |       0.493997 |   0.465307 |
| k-d_tree_polars      |     0.583173 |       0.456027 |   0.468278 |
| barab-szabi-1        |     0.596495 |       0.526212 |   0.50483  |
| Bori_Aron_solution-1 |     0.558731 |       0.641634 |   0.569231 |
| k-d_tree_pandas      |     0.570045 |       0.446876 |   0.677028 |
| k-d_tree_sklearn     |     0.573923 |       1.114    |   1.17525  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570083 |       0.567868 |   0.521962 |
| k-d_tree_polars      |     0.570682 |       0.593315 |   0.573224 |
| barab-szabi-1        |     0.552994 |       0.568944 |   0.589894 |
| Bori_Aron_solution-1 |     0.551898 |       0.804179 |   0.589918 |
| k-d_tree_pandas      |     0.5705   |       0.506913 |   0.793585 |
| k-d_tree_sklearn     |     0.642096 |       1.31933  |   1.21564  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.582185 |       1.44476  |   0.644787 |
| barab-szabi-2        |     0.588713 |       0.796555 |   0.736742 |
| k-d_tree_polars      |     0.568214 |       0.936431 |   0.988236 |
| barab-szabi-1        |     0.55706  |       0.974684 |   1.00909  |
| k-d_tree_pandas      |     0.562444 |       0.780379 |   1.23345  |
| k-d_tree_sklearn     |     0.618955 |       2.19322  |   1.31207  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573946 |        5.77668 |   0.827087 |
| Bori_Aron_solution-1 |     0.562032 |       11.5267  |   0.887597 |
| k-d_tree_sklearn     |     0.595463 |       18.246   |   1.44063  |
| k-d_tree_polars      |     0.580677 |        5.18342 |   7.16622  |
| barab-szabi-1        |     0.607701 |        5.08505 |   7.3146   |
| k-d_tree_pandas      |     0.559684 |        3.99594 |   7.90539  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590763 |         73.477 |    2.80917 |
| k-d_tree_sklearn     |     0.572071 |        241.306 |    4.54142 |
| Bori_Aron_solution-1 |     0.661057 |        148.899 |   18.4788  |