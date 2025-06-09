# 2025-06-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.61036  |       1e-06    |   0.40451  |
| barab-szabi-2        |     0.62397  |       0.468402 |   0.472722 |
| k-d_tree_polars      |     0.599019 |       0.442474 |   0.473145 |
| barab-szabi-1        |     8.95948  |       0.471207 |   0.504807 |
| k-d_tree_pandas      |     0.603888 |       0.439331 |   0.610121 |
| Bori_Aron_solution-1 |     0.600899 |       0.610077 |   0.632146 |
| k-d_tree_sklearn     |     3.53575  |       1.14623  |   1.2369   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.622857 |       0.469094 |   0.463186 |
| barab-szabi-1        |     0.599656 |       0.474205 |   0.473077 |
| barab-szabi-2        |     0.596291 |       0.488025 |   0.480966 |
| Bori_Aron_solution-1 |     0.603764 |       0.611826 |   0.596253 |
| k-d_tree_pandas      |     0.644331 |       0.497319 |   0.615938 |
| k-d_tree_sklearn     |     0.617348 |       1.11672  |   1.16434  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596736 |       0.49157  |   0.47834  |
| k-d_tree_polars      |     0.604279 |       0.482543 |   0.502105 |
| barab-szabi-1        |     0.603786 |       0.484916 |   0.521326 |
| Bori_Aron_solution-1 |     0.586899 |       0.674008 |   0.608817 |
| k-d_tree_pandas      |     0.597278 |       0.442963 |   0.649782 |
| k-d_tree_sklearn     |     0.603213 |       1.15279  |   1.18863  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592859 |       0.547821 |   0.518278 |
| k-d_tree_polars      |     0.611379 |       0.615802 |   0.58801  |
| barab-szabi-1        |     0.605886 |       0.633259 |   0.619509 |
| Bori_Aron_solution-1 |     0.613291 |       0.855499 |   0.662555 |
| k-d_tree_pandas      |     0.601264 |       0.522686 |   0.826726 |
| k-d_tree_sklearn     |     0.617495 |       1.40213  |   1.28223  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.59185  |       1.54218  |   0.662714 |
| barab-szabi-2        |     0.619603 |       0.859843 |   0.691589 |
| k-d_tree_polars      |     0.587553 |       0.943113 |   0.997716 |
| barab-szabi-1        |     0.617108 |       0.921532 |   1.05215  |
| k-d_tree_pandas      |     0.616299 |       0.809668 |   1.30079  |
| k-d_tree_sklearn     |     0.604076 |       2.34869  |   1.33796  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587618 |        5.85478 |   0.823104 |
| Bori_Aron_solution-1 |     0.629759 |       11.3522  |   0.93678  |
| k-d_tree_sklearn     |     0.638469 |       18.1805  |   1.45677  |
| barab-szabi-1        |     0.611603 |        5.09159 |   7.30741  |
| k-d_tree_polars      |     0.619372 |        5.03993 |   7.36253  |
| k-d_tree_pandas      |     0.630888 |        3.97708 |   7.69369  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.664816 |        78.3086 |    3.02778 |
| k-d_tree_sklearn     |     0.795605 |       255.005  |    4.3538  |
| Bori_Aron_solution-1 |     0.596413 |       152.618  |   15.8155  |