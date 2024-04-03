# Vietlott data

Project to crawl data from [Vietlott](https://vietlott.vn) daily.
Current support products:
- [x] [Power 6/45](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/645)
- [x] [Power 6/55](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/655)
- [x] [Keno](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/winning-number-keno)
- [ ] [Max 3D](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3d)
- [ ] [Max 3D Pro](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3dpro)
- [ ] [Bingo](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/winning-number-bingo18)

Data are stored in [/data](https://github.com/vietvudanh/vietlott-data/tree/master/data) folder in jsonl format.

## Predictions (just for testing, not a financial advice)
These are backtest results for the strategies I have developed
### random
predicted: 20 / day (20 tickets perday or 200,000 vnd)
predicted corrected:
| date   | result   | predicted   |
|--------|----------|-------------| 

## raw details 6/55
| date       |    id | result                       |   page | process_time               |
|:-----------|------:|:-----------------------------|-------:|:---------------------------|
| 2024-04-02 | 01016 | [1, 12, 18, 20, 51, 52, 37]  |      0 | 2024-04-03T01:51:47.642083 |
| 2024-03-30 | 01015 | [14, 17, 27, 38, 54, 55, 23] |      0 | 2024-03-31 01:55:34.015736 |
| 2024-03-28 | 01014 | [1, 7, 18, 26, 38, 49, 21]   |      0 | 2024-03-29 01:49:59.328787 |
| 2024-03-26 | 01013 | [1, 8, 13, 16, 38, 44, 47]   |      0 | 2024-03-27 01:50:40.849831 |
| 2024-03-23 | 01012 | [3, 10, 13, 30, 40, 52, 4]   |      0 | 2024-03-24 01:55:49.474576 |
| 2024-03-21 | 01011 | [12, 13, 41, 48, 49, 53, 43] |      0 | 2024-03-22 01:49:41.601528 |
| 2024-03-19 | 01010 | [6, 25, 39, 45, 46, 55, 26]  |      0 | 2024-03-20 01:49:32.227608 |
| 2024-03-16 | 01009 | [8, 36, 42, 43, 44, 55, 54]  |      0 | 2024-03-17 01:53:13.312382 |
| 2024-03-14 | 01008 | [21, 25, 26, 29, 41, 51, 39] |      0 | 2024-03-15 01:51:10.197869 |
| 2024-03-12 | 01007 | [11, 14, 18, 20, 22, 43, 16] |      0 | 2024-03-13 01:55:29.283981 |
## stats 6/55 all time
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |     139 | 1.95 |     |       21 |     123 | 1.73 |     | 41       | 145     | 2.04 |
|        2 |     117 | 1.65 |     |       22 |     148 | 2.08 |     | 42       | 126     | 1.77 |
|        3 |     144 | 2.03 |     |       23 |     144 | 2.03 |     | 43       | 141     | 1.98 |
|        4 |     117 | 1.65 |     |       24 |     132 | 1.86 |     | 44       | 138     | 1.94 |
|        5 |     131 | 1.84 |     |       25 |     118 | 1.66 |     | 45       | 127     | 1.79 |
|        6 |     113 | 1.59 |     |       26 |     118 | 1.66 |     | 46       | 134     | 1.88 |
|        7 |     114 | 1.6  |     |       27 |     120 | 1.69 |     | 47       | 129     | 1.81 |
|        8 |     134 | 1.88 |     |       28 |     119 | 1.67 |     | 48       | 135     | 1.9  |
|        9 |     144 | 2.03 |     |       29 |     130 | 1.83 |     | 49       | 139     | 1.95 |
|       10 |     122 | 1.72 |     |       30 |     113 | 1.59 |     | 50       | 133     | 1.87 |
|       11 |     134 | 1.88 |     |       31 |     133 | 1.87 |     | 51       | 143     | 2.01 |
|       12 |     139 | 1.95 |     |       32 |     135 | 1.9  |     | 52       | 137     | 1.93 |
|       13 |     124 | 1.74 |     |       33 |     132 | 1.86 |     | 53       | 138     | 1.94 |
|       14 |     127 | 1.79 |     |       34 |     140 | 1.97 |     | 54       | 121     | 1.7  |
|       15 |     122 | 1.72 |     |       35 |     137 | 1.93 |     | 55       | 128     | 1.8  |
|       16 |     116 | 1.63 |     |       36 |     121 | 1.7  |     |          |         |      |
|       17 |     119 | 1.67 |     |       37 |     113 | 1.59 |     |          |         |      |
|       18 |     132 | 1.86 |     |       38 |     118 | 1.66 |     |          |         |      |
|       19 |     131 | 1.84 |     |       39 |     112 | 1.58 |     |          |         |      |
|       20 |     137 | 1.93 |     |       40 |     135 | 1.9  |     |          |         |      |
## stats 6/55 -15d
|   result |   count |    % | -   |   result |   count |   % | -   | result   | count   | %   |
|---------:|--------:|-----:|:----|---------:|--------:|----:|:----|:---------|:--------|:----|
|        1 |       3 | 3.3  |     |       26 |       3 | 3.3 |     | 49       | 3       | 3.3 |
|        3 |       1 | 1.1  |     |       27 |       1 | 1.1 |     | 51       | 2       | 2.2 |
|        4 |       1 | 1.1  |     |       28 |       1 | 1.1 |     | 52       | 2       | 2.2 |
|        6 |       1 | 1.1  |     |       29 |       1 | 1.1 |     | 53       | 2       | 2.2 |
|        7 |       1 | 1.1  |     |       30 |       1 | 1.1 |     | 54       | 4       | 4.4 |
|        8 |       2 | 2.2  |     |       31 |       1 | 1.1 |     | 55       | 3       | 3.3 |
|       10 |       1 | 1.1  |     |       33 |       1 | 1.1 |     |          |         |     |
|       11 |       2 | 2.2  |     |       36 |       2 | 2.2 |     |          |         |     |
|       12 |       3 | 3.3  |     |       37 |       2 | 2.2 |     |          |         |     |
|       13 |       5 | 5.49 |     |       38 |       3 | 3.3 |     |          |         |     |
|       14 |       2 | 2.2  |     |       39 |       2 | 2.2 |     |          |         |     |
|       16 |       2 | 2.2  |     |       40 |       1 | 1.1 |     |          |         |     |
|       17 |       1 | 1.1  |     |       41 |       2 | 2.2 |     |          |         |     |
|       18 |       3 | 3.3  |     |       42 |       1 | 1.1 |     |          |         |     |
|       19 |       2 | 2.2  |     |       43 |       3 | 3.3 |     |          |         |     |
|       20 |       3 | 3.3  |     |       44 |       2 | 2.2 |     |          |         |     |
|       21 |       3 | 3.3  |     |       45 |       1 | 1.1 |     |          |         |     |
|       22 |       2 | 2.2  |     |       46 |       2 | 2.2 |     |          |         |     |
|       23 |       2 | 2.2  |     |       47 |       2 | 2.2 |     |          |         |     |
|       25 |       2 | 2.2  |     |       48 |       1 | 1.1 |     |          |         |     |
## stats 6/55 -30d
|   result |   count |    % | -   |   result |   count |   % | -   | result   | count   | %   |
|---------:|--------:|-----:|:----|---------:|--------:|----:|:----|:---------|:--------|:----|
|        1 |       3 | 3.3  |     |       26 |       3 | 3.3 |     | 49       | 3       | 3.3 |
|        3 |       1 | 1.1  |     |       27 |       1 | 1.1 |     | 51       | 2       | 2.2 |
|        4 |       1 | 1.1  |     |       28 |       1 | 1.1 |     | 52       | 2       | 2.2 |
|        6 |       1 | 1.1  |     |       29 |       1 | 1.1 |     | 53       | 2       | 2.2 |
|        7 |       1 | 1.1  |     |       30 |       1 | 1.1 |     | 54       | 4       | 4.4 |
|        8 |       2 | 2.2  |     |       31 |       1 | 1.1 |     | 55       | 3       | 3.3 |
|       10 |       1 | 1.1  |     |       33 |       1 | 1.1 |     |          |         |     |
|       11 |       2 | 2.2  |     |       36 |       2 | 2.2 |     |          |         |     |
|       12 |       3 | 3.3  |     |       37 |       2 | 2.2 |     |          |         |     |
|       13 |       5 | 5.49 |     |       38 |       3 | 3.3 |     |          |         |     |
|       14 |       2 | 2.2  |     |       39 |       2 | 2.2 |     |          |         |     |
|       16 |       2 | 2.2  |     |       40 |       1 | 1.1 |     |          |         |     |
|       17 |       1 | 1.1  |     |       41 |       2 | 2.2 |     |          |         |     |
|       18 |       3 | 3.3  |     |       42 |       1 | 1.1 |     |          |         |     |
|       19 |       2 | 2.2  |     |       43 |       3 | 3.3 |     |          |         |     |
|       20 |       3 | 3.3  |     |       44 |       2 | 2.2 |     |          |         |     |
|       21 |       3 | 3.3  |     |       45 |       1 | 1.1 |     |          |         |     |
|       22 |       2 | 2.2  |     |       46 |       2 | 2.2 |     |          |         |     |
|       23 |       2 | 2.2  |     |       47 |       2 | 2.2 |     |          |         |     |
|       25 |       2 | 2.2  |     |       48 |       1 | 1.1 |     |          |         |     |
## stats 6/55 -60d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       7 | 4    |     |       24 |       3 | 1.71 |     | 45       | 1       | 0.57 |
|        3 |       3 | 1.71 |     |       25 |       2 | 1.14 |     | 46       | 4       | 2.29 |
|        4 |       4 | 2.29 |     |       26 |       6 | 3.43 |     | 47       | 3       | 1.71 |
|        5 |       1 | 0.57 |     |       27 |       4 | 2.29 |     | 48       | 1       | 0.57 |
|        6 |       3 | 1.71 |     |       28 |       1 | 0.57 |     | 49       | 5       | 2.86 |
|        7 |       3 | 1.71 |     |       29 |       1 | 0.57 |     | 50       | 2       | 1.14 |
|        8 |       8 | 4.57 |     |       30 |       1 | 0.57 |     | 51       | 4       | 2.29 |
|       10 |       1 | 0.57 |     |       31 |       5 | 2.86 |     | 52       | 4       | 2.29 |
|       11 |       4 | 2.29 |     |       33 |       2 | 1.14 |     | 53       | 4       | 2.29 |
|       12 |       4 | 2.29 |     |       34 |       3 | 1.71 |     | 54       | 4       | 2.29 |
|       13 |       6 | 3.43 |     |       35 |       3 | 1.71 |     | 55       | 7       | 4.0  |
|       14 |       2 | 1.14 |     |       36 |       3 | 1.71 |     |          |         |      |
|       16 |       2 | 1.14 |     |       37 |       3 | 1.71 |     |          |         |      |
|       17 |       3 | 1.71 |     |       38 |       7 | 4    |     |          |         |      |
|       18 |       6 | 3.43 |     |       39 |       2 | 1.14 |     |          |         |      |
|       19 |       6 | 3.43 |     |       40 |       2 | 1.14 |     |          |         |      |
|       20 |       4 | 2.29 |     |       41 |       2 | 1.14 |     |          |         |      |
|       21 |       5 | 2.86 |     |       42 |       2 | 1.14 |     |          |         |      |
|       22 |       5 | 2.86 |     |       43 |       3 | 1.71 |     |          |         |      |
|       23 |       2 | 1.14 |     |       44 |       2 | 1.14 |     |          |         |      |
## stats 6/55 -90d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       8 | 3.01 |     |       21 |       7 | 2.63 |     | 41       | 3       | 1.13 |
|        2 |       2 | 0.75 |     |       22 |       6 | 2.26 |     | 42       | 5       | 1.88 |
|        3 |       4 | 1.5  |     |       23 |       5 | 1.88 |     | 43       | 5       | 1.88 |
|        4 |       4 | 1.5  |     |       24 |       4 | 1.5  |     | 44       | 3       | 1.13 |
|        5 |       2 | 0.75 |     |       25 |       3 | 1.13 |     | 45       | 2       | 0.75 |
|        6 |       5 | 1.88 |     |       26 |       6 | 2.26 |     | 46       | 6       | 2.26 |
|        7 |       7 | 2.63 |     |       27 |       6 | 2.26 |     | 47       | 3       | 1.13 |
|        8 |       8 | 3.01 |     |       28 |       3 | 1.13 |     | 48       | 3       | 1.13 |
|        9 |       2 | 0.75 |     |       29 |       2 | 0.75 |     | 49       | 8       | 3.01 |
|       10 |       3 | 1.13 |     |       30 |       1 | 0.38 |     | 50       | 3       | 1.13 |
|       11 |       5 | 1.88 |     |       31 |       5 | 1.88 |     | 51       | 6       | 2.26 |
|       12 |       6 | 2.26 |     |       32 |       4 | 1.5  |     | 52       | 9       | 3.38 |
|       13 |      10 | 3.76 |     |       33 |       3 | 1.13 |     | 53       | 5       | 1.88 |
|       14 |       3 | 1.13 |     |       34 |       6 | 2.26 |     | 54       | 7       | 2.63 |
|       15 |       1 | 0.38 |     |       35 |       6 | 2.26 |     | 55       | 8       | 3.01 |
|       16 |       3 | 1.13 |     |       36 |       3 | 1.13 |     |          |         |      |
|       17 |       5 | 1.88 |     |       37 |       4 | 1.5  |     |          |         |      |
|       18 |       7 | 2.63 |     |       38 |      11 | 4.14 |     |          |         |      |
|       19 |       6 | 2.26 |     |       39 |       3 | 1.13 |     |          |         |      |
|       20 |       6 | 2.26 |     |       40 |       5 | 1.88 |     |          |         |      |
