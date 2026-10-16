# 2026-10-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.295489 |       0.279166 |   0.279803 |
| k-d_tree_polars      |     0.296521 |       0.279113 |   0.290477 |
| Bori_Aron_solution-1 |     0.291282 |       0.35854  |   0.358664 |
| k-d_tree_pandas      |     0.301978 |       0.2628   |   0.375807 |
| solution-1           |     5.17959  |       1e-06    |   0.425637 |
| barab-szabi-1        |     6.91271  |       0.426415 |   0.42876  |
| k-d_tree_sklearn     |     2.33517  |       1.0721   |   0.80268  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.304821 |       0.293449 |   0.293184 |
| k-d_tree_polars      |     0.310095 |       0.289884 |   0.300993 |
| barab-szabi-1        |     0.348056 |       0.319535 |   0.336466 |
| k-d_tree_pandas      |     0.331224 |       0.269087 |   0.364227 |
| Bori_Aron_solution-1 |     0.305014 |       0.374721 |   0.37471  |
| k-d_tree_sklearn     |     0.309717 |       0.644007 |   0.709341 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.306793 |       0.310611 |   0.29092  |
| barab-szabi-1        |     0.303827 |       0.304463 |   0.319063 |
| k-d_tree_polars      |     0.300642 |       0.313591 |   0.321761 |
| Bori_Aron_solution-1 |     0.299836 |       0.399682 |   0.365457 |
| k-d_tree_pandas      |     0.307294 |       0.276739 |   0.400062 |
| k-d_tree_sklearn     |     0.30459  |       0.707823 |   0.725643 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.303127 |       0.357079 |   0.320014 |
| k-d_tree_polars      |     0.309792 |       0.424038 |   0.374705 |
| Bori_Aron_solution-1 |     0.305656 |       0.52469  |   0.382833 |
| barab-szabi-1        |     0.305409 |       0.400363 |   0.411677 |
| k-d_tree_pandas      |     0.310512 |       0.34627  |   0.540218 |
| k-d_tree_sklearn     |     0.308389 |       0.858376 |   0.749036 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.349427 |       0.561296 |   0.363221 |
| Bori_Aron_solution-1 |     0.308915 |       0.957304 |   0.411402 |
| barab-szabi-1        |     0.308317 |       0.681743 |   0.64918  |
| k-d_tree_polars      |     0.306    |       0.768894 |   0.693938 |
| k-d_tree_pandas      |     0.309807 |       0.524418 |   0.77643  |
| k-d_tree_sklearn     |     0.308597 |       1.48767  |   0.797324 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.304943 |        3.47112 |   0.563688 |
| Bori_Aron_solution-1 |     0.305823 |        7.52354 |   0.721204 |
| k-d_tree_sklearn     |     0.312442 |       11.3027  |   0.931857 |
| barab-szabi-1        |     0.311067 |        3.98313 |   4.47065  |
| k-d_tree_polars      |     0.311727 |        3.80027 |   4.50658  |
| k-d_tree_pandas      |     0.311015 |        2.72965 |   4.80203  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48084  |        59.0567 |    2.70676 |
| k-d_tree_sklearn     |     0.404571 |       149.552  |    3.14193 |
| Bori_Aron_solution-1 |     0.306361 |       131.784  |   23.5084  |