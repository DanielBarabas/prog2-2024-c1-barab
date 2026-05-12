# 2026-05-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.27012  |       1e-06    |   0.406882 |
| barab-szabi-2        |     0.454393 |       0.416857 |   0.415158 |
| barab-szabi-1        |     0.449767 |       0.395686 |   0.417322 |
| k-d_tree_polars      |     0.450763 |       0.395927 |   0.419219 |
| Bori_Aron_solution-1 |     0.44417  |       0.525308 |   0.529345 |
| k-d_tree_pandas      |     0.454985 |       0.376531 |   0.533509 |
| k-d_tree_sklearn     |    10.1156   |       1.14562  |   1.02713  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.450826 |       0.419879 |   0.420828 |
| barab-szabi-1        |     0.453357 |       0.404814 |   0.425492 |
| k-d_tree_polars      |     0.458612 |       0.405844 |   0.425643 |
| k-d_tree_pandas      |     0.465186 |       0.387107 |   0.535519 |
| Bori_Aron_solution-1 |     0.445039 |       0.544939 |   0.537886 |
| k-d_tree_sklearn     |     0.455652 |       0.949778 |   1.08437  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.44693  |       0.432446 |   0.428082 |
| barab-szabi-1        |     0.450644 |       0.428145 |   0.448208 |
| k-d_tree_polars      |     0.451763 |       0.433643 |   0.449022 |
| Bori_Aron_solution-1 |     0.440769 |       0.580134 |   0.536545 |
| k-d_tree_pandas      |     0.464352 |       0.401744 |   0.574445 |
| k-d_tree_sklearn     |     0.453271 |       0.999965 |   1.06169  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.449021 |       0.490202 |   0.456762 |
| Bori_Aron_solution-1 |     0.443078 |       0.766384 |   0.544174 |
| k-d_tree_polars      |     0.44694  |       0.545538 |   0.544696 |
| barab-szabi-1        |     0.447184 |       0.550096 |   0.559322 |
| k-d_tree_pandas      |     0.450694 |       0.488024 |   0.705769 |
| k-d_tree_sklearn     |     0.456078 |       1.33053  |   1.08868  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45049  |       0.740086 |   0.494023 |
| Bori_Aron_solution-1 |     0.442603 |       1.46902  |   0.566572 |
| k-d_tree_polars      |     0.448417 |       0.900359 |   0.936348 |
| barab-szabi-1        |     0.459802 |       0.883494 |   0.970654 |
| k-d_tree_sklearn     |     0.454652 |       2.11257  |   1.12737  |
| k-d_tree_pandas      |     0.44814  |       0.783867 |   1.16637  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448102 |        5.2318  |   0.700829 |
| Bori_Aron_solution-1 |     0.44298  |       11.1742  |   0.782724 |
| k-d_tree_sklearn     |     0.456388 |       16.4922  |   1.19387  |
| barab-szabi-1        |     0.447242 |        5.22987 |   7.11189  |
| k-d_tree_polars      |     0.447486 |        5.19259 |   7.15266  |
| k-d_tree_pandas      |     0.451152 |        4.13973 |   7.45802  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744194 |        74.7853 |    2.34183 |
| k-d_tree_sklearn     |     0.454878 |       253.176  |    3.14137 |
| Bori_Aron_solution-1 |     0.449684 |       154.671  |   18.9863  |