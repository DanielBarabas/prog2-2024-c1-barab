# 2026-02-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.482515 |       0.397952 |   0.426472 |
| barab-szabi-2        |     0.469748 |       0.484054 |   0.432006 |
| solution-1           |     7.70931  |       1e-06    |   0.451094 |
| k-d_tree_polars      |     0.484084 |       0.397977 |   0.467202 |
| Bori_Aron_solution-1 |     0.504189 |       0.544954 |   0.536103 |
| k-d_tree_pandas      |     8.2426   |       0.402593 |   0.625153 |
| k-d_tree_sklearn     |     2.97509  |       1.07258  |   1.05553  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487581 |       0.431228 |   0.433511 |
| barab-szabi-1        |     0.484528 |       0.402929 |   0.433572 |
| k-d_tree_polars      |     0.485566 |       0.402927 |   0.436407 |
| Bori_Aron_solution-1 |     0.477116 |       0.565353 |   0.533477 |
| k-d_tree_pandas      |     0.482885 |       0.382267 |   0.551442 |
| k-d_tree_sklearn     |     0.48768  |       0.971309 |   1.04627  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487716 |       0.451638 |   0.448358 |
| barab-szabi-1        |     0.49226  |       0.436721 |   0.463461 |
| k-d_tree_polars      |     0.490559 |       0.434539 |   0.464889 |
| Bori_Aron_solution-1 |     0.49139  |       0.589454 |   0.54401  |
| k-d_tree_pandas      |     0.486012 |       0.41016  |   0.594749 |
| k-d_tree_sklearn     |     0.493947 |       1.0235   |   1.10402  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495085 |       0.515953 |   0.477162 |
| k-d_tree_polars      |     0.485702 |       0.562635 |   0.560838 |
| Bori_Aron_solution-1 |     0.480763 |       0.785851 |   0.564733 |
| barab-szabi-1        |     0.491953 |       0.564365 |   0.574746 |
| k-d_tree_pandas      |     0.486787 |       0.497777 |   0.748676 |
| k-d_tree_sklearn     |     0.499608 |       1.2703   |   1.16299  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494898 |       0.745287 |   0.518641 |
| Bori_Aron_solution-1 |     0.488694 |       1.47317  |   0.584153 |
| k-d_tree_polars      |     0.497979 |       0.92983  |   0.910202 |
| barab-szabi-1        |     0.496867 |       0.944259 |   0.967165 |
| k-d_tree_pandas      |     0.485644 |       0.816381 |   1.20719  |
| k-d_tree_sklearn     |     0.498419 |       2.14554  |   1.23254  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488121 |        5.48214 |   0.767923 |
| Bori_Aron_solution-1 |     0.48606  |       11.5865  |   0.867643 |
| k-d_tree_sklearn     |     0.506903 |       17.3036  |   1.34679  |
| k-d_tree_polars      |     0.507725 |        5.6766  |   6.80135  |
| barab-szabi-1        |     0.495523 |        5.55841 |   7.09403  |
| k-d_tree_pandas      |     0.488144 |        4.4636  |   7.25435  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498092 |        78.4125 |    2.77735 |
| k-d_tree_sklearn     |     0.495014 |       239.284  |    4.1078  |
| Bori_Aron_solution-1 |     0.604621 |       151.33   |   17.7266  |