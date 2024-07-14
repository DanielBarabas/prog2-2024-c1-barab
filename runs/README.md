# 2024-07-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.613317 |       0.459985 |   0.429838 |
| k-d_tree_polars      |     0.615714 |       0.465456 |   0.451084 |
| barab-szabi-2        |     0.626575 |       0.455655 |   0.453541 |
| solution-1           |     8.20724  |       1e-06    |   0.490637 |
| Bori_Aron_solution-1 |     0.614283 |       0.611375 |   0.591583 |
| k-d_tree_pandas      |     0.623132 |       0.445884 |   0.5932   |
| k-d_tree_sklearn     |    11.2286   |       1.54017  |   0.878056 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606382 |       0.442456 |   0.447364 |
| barab-szabi-1        |     0.614499 |       0.467642 |   0.452718 |
| k-d_tree_polars      |     0.637991 |       0.464391 |   0.456267 |
| Bori_Aron_solution-1 |     0.618325 |       0.602048 |   0.623955 |
| k-d_tree_pandas      |     0.615315 |       0.429353 |   0.638268 |
| k-d_tree_sklearn     |     0.614754 |       1.07736  |   0.842661 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626016 |       0.4588   |   0.464356 |
| k-d_tree_polars      |     0.614861 |       0.50545  |   0.481079 |
| barab-szabi-1        |     0.635249 |       0.487591 |   0.486921 |
| Bori_Aron_solution-1 |     0.608851 |       0.660776 |   0.608917 |
| k-d_tree_pandas      |     0.611167 |       0.46879  |   0.663806 |
| k-d_tree_sklearn     |     0.615555 |       1.07476  |   0.849196 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606442 |       0.518412 |   0.469905 |
| k-d_tree_polars      |     0.600463 |       0.616882 |   0.574877 |
| barab-szabi-1        |     0.60672  |       0.626884 |   0.596251 |
| Bori_Aron_solution-1 |     0.587871 |       0.830106 |   0.610217 |
| k-d_tree_pandas      |     0.613888 |       0.526427 |   0.786609 |
| k-d_tree_sklearn     |     0.6273   |       1.37675  |   0.922576 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638    |       0.810615 |   0.550587 |
| Bori_Aron_solution-1 |     0.623602 |       1.53896  |   0.655483 |
| k-d_tree_polars      |     0.603203 |       0.964226 |   0.979182 |
| k-d_tree_sklearn     |     0.632013 |       2.33471  |   1.00502  |
| barab-szabi-1        |     0.633929 |       0.934038 |   1.00549  |
| k-d_tree_pandas      |     0.666807 |       0.823715 |   1.29126  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.588964 |       14.2264  |    1.06139 |
| barab-szabi-2        |     0.604686 |        8.4933  |    1.22129 |
| k-d_tree_sklearn     |     0.605149 |       24.5534  |    1.25263 |
| barab-szabi-1        |     0.611708 |        5.15252 |    9.55179 |
| k-d_tree_polars      |     0.635272 |        5.15197 |    9.56659 |
| k-d_tree_pandas      |     0.610657 |        4.11061 |   10.5327  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785967 |        95.4885 |    4.89991 |
| k-d_tree_sklearn     |     0.600932 |       341.296  |    5.3718  |
| Bori_Aron_solution-1 |     0.589394 |       201.221  |   18.8812  |