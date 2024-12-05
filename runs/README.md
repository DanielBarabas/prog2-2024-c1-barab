# 2024-12-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.612977 |       0.407162 |   0.380329 |
| barab-szabi-1        |     0.643008 |       0.393722 |   0.383327 |
| barab-szabi-2        |     0.613228 |       0.38116  |   0.38348  |
| solution-1           |     7.42103  |       1e-06    |   0.418143 |
| Bori_Aron_solution-1 |     0.605043 |       0.509525 |   0.509004 |
| k-d_tree_pandas      |     0.613459 |       0.376945 |   0.525214 |
| k-d_tree_sklearn     |    10.3036   |       1.3259   |   0.945337 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.610319 |       0.396105 |   0.385223 |
| barab-szabi-1        |     0.613388 |       0.396822 |   0.390318 |
| barab-szabi-2        |     0.605766 |       0.384609 |   0.419322 |
| Bori_Aron_solution-1 |     0.601752 |       0.518147 |   0.511338 |
| k-d_tree_pandas      |     0.605938 |       0.376212 |   0.518132 |
| k-d_tree_sklearn     |     0.617952 |       0.867336 |   0.937835 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60753  |       0.409476 |   0.394033 |
| k-d_tree_polars      |     0.61424  |       0.422262 |   0.415131 |
| barab-szabi-1        |     0.609473 |       0.42494  |   0.420662 |
| Bori_Aron_solution-1 |     0.601396 |       0.555102 |   0.513066 |
| k-d_tree_pandas      |     0.604266 |       0.410674 |   0.571041 |
| k-d_tree_sklearn     |     0.646318 |       0.926208 |   0.974631 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606045 |       0.467242 |   0.426593 |
| k-d_tree_polars      |     0.61663  |       0.527004 |   0.515635 |
| barab-szabi-1        |     0.611765 |       0.529075 |   0.523002 |
| Bori_Aron_solution-1 |     0.601167 |       0.736576 |   0.528047 |
| k-d_tree_pandas      |     0.606489 |       0.472307 |   0.697729 |
| k-d_tree_sklearn     |     0.607052 |       1.13831  |   1.03103  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606925 |       0.705593 |   0.457392 |
| Bori_Aron_solution-1 |     0.605247 |       1.37379  |   0.560803 |
| k-d_tree_polars      |     0.604948 |       0.854456 |   0.852925 |
| barab-szabi-1        |     0.60912  |       0.859945 |   0.888853 |
| k-d_tree_sklearn     |     0.613016 |       1.96648  |   1.11849  |
| k-d_tree_pandas      |     0.612954 |       0.742393 |   1.12453  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607349 |        5.27652 |   0.712068 |
| Bori_Aron_solution-1 |     0.599248 |       10.7985  |   0.80799  |
| k-d_tree_sklearn     |     0.618765 |       16.0184  |   1.22254  |
| barab-szabi-1        |     0.609543 |        4.85194 |   6.46227  |
| k-d_tree_polars      |     0.609787 |        4.85168 |   6.54149  |
| k-d_tree_pandas      |     0.617063 |        3.89405 |   7.69877  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629162 |        70.1282 |    3.09903 |
| k-d_tree_sklearn     |     0.616093 |       223.426  |    4.15351 |
| Bori_Aron_solution-1 |     0.621304 |       144.418  |   17.0422  |