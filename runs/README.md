# 2026-11-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     5.23081  |       1e-06    |   0.246233 |
| barab-szabi-2        |     0.290555 |       0.299482 |   0.286811 |
| barab-szabi-1        |     0.282818 |       0.297846 |   0.294499 |
| k-d_tree_polars      |     6.92369  |       0.319371 |   0.326114 |
| Bori_Aron_solution-1 |     0.30017  |       0.375154 |   0.383737 |
| k-d_tree_pandas      |     0.297371 |       0.272914 |   0.398708 |
| k-d_tree_sklearn     |     2.09717  |       0.717907 |   0.744172 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.287783 |       0.296544 |   0.286405 |
| k-d_tree_polars      |     0.293666 |       0.293797 |   0.302833 |
| barab-szabi-1        |     0.311912 |       0.2859   |   0.304605 |
| Bori_Aron_solution-1 |     0.284772 |       0.372508 |   0.363525 |
| k-d_tree_pandas      |     0.292828 |       0.261264 |   0.377585 |
| k-d_tree_sklearn     |     0.3096   |       0.820673 |   0.783915 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.310326 |       0.342069 |   0.307035 |
| barab-szabi-1        |     0.297545 |       0.325718 |   0.321853 |
| k-d_tree_polars      |     0.310159 |       0.333206 |   0.356278 |
| Bori_Aron_solution-1 |     0.295866 |       0.441385 |   0.455958 |
| k-d_tree_pandas      |     0.318929 |       0.292848 |   0.51277  |
| k-d_tree_sklearn     |     0.300818 |       0.714464 |   0.714339 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.288995 |       0.372263 |   0.33174  |
| Bori_Aron_solution-1 |     0.282607 |       0.532581 |   0.389684 |
| k-d_tree_polars      |     0.279893 |       0.393211 |   0.390664 |
| barab-szabi-1        |     0.30699  |       0.402428 |   0.394924 |
| k-d_tree_pandas      |     0.301127 |       0.333279 |   0.477072 |
| k-d_tree_sklearn     |     0.30148  |       0.887863 |   0.756784 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.287764 |       0.547356 |   0.370047 |
| Bori_Aron_solution-1 |     0.288506 |       0.94902  |   0.411771 |
| k-d_tree_polars      |     0.292435 |       0.628676 |   0.639706 |
| barab-szabi-1        |     0.297975 |       0.666107 |   0.697944 |
| k-d_tree_pandas      |     0.300181 |       0.504228 |   0.773133 |
| k-d_tree_sklearn     |     0.331169 |       1.51336  |   0.803427 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.296999 |        3.73361 |   0.645509 |
| Bori_Aron_solution-1 |     0.289453 |        7.17242 |   0.829107 |
| k-d_tree_sklearn     |     0.273436 |       11.0823  |   0.841772 |
| barab-szabi-1        |     0.29063  |        3.53487 |   4.69742  |
| k-d_tree_polars      |     0.296129 |        3.64535 |   4.99411  |
| k-d_tree_pandas      |     0.293163 |        2.43205 |   5.22214  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.360597 |       169.576  |    2.65267 |
| barab-szabi-2        |     0.425999 |        58.3935 |    3.10696 |
| Bori_Aron_solution-1 |     0.270984 |       120.931  |   24.9373  |