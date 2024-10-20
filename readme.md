# Vietlot data

Data crawling from https://vietlott.vn/, results for products:
- [6/55](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/655)
- [6/45](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/645)
- [Keno](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/winning-number-keno)
- [Max 3D](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3d)
- [Max 3D Pro](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3dpro)

## Table of content
- [Vietlot data](#vietlot-data)
  * [Predictions (just for testing, not a financial advice)](#predictions--just-for-testing--not-a-financial-advice-)
    + [random](#random)
  * [raw details 6/55](#raw-details-6-55)
  * [stats 6/55 all time](#stats-6-55-all-time)
  * [stats 6/55 -15d](#stats-6-55--15d)
  * [stats 6/55 -30d](#stats-6-55--30d)
  * [stats 6/55 -60d](#stats-6-55--60d)
  * [stats 6/55 -90d](#stats-6-55--90d)
- [Install](#install)
  * [via pip](#via-pip)
  * [cli](#cli)
    + [crawl](#crawl)
    + [Backfill missing data](#backfill-missing-data)


## Predictions (just for testing, not a financial advice)
These are backtest results for the strategies I have tested (just the abstract method at the moment, you can't predict lotery lol)

### random strategy
predicted: 20 / day (20 tickets perday or 200,000 vnd)
predicted corrected:
| date   | result   | predicted   |
|--------|----------|-------------| 

## raw details 6/55 last 10 days
| date       |    id | result                       |   page | process_time               |
|:-----------|------:|:-----------------------------|-------:|:---------------------------|
| 2024-10-19 | 01102 | [9, 22, 31, 39, 43, 51, 19]  |      0 | 2024-10-19 14:07:01.732285 |
| 2024-10-17 | 01101 | [11, 14, 15, 26, 38, 41, 25] |      0 | 2024-10-17 14:08:38.965236 |
| 2024-10-15 | 01100 | [4, 25, 41, 42, 46, 52, 33]  |      0 | 2024-10-15 14:08:16.788716 |
| 2024-10-12 | 01099 | [29, 34, 35, 38, 50, 51, 37] |      0 | 2024-10-12 14:06:38.873281 |
| 2024-10-10 | 01098 | [4, 5, 6, 29, 32, 44, 53]    |      0 | 2024-10-10 14:08:31.717284 |
| 2024-10-08 | 01097 | [3, 7, 14, 17, 48, 50, 40]   |      0 | 2024-10-08 14:08:48.961350 |
| 2024-10-05 | 01096 | [2, 10, 17, 27, 50, 52, 18]  |      0 | 2024-10-05 14:05:33.835578 |
| 2024-10-03 | 01095 | [18, 21, 34, 40, 42, 53, 25] |      0 | 2024-10-03 14:08:22.354403 |
| 2024-10-01 | 01094 | [3, 18, 22, 41, 43, 44, 12]  |      0 | 2024-10-01 14:08:26.085082 |
| 2024-09-28 | 01093 | [2, 11, 13, 32, 41, 48, 15]  |      0 | 2024-09-28 14:05:31.520053 |
## stats 6/55 all time
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |     152 | 1.97 |     |       21 |     134 | 1.74 |     | 41       | 160     | 2.07 |
|        2 |     131 | 1.7  |     |       22 |     160 | 2.07 |     | 42       | 138     | 1.79 |
|        3 |     153 | 1.98 |     |       23 |     156 | 2.02 |     | 43       | 155     | 2.01 |
|        4 |     124 | 1.61 |     |       24 |     138 | 1.79 |     | 44       | 148     | 1.92 |
|        5 |     141 | 1.83 |     |       25 |     132 | 1.71 |     | 45       | 136     | 1.76 |
|        6 |     122 | 1.58 |     |       26 |     127 | 1.65 |     | 46       | 151     | 1.96 |
|        7 |     122 | 1.58 |     |       27 |     130 | 1.69 |     | 47       | 139     | 1.8  |
|        8 |     150 | 1.94 |     |       28 |     125 | 1.62 |     | 48       | 148     | 1.92 |
|        9 |     153 | 1.98 |     |       29 |     143 | 1.85 |     | 49       | 147     | 1.91 |
|       10 |     132 | 1.71 |     |       30 |     120 | 1.56 |     | 50       | 141     | 1.83 |
|       11 |     144 | 1.87 |     |       31 |     142 | 1.84 |     | 51       | 155     | 2.01 |
|       12 |     152 | 1.97 |     |       32 |     150 | 1.94 |     | 52       | 147     | 1.91 |
|       13 |     135 | 1.75 |     |       33 |     143 | 1.85 |     | 53       | 148     | 1.92 |
|       14 |     136 | 1.76 |     |       34 |     155 | 2.01 |     | 54       | 134     | 1.74 |
|       15 |     130 | 1.69 |     |       35 |     146 | 1.89 |     | 55       | 141     | 1.83 |
|       16 |     123 | 1.59 |     |       36 |     132 | 1.71 |     |          |         |      |
|       17 |     127 | 1.65 |     |       37 |     123 | 1.59 |     |          |         |      |
|       18 |     144 | 1.87 |     |       38 |     134 | 1.74 |     |          |         |      |
|       19 |     136 | 1.76 |     |       39 |     127 | 1.65 |     |          |         |      |
|       20 |     151 | 1.96 |     |       40 |     150 | 1.94 |     |          |         |      |
## stats 6/55 -15d
|   result |   count |   % | -   |   result |   count |    % | -   | result   | count   | %   |
|---------:|--------:|----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:----|
|        1 |       1 | 1.1 |     |       24 |       1 | 1.1  |     | 49       | 1       | 1.1 |
|        2 |       2 | 2.2 |     |       25 |       3 | 3.3  |     | 50       | 3       | 3.3 |
|        3 |       4 | 4.4 |     |       26 |       2 | 2.2  |     | 51       | 2       | 2.2 |
|        4 |       2 | 2.2 |     |       27 |       1 | 1.1  |     | 52       | 2       | 2.2 |
|        5 |       1 | 1.1 |     |       29 |       3 | 3.3  |     | 53       | 2       | 2.2 |
|        6 |       2 | 2.2 |     |       31 |       2 | 2.2  |     | 55       | 1       | 1.1 |
|        7 |       1 | 1.1 |     |       32 |       2 | 2.2  |     |          |         |     |
|        8 |       1 | 1.1 |     |       33 |       1 | 1.1  |     |          |         |     |
|        9 |       2 | 2.2 |     |       34 |       2 | 2.2  |     |          |         |     |
|       10 |       1 | 1.1 |     |       35 |       1 | 1.1  |     |          |         |     |
|       11 |       4 | 4.4 |     |       37 |       1 | 1.1  |     |          |         |     |
|       12 |       1 | 1.1 |     |       38 |       2 | 2.2  |     |          |         |     |
|       13 |       1 | 1.1 |     |       39 |       2 | 2.2  |     |          |         |     |
|       14 |       2 | 2.2 |     |       40 |       2 | 2.2  |     |          |         |     |
|       15 |       2 | 2.2 |     |       41 |       5 | 5.49 |     |          |         |     |
|       17 |       3 | 3.3 |     |       42 |       2 | 2.2  |     |          |         |     |
|       18 |       4 | 4.4 |     |       43 |       3 | 3.3  |     |          |         |     |
|       19 |       1 | 1.1 |     |       44 |       2 | 2.2  |     |          |         |     |
|       21 |       1 | 1.1 |     |       46 |       2 | 2.2  |     |          |         |     |
|       22 |       3 | 3.3 |     |       48 |       2 | 2.2  |     |          |         |     |
## stats 6/55 -30d
|   result |   count |   % | -   |   result |   count |    % | -   | result   | count   | %   |
|---------:|--------:|----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:----|
|        1 |       1 | 1.1 |     |       24 |       1 | 1.1  |     | 49       | 1       | 1.1 |
|        2 |       2 | 2.2 |     |       25 |       3 | 3.3  |     | 50       | 3       | 3.3 |
|        3 |       4 | 4.4 |     |       26 |       2 | 2.2  |     | 51       | 2       | 2.2 |
|        4 |       2 | 2.2 |     |       27 |       1 | 1.1  |     | 52       | 2       | 2.2 |
|        5 |       1 | 1.1 |     |       29 |       3 | 3.3  |     | 53       | 2       | 2.2 |
|        6 |       2 | 2.2 |     |       31 |       2 | 2.2  |     | 55       | 1       | 1.1 |
|        7 |       1 | 1.1 |     |       32 |       2 | 2.2  |     |          |         |     |
|        8 |       1 | 1.1 |     |       33 |       1 | 1.1  |     |          |         |     |
|        9 |       2 | 2.2 |     |       34 |       2 | 2.2  |     |          |         |     |
|       10 |       1 | 1.1 |     |       35 |       1 | 1.1  |     |          |         |     |
|       11 |       4 | 4.4 |     |       37 |       1 | 1.1  |     |          |         |     |
|       12 |       1 | 1.1 |     |       38 |       2 | 2.2  |     |          |         |     |
|       13 |       1 | 1.1 |     |       39 |       2 | 2.2  |     |          |         |     |
|       14 |       2 | 2.2 |     |       40 |       2 | 2.2  |     |          |         |     |
|       15 |       2 | 2.2 |     |       41 |       5 | 5.49 |     |          |         |     |
|       17 |       3 | 3.3 |     |       42 |       2 | 2.2  |     |          |         |     |
|       18 |       4 | 4.4 |     |       43 |       3 | 3.3  |     |          |         |     |
|       19 |       1 | 1.1 |     |       44 |       2 | 2.2  |     |          |         |     |
|       21 |       1 | 1.1 |     |       46 |       2 | 2.2  |     |          |         |     |
|       22 |       3 | 3.3 |     |       48 |       2 | 2.2  |     |          |         |     |
## stats 6/55 -60d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       2 | 1.1  |     |       22 |       5 | 2.75 |     | 42       | 3       | 1.65 |
|        2 |       5 | 2.75 |     |       23 |       3 | 1.65 |     | 43       | 3       | 1.65 |
|        3 |       5 | 2.75 |     |       24 |       3 | 1.65 |     | 44       | 2       | 1.1  |
|        4 |       3 | 1.65 |     |       25 |       4 | 2.2  |     | 45       | 2       | 1.1  |
|        5 |       3 | 1.65 |     |       26 |       2 | 1.1  |     | 46       | 5       | 2.75 |
|        6 |       3 | 1.65 |     |       27 |       1 | 0.55 |     | 47       | 2       | 1.1  |
|        7 |       1 | 0.55 |     |       28 |       1 | 0.55 |     | 48       | 6       | 3.3  |
|        8 |       4 | 2.2  |     |       29 |       6 | 3.3  |     | 49       | 2       | 1.1  |
|        9 |       3 | 1.65 |     |       30 |       1 | 0.55 |     | 50       | 3       | 1.65 |
|       10 |       2 | 1.1  |     |       31 |       4 | 2.2  |     | 51       | 4       | 2.2  |
|       11 |       8 | 4.4  |     |       32 |       5 | 2.75 |     | 52       | 2       | 1.1  |
|       12 |       3 | 1.65 |     |       33 |       3 | 1.65 |     | 53       | 3       | 1.65 |
|       13 |       1 | 0.55 |     |       34 |       5 | 2.75 |     | 54       | 3       | 1.65 |
|       14 |       4 | 2.2  |     |       35 |       1 | 0.55 |     | 55       | 2       | 1.1  |
|       15 |       4 | 2.2  |     |       36 |       1 | 0.55 |     |          |         |      |
|       17 |       4 | 2.2  |     |       37 |       4 | 2.2  |     |          |         |      |
|       18 |       5 | 2.75 |     |       38 |       8 | 4.4  |     |          |         |      |
|       19 |       1 | 0.55 |     |       39 |       4 | 2.2  |     |          |         |      |
|       20 |       4 | 2.2  |     |       40 |       3 | 1.65 |     |          |         |      |
|       21 |       3 | 1.65 |     |       41 |       8 | 4.4  |     |          |         |      |
## stats 6/55 -90d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       3 | 1.1  |     |       21 |       5 | 1.83 |     | 41       | 9       | 3.3  |
|        2 |       6 | 2.2  |     |       22 |       7 | 2.56 |     | 42       | 5       | 1.83 |
|        3 |       5 | 1.83 |     |       23 |       6 | 2.2  |     | 43       | 5       | 1.83 |
|        4 |       4 | 1.47 |     |       24 |       4 | 1.47 |     | 44       | 4       | 1.47 |
|        5 |       5 | 1.83 |     |       25 |       6 | 2.2  |     | 45       | 4       | 1.47 |
|        6 |       5 | 1.83 |     |       26 |       4 | 1.47 |     | 46       | 8       | 2.93 |
|        7 |       3 | 1.1  |     |       27 |       3 | 1.1  |     | 47       | 2       | 0.73 |
|        8 |       5 | 1.83 |     |       28 |       2 | 0.73 |     | 48       | 9       | 3.3  |
|        9 |       5 | 1.83 |     |       29 |       9 | 3.3  |     | 49       | 2       | 0.73 |
|       10 |       3 | 1.1  |     |       30 |       3 | 1.1  |     | 50       | 4       | 1.47 |
|       11 |       8 | 2.93 |     |       31 |       4 | 1.47 |     | 51       | 6       | 2.2  |
|       12 |       4 | 1.47 |     |       32 |       7 | 2.56 |     | 52       | 2       | 0.73 |
|       13 |       1 | 0.37 |     |       33 |       4 | 1.47 |     | 53       | 4       | 1.47 |
|       14 |       6 | 2.2  |     |       34 |       9 | 3.3  |     | 54       | 6       | 2.2  |
|       15 |       4 | 1.47 |     |       35 |       3 | 1.1  |     | 55       | 6       | 2.2  |
|       16 |       2 | 0.73 |     |       36 |       2 | 0.73 |     |          |         |      |
|       17 |       6 | 2.2  |     |       37 |       6 | 2.2  |     |          |         |      |
|       18 |       6 | 2.2  |     |       38 |      10 | 3.66 |     |          |         |      |
|       19 |       1 | 0.37 |     |       39 |       8 | 2.93 |     |          |         |      |
|       20 |       6 | 2.2  |     |       40 |       7 | 2.56 |     |          |         |      |

# How project works
Since there are many people asked, I write this section.

## Schedule
The project is schedule automatically via Github Actions, run a script, fetch data and auto commit to Github. No server is required, I don't need to do anything.
Details in [workflow file](https://github.com/vietvudanh/vietlott-data/blob/dffb2bcdfa860a0dfc3f2e22e269e6978d478965/.github/workflows/crawl.yaml#L8)

## How crawling works
I just inspected network packages sent between browser and server to find out how data is fetched and replicated that in Python code. 

# Install
 
## via pip

```shell
pip install -i https://test.pypi.org/simple/ vietlott-data==0.1.3
```

## cli
project provides two cli

### crawl
```shell
Usage: vietlott-crawl [OPTIONS] PRODUCT

  crawl a product with a given run date or from/to index page 

Options:
  --run-date TEXT
  --index_from INTEGER  page index from run since we crawl by pagination the
                        pages
  --index_to INTEGER    page index from run since we crawl by pagination the
                        pages
  --help                Show this message and exit.
```

### Backfill missing data

```shell
Usage: vietlott-missing [OPTIONS] PRODUCT

  detect_missing_data and run if needed :param ctx: context :param product:
  product to run :param limit: number of pages to run :return:

Options:
  --limit INTEGER
  --help           Show this message and exit.
```

