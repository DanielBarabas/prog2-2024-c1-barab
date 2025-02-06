# 2025-02-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.588951 |       0.417581 |   0.40924  |
| barab-szabi-2        |     7.97904  |       0.589187 |   0.417722 |
| k-d_tree_polars      |     0.593447 |       0.442676 |   0.420367 |
| solution-1           |     7.39982  |       1e-06    |   0.442412 |
| k-d_tree_pandas      |     0.603439 |       0.389909 |   0.538446 |
| Bori_Aron_solution-1 |     0.600586 |       0.543389 |   0.548949 |
| k-d_tree_sklearn     |     3.12108  |       1.05439  |   1.11686  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596731 |       0.408264 |   0.405828 |
| barab-szabi-1        |     0.586038 |       0.405975 |   0.410224 |
| k-d_tree_polars      |     0.591547 |       0.408206 |   0.413764 |
| Bori_Aron_solution-1 |     0.595332 |       0.547228 |   0.52972  |
| k-d_tree_pandas      |     0.5836   |       0.388586 |   0.549323 |
| k-d_tree_sklearn     |     0.589818 |       0.965741 |   1.03596  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583138 |       0.418752 |   0.412519 |
| barab-szabi-1        |     0.587596 |       0.432199 |   0.433631 |
| k-d_tree_polars      |     0.586709 |       0.430815 |   0.435181 |
| Bori_Aron_solution-1 |     0.59693  |       0.58059  |   0.535759 |
| k-d_tree_pandas      |     0.588168 |       0.406634 |   0.5884   |
| k-d_tree_sklearn     |     0.589215 |       1.03767  |   1.11883  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583237 |       0.480867 |   0.446374 |
| k-d_tree_polars      |     0.585403 |       0.559446 |   0.534027 |
| Bori_Aron_solution-1 |     0.580928 |       0.747416 |   0.549445 |
| barab-szabi-1        |     0.586159 |       0.54898  |   0.550776 |
| k-d_tree_pandas      |     0.604162 |       0.480844 |   0.722208 |
| k-d_tree_sklearn     |     0.594607 |       1.21871  |   1.13166  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585578 |       0.727132 |   0.480177 |
| Bori_Aron_solution-1 |     0.576966 |       1.36612  |   0.57607  |
| k-d_tree_polars      |     0.586115 |       0.875978 |   0.879327 |
| barab-szabi-1        |     0.587411 |       0.867442 |   0.918429 |
| k-d_tree_pandas      |     0.584352 |       0.740838 |   1.15769  |
| k-d_tree_sklearn     |     0.588788 |       2.01607  |   1.19676  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586343 |        5.12875 |   0.755467 |
| Bori_Aron_solution-1 |     0.572014 |       10.3985  |   0.87308  |
| k-d_tree_sklearn     |     0.583231 |       15.3956  |   1.30513  |
| k-d_tree_polars      |     0.578616 |        4.90697 |   6.30198  |
| barab-szabi-1        |     0.58104  |        4.89966 |   6.49463  |
| k-d_tree_pandas      |     0.582612 |        3.82677 |   6.77971  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584689 |        73.6713 |    3.20133 |
| k-d_tree_sklearn     |     0.591157 |       228.719  |    4.58848 |
| Bori_Aron_solution-1 |     0.679176 |       152.022  |   15.8111  |