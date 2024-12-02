# 2024-12-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35736  |       1e-06    |   0.351573 |
| barab-szabi-2        |     0.632863 |       0.386873 |   0.380387 |
| k-d_tree_polars      |     0.609529 |       0.395693 |   0.384751 |
| barab-szabi-1        |     0.617011 |       0.398765 |   0.391951 |
| Bori_Aron_solution-1 |     0.614779 |       0.519905 |   0.515769 |
| k-d_tree_pandas      |     0.613637 |       0.377881 |   0.528929 |
| k-d_tree_sklearn     |    10.2222   |       0.990185 |   0.9584   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614618 |       0.389782 |   0.390819 |
| barab-szabi-1        |     0.632944 |       0.405203 |   0.391838 |
| k-d_tree_polars      |     0.610982 |       0.406761 |   0.395233 |
| Bori_Aron_solution-1 |     0.612955 |       0.52941  |   0.518163 |
| k-d_tree_pandas      |     0.612815 |       0.383291 |   0.536209 |
| k-d_tree_sklearn     |     0.620082 |       0.874115 |   0.957967 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618426 |       0.415612 |   0.396547 |
| k-d_tree_polars      |     0.616584 |       0.429622 |   0.41859  |
| barab-szabi-1        |     0.62953  |       0.437639 |   0.427436 |
| Bori_Aron_solution-1 |     0.62807  |       0.570228 |   0.528054 |
| k-d_tree_pandas      |     0.624824 |       0.438039 |   0.604694 |
| k-d_tree_sklearn     |     0.623991 |       0.935693 |   0.987579 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622907 |       0.471328 |   0.427312 |
| k-d_tree_polars      |     0.612341 |       0.536989 |   0.518545 |
| barab-szabi-1        |     0.611222 |       0.541548 |   0.533144 |
| Bori_Aron_solution-1 |     0.606322 |       0.741673 |   0.537354 |
| k-d_tree_pandas      |     0.611581 |       0.483786 |   0.712597 |
| k-d_tree_sklearn     |     0.636134 |       1.17411  |   1.04807  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626404 |       0.714173 |   0.485265 |
| Bori_Aron_solution-1 |     0.605911 |       1.38242  |   0.556727 |
| k-d_tree_polars      |     0.621737 |       0.868933 |   0.894819 |
| barab-szabi-1        |     0.612321 |       0.867495 |   0.899302 |
| k-d_tree_pandas      |     0.616467 |       0.759405 |   1.13194  |
| k-d_tree_sklearn     |     0.617414 |       1.98184  |   1.13902  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617232 |        5.54494 |   0.740066 |
| Bori_Aron_solution-1 |     0.60778  |       10.9703  |   0.812633 |
| k-d_tree_sklearn     |     0.610629 |       16.1134  |   1.24201  |
| k-d_tree_polars      |     0.61213  |        4.90131 |   6.62301  |
| barab-szabi-1        |     0.619524 |        4.90656 |   6.6656   |
| k-d_tree_pandas      |     0.618076 |        3.89139 |   6.99957  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638833 |        71.8334 |    3.03256 |
| k-d_tree_sklearn     |     0.615748 |       227.796  |    4.20664 |
| Bori_Aron_solution-1 |     0.627639 |       156.27   |   17.5877  |