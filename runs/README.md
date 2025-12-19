# 2025-12-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.464346 |       0.370252 |   0.399808 |
| barab-szabi-2        |     0.665909 |       0.492669 |   0.39994  |
| k-d_tree_polars      |     0.468161 |       0.371533 |   0.402229 |
| solution-1           |     7.32695  |       1e-06    |   0.462129 |
| Bori_Aron_solution-1 |     0.462184 |       0.499677 |   0.49633  |
| k-d_tree_pandas      |     8.19463  |       0.400145 |   0.602962 |
| k-d_tree_sklearn     |     2.93856  |       0.982647 |   0.950557 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466388 |       0.402722 |   0.398228 |
| barab-szabi-1        |     0.466107 |       0.375458 |   0.401349 |
| k-d_tree_polars      |     0.466908 |       0.373681 |   0.402917 |
| Bori_Aron_solution-1 |     0.459542 |       0.507913 |   0.495562 |
| k-d_tree_pandas      |     0.466828 |       0.361544 |   0.510081 |
| k-d_tree_sklearn     |     0.470005 |       0.877255 |   0.949658 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471676 |       0.410575 |   0.41068  |
| barab-szabi-1        |     0.480411 |       0.402    |   0.423748 |
| k-d_tree_polars      |     0.467389 |       0.400471 |   0.424832 |
| Bori_Aron_solution-1 |     0.461473 |       0.539496 |   0.498768 |
| k-d_tree_pandas      |     0.466256 |       0.422769 |   0.548881 |
| k-d_tree_sklearn     |     0.473395 |       0.907225 |   0.962722 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467417 |       0.470889 |   0.436326 |
| k-d_tree_polars      |     0.469803 |       0.515441 |   0.511238 |
| Bori_Aron_solution-1 |     0.462937 |       0.701884 |   0.51729  |
| barab-szabi-1        |     0.467278 |       0.521828 |   0.520783 |
| k-d_tree_pandas      |     0.468871 |       0.454163 |   0.661935 |
| k-d_tree_sklearn     |     0.469812 |       1.1252   |   1.0104   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474405 |       0.690784 |   0.47483  |
| Bori_Aron_solution-1 |     0.471127 |       1.29834  |   0.550738 |
| k-d_tree_polars      |     0.466631 |       0.840664 |   0.832758 |
| barab-szabi-1        |     0.467671 |       0.841356 |   0.853488 |
| k-d_tree_pandas      |     0.46832  |       0.714478 |   1.05765  |
| k-d_tree_sklearn     |     0.473256 |       1.87551  |   1.09095  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47723  |        4.63781 |   0.679169 |
| Bori_Aron_solution-1 |     0.468101 |        9.78083 |   0.891812 |
| k-d_tree_sklearn     |     0.473618 |       13.6338  |   1.21787  |
| barab-szabi-1        |     0.470494 |        4.79058 |   5.78739  |
| k-d_tree_polars      |     0.471936 |        4.81856 |   5.96694  |
| k-d_tree_pandas      |     0.478096 |        3.79804 |   6.3717   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477253 |        91.4355 |    2.57483 |
| k-d_tree_sklearn     |     0.487381 |       173.224  |    4.16303 |
| Bori_Aron_solution-1 |     0.58918  |       133.862  |   17.2891  |