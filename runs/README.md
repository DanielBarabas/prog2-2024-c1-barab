# 2025-08-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7298   |       1e-06    |   0.375517 |
| k-d_tree_polars      |     0.552212 |       0.422566 |   0.435    |
| barab-szabi-2        |     0.542777 |       0.436954 |   0.448643 |
| Bori_Aron_solution-1 |     0.54421  |       0.555677 |   0.556608 |
| barab-szabi-1        |     0.536352 |       0.435299 |   0.572237 |
| k-d_tree_pandas      |     8.45297  |       0.440856 |   0.787085 |
| k-d_tree_sklearn     |     3.35059  |       1.14643  |   1.10884  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557717 |       0.44699  |   0.437506 |
| k-d_tree_polars      |     0.555706 |       0.422733 |   0.439348 |
| barab-szabi-1        |     0.577688 |       0.431563 |   0.441907 |
| k-d_tree_pandas      |     0.551577 |       0.394961 |   0.562019 |
| Bori_Aron_solution-1 |     0.550574 |       0.59351  |   0.585551 |
| k-d_tree_sklearn     |     0.548738 |       0.987994 |   1.07436  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565235 |       0.459041 |   0.455709 |
| k-d_tree_polars      |     0.579749 |       0.45016  |   0.47181  |
| barab-szabi-1        |     0.580199 |       0.451932 |   0.472353 |
| Bori_Aron_solution-1 |     0.562464 |       0.618741 |   0.56831  |
| k-d_tree_pandas      |     0.553851 |       0.422547 |   0.613535 |
| k-d_tree_sklearn     |     0.560668 |       1.0522   |   1.10424  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550087 |       0.524964 |   0.485086 |
| k-d_tree_polars      |     0.57496  |       0.578512 |   0.570715 |
| barab-szabi-1        |     0.585245 |       0.565082 |   0.574923 |
| Bori_Aron_solution-1 |     0.569254 |       0.813371 |   0.594201 |
| k-d_tree_pandas      |     0.565526 |       0.526684 |   0.827314 |
| k-d_tree_sklearn     |     0.581276 |       1.29241  |   1.23507  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560684 |       0.792432 |   0.518289 |
| Bori_Aron_solution-1 |     0.568316 |       1.47623  |   0.633372 |
| k-d_tree_polars      |     0.570028 |       0.907254 |   0.952308 |
| barab-szabi-1        |     0.571873 |       0.913615 |   0.967905 |
| k-d_tree_pandas      |     0.561981 |       0.783736 |   1.22264  |
| k-d_tree_sklearn     |     0.577736 |       2.18572  |   1.31373  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559339 |        5.62253 |   0.789738 |
| Bori_Aron_solution-1 |     0.566628 |       10.8942  |   0.87169  |
| k-d_tree_sklearn     |     0.587729 |       17.3464  |   1.45456  |
| barab-szabi-1        |     0.552612 |        5.12559 |   6.83899  |
| k-d_tree_polars      |     0.589456 |        5.07508 |   7.03582  |
| k-d_tree_pandas      |     0.582733 |        3.98545 |   7.2062   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552035 |        75.5395 |    2.83693 |
| k-d_tree_sklearn     |     0.568619 |       240.838  |    4.32633 |
| Bori_Aron_solution-1 |     0.774914 |       145.054  |   17.9283  |