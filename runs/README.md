# 2024-08-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.623772 |       0.415451 |   0.403114 |
| k-d_tree_polars      |     0.638849 |       0.410048 |   0.406174 |
| barab-szabi-2        |     8.27603  |       0.681267 |   0.407267 |
| Bori_Aron_solution-1 |     0.6374   |       0.552171 |   0.544534 |
| k-d_tree_pandas      |     0.638914 |       0.4449   |   0.549518 |
| solution-1           |     8.00056  |       2e-06    |   0.568129 |
| k-d_tree_sklearn     |     3.23975  |       1.12255  |   0.737118 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637585 |       0.404569 |   0.399771 |
| k-d_tree_polars      |     0.636117 |       0.419046 |   0.401304 |
| barab-szabi-1        |     0.632303 |       0.432201 |   0.40364  |
| Bori_Aron_solution-1 |     0.62826  |       0.555205 |   0.558834 |
| k-d_tree_pandas      |     0.638156 |       0.401587 |   0.56323  |
| k-d_tree_sklearn     |     0.661027 |       0.947746 |   0.754713 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636781 |       0.422044 |   0.416008 |
| k-d_tree_polars      |     0.656614 |       0.445187 |   0.434111 |
| barab-szabi-1        |     0.637434 |       0.447638 |   0.44822  |
| Bori_Aron_solution-1 |     0.625393 |       0.594251 |   0.559046 |
| k-d_tree_pandas      |     0.649211 |       0.437754 |   0.615786 |
| k-d_tree_sklearn     |     0.63512  |       1.03216  |   0.76823  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629125 |       0.480162 |   0.453126 |
| k-d_tree_polars      |     0.637422 |       0.559758 |   0.539857 |
| barab-szabi-1        |     0.659237 |       0.56777  |   0.555969 |
| Bori_Aron_solution-1 |     0.667438 |       0.801636 |   0.584769 |
| k-d_tree_pandas      |     0.639523 |       0.493293 |   0.735981 |
| k-d_tree_sklearn     |     0.66801  |       1.27895  |   0.865918 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.645744 |       1.54204  |   0.620265 |
| barab-szabi-2        |     0.663301 |       0.813846 |   0.646314 |
| k-d_tree_sklearn     |     0.656649 |       2.29797  |   0.935171 |
| k-d_tree_polars      |     0.668498 |       0.903948 |   0.947423 |
| barab-szabi-1        |     0.653304 |       0.901334 |   0.981979 |
| k-d_tree_pandas      |     0.660535 |       0.800822 |   1.28619  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.660711 |        6.08845 |   0.788001 |
| Bori_Aron_solution-1 |     0.658205 |       11.4597  |   0.874097 |
| k-d_tree_sklearn     |     0.638072 |       18.5735  |   1.05146  |
| barab-szabi-1        |     0.646674 |        4.87191 |   7.09673  |
| k-d_tree_polars      |     0.658661 |        4.94225 |   7.21432  |
| k-d_tree_pandas      |     0.644544 |        3.91814 |   7.65116  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639127 |        76.0834 |    3.16279 |
| k-d_tree_sklearn     |     0.656599 |       241.474  |    3.99664 |
| Bori_Aron_solution-1 |     0.704563 |       146.445  |   18.0989  |