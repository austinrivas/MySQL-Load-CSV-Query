MySQL Load CSV Query
===================

A simple query to load a local CSV file

```
LOAD DATA INFILE "/local/path/to/file.csv"
INTO TABLE `table`
COLUMNS TERMINATED BY ','
OPTIONALLY ENCLOSED BY '"'
ESCAPED BY '"'
LINES TERMINATED BY '\n'
IGNORE 1 LINES;
```
