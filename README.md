以遺傳演算法實作中文法律裁判書斷詞
============
#### 說明
1. 內建詞庫`library.txt`
2. 可以自行調整詞庫內容，以符合需求
3. 預設會輸出前三筆演算結果，與系統自動使用的參數

#### 使用方式
`python3 GA.py 欲斷之詞`
##### Example:
`python3 GA.py 上列被告因公共危險案件`
##### Output
```
GENE_LEN: 10 POPULATION_COUNT: 100 ITERATION_COUNT: 200
Best Result:
14897 [0, 0, 0, 0, 1, 0, 0, 0, 1, 0] ['上列被告因', '公共危險', '案件']
13253 [0, 0, 0, 0, 1, 1, 0, 0, 1, 0] ['上列被告因', '公', '共危險', '案件']
12542 [0, 0, 0, 0, 1, 0, 0, 1, 1, 0] ['上列被告因', '公共危', '險', '案件']
```