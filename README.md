# **SQL Server Learning path**

### **Fundamentals**
  * [`Database`](https://www.tutorialsteacher.com/sqlserver/create-database)
  * [`Schema`](https://www.tutorialsteacher.com/sqlserver/database-schema)
  * [`Table`](https://www.tutorialsteacher.com/sqlserver/create-table)
  * `Row`
  * `Column`
  * [`Keys`](https://www.dotnettricks.com/learn/sqlserver/different-types-of-sql-keys)
    - [`PRIMARY KEY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-primary-key/)
    - [`FOREIGN KEY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-primary-key/)
    - `SUPER KEY`
    - `CANDIDATE KEY`
    - `COMPOSITE KEY`
    - `UNIQUE KEY`
  * `Indexes`
    - [`Clustered Index`](https://www.sqlservertutorial.net/sql-server-indexes/sql-server-clustered-indexes/)
    - [`Non Clustered Index`](https://www.sqlservertutorial.net/sql-server-indexes/sql-server-create-index/)
    - [`DROP indexes`](https://www.sqlservertutorial.net/sql-server-indexes/sql-server-drop-index/)
  * `Constraints`
    - Column level constraints
        - [`NOT NULL`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-not-null-constraint/)
        - [`PRIMARY KEY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-primary-key/)
        - [`FOREIGN KEY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-foreign-key/)
        - [`UNIQUE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-unique-constraint/)
        - [`CHECK`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-check-constraint/)
        - [`DEFAULT`](https://www.w3schools.com/sql/sql_default.asp)
    - Table level constraints
        - `ALTER`
  * [`Statement blocks`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-begin-end/)
  * `Stored Procedures`
    - [`Parameters`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-stored-procedure-parameters/)
    - [`Variables`](https://www.sqlservertutorial.net/sql-server-stored-procedures/variables/)
    - [`Output parameters`](https://www.sqlservertutorial.net/sql-server-stored-procedures/stored-procedure-output-parameters/)
  * `User defined Functions (UDF)`
    - [`Scalar functions`](https://www.sqlservertutorial.net/sql-server-user-defined-functions/sql-server-scalar-functions/)
    - [`Table variables`](https://www.sqlservertutorial.net/sql-server-user-defined-functions/sql-server-table-variables/)
    - [`Table valued functions`](https://www.sqlservertutorial.net/sql-server-user-defined-functions/sql-server-table-valued-functions/)
    - [`DROP UDF(s)`](https://www.sqlservertutorial.net/sql-server-user-defined-functions/sql-server-drop-function/)
  * [`Temporary tables`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-temporary-tables/)
  * `Views`
    - [`CREATE VIEW`](https://www.sqlservertutorial.net/sql-server-views/sql-server-create-view/)
    - [`DROP VIEW`](https://www.sqlservertutorial.net/sql-server-views/sql-server-drop-view/)
    - [`Add indexes to views`](https://www.sqlservertutorial.net/sql-server-views/sql-server-indexed-view/)
  * `Triggers`
    - [`Trigger`](https://www.sqlservertutorial.net/sql-server-triggers/sql-server-create-trigger/)
    - [`INSTEAD OF trigger`](https://www.sqlservertutorial.net/sql-server-triggers/sql-server-instead-of-trigger/)
    - [`DROP TRIGGER`](https://www.sqlservertutorial.net/sql-server-triggers/sql-server-drop-trigger/)
  * [`Transactions`](https://www.javatpoint.com/sql-server-transaction)

<br/>

### **[`Data types`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-data-types/)**
  * Exact Number types
    - `bigint`
    - `bit`
    - `decimal`
    - `int`
    - `money`
    - `numeric`
    - `smallint`
    - `smallmoney`
    - `tinyint`

  * Approximate Number types
    - `float`
    - `real`

  * Character Strings
    - `char`
    - `text`
    - `varchar`

  * Unicode Character Strings
    - `nchar`
    - `ntext`
    - `nvarchar`

  * Binary Strings
    - `binary`
    - `image`
    - `varbinary`

  * Date and Time
    - `date`
    - `datetime2`
    - `datetime`
    - `datetimeoffset`
    - `smalldatetime`
    - `time`

  * Miscellaneous
    - `rowversion`
    - `uniqueidentifier`
    - `hierarchyid`

<br/>

## **Flow of control**
  * [`IF-ELSE`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-if-else/)
  * [`WHILE`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-while/)
  * [`BREAK`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-break/)
  * [`CONTINUE`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-continue/)

<br/>

### **Statement types**

  * DML statements
    - `SELECT` statement
        - [`SELECT INTO`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-select-into/)
        - Sorting results
            - [`ORDER BY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-order-by/)
        - Limiting results
            - [`OFFSET FETCH`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-offset-fetch/)
            - [`SELECT TOP`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-select-top/)
        - Filtering results
            - [`DISTINCT`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-select-distinct/)
            - [`WHERE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-where/)
            - [`AND`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-and/)
            - [`OR`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-or/)
            - [`IN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-in/)
            - [`BETWEEN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-between/)
            - [`LIKE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-like/)
            - [`Aliasing`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-alias/)
        - Expressions
            - [`CASE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-case/)
            - [`COALESCE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-coalesce/)
            - [`NULLIF`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-nullif/)
        - Joins
            - [`INNER JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-inner-join/)
            - [`LEFT JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-left-join/)
            - [`RIGHT JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-right-join/)
            - [`FULL OUTER JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-full-outer-join/)
            - [`CROSS JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-cross-join/)
            - [`SELF JOIN`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-self-join/)
        - Grouping Results
            - [`GROUP BY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-group-by/)
            - [`HAVING`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-having/)
            - [`GROUP BY on more than 1 column`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-grouping-sets/)
            - [`CUBE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-cube/)
            - [`ROLLUP`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-rollup/)
        - Subqueries
            - [`Subquery`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-subquery/)
            - [`Correlated subquery`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-correlated-subquery/)
            - [`EXISTS`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-exists/)
            - [`ANY`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-any/)
            - [`ALL`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-all/)
        - Set operations
            - [`UNION`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-union/)
            - [`UNION ALL`](https://www.tutorialgateway.org/sql-union-all/)
            - [`INTERSECT`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-intersect/)
            - [`EXCEPT`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-except/)
        - Common Table Expression (CTE)
            - [`CTE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-cte/)
            - [`RECURSIVE CTE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-recursive-cte/)
        - [`Pivot`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-pivot/)


    - `INSERT` statement
        - [`INSERT single row`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-insert/)
        - [`INSERT multiple rows`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-insert/)
        - [`INSERT INTO SELECT`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-insert-into-select/)

    - `UPDATE` statement
        - [`UPDATE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-update/)
        - [`UPDATE based on the join result of query`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-update-join/)

    - [`DELETE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-delete/) statement

    - [`MERGE`](https://www.sqlservertutorial.net/sql-server-basics/sql-server-merge/) statement

    - [`BULK INSERT`](https://www.geeksforgeeks.org/sql-server-bulk-insert-data-from-csv-file-using-t-sql-command/)


  * DDL statements
    - `CREATE` statement
    - `DROP` statement
    - `TRUNCATE` statement

<br/>

## **Handling exceptions**
  * [`TRY CATCH`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-try-catch/)
  * [`RAISERROR`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-raiserror/)
  * [`THROW`](https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-throw/)

<br/>

## **SQL server in built functions**
  * `Aggregate functions`
    - [`AVG`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-avg/)
    - [`CHECKSUM_AGG`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-checksum_agg/)
    - [`COUNT`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-count/)
    - [`COUNT_BIG`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-count/)
    - [`MAX`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-max/)
    - [`MIN`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-min/)
    - [`SUM`](https://www.sqlservertutorial.net/sql-server-aggregate-functions/sql-server-sum/)
    - [`STDEV`](https://www.tutorialgateway.org/sql-stdev-function/)
    - [`STDEVP`](https://www.tutorialgateway.org/sql-stdevp-function/)
    - [`VAR`](https://www.tutorialgateway.org/sql-var-function/)
    - [`VARP`](https://www.tutorialgateway.org/sql-varp-function/)

  * `Date functions`
    - [`CURRENT_TIMESTAMP`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-current_time-function/)
    - [`GETUTCDATE`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-getutcdate-function/)
    - [`GETDATE`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-getdate-function/)
    - [`SYSDATETIME`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-sysdatetime-function/)
    - [`SYSUTCDATETIME`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-sysutcdatetime-function/)
    - [`SYSDATETIMEOFFSET`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-sysdatetimeoffset-function/)
    - [`DATENAME`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datename-function/)
    - [`DATEPART`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datepart-function/)
    - [`DAY`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-day-function/)
    - [`MONTH`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-month-function/)
    - [`YEAR`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-year-function/)
    - [`DATEDIFF`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datediff-function/)
    - [`DATEADD`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datediff-function/)
    - [`EOMONTH`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-eomonth-function/)
    - [`SWITCHOFFSET`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-switchoffset-function/)
    - [`TODATETIMEOFFSET`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-todatetimeoffset-function/)
    - [`DATEFROMPARTS`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datefromparts-function/)
    - [`DATETIME2FROMPARTS`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datetime2fromparts-function/)
    - [`DATETIMEOFFSETFROMPARTS`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-datetimeoffsetfromparts-function/)
    - [`TIMEFROMPARTS`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-timefromparts/)
    - [`ISDATE`](https://www.sqlservertutorial.net/sql-server-date-functions/sql-server-isdate-function/)

  * `System functions`
    - [`CAST`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-cast-function/)
    - [`TRY_CAST`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-try_cast-function/)
    - [`CONVERT`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-convert-function/)
        - [`Datetime to string`](https://www.sqlservertutorial.net/sql-server-system-functions/convert-datetime-to-string/)
        - [`String to Datetime`](https://www.sqlservertutorial.net/sql-server-system-functions/convert-string-to-datetime/)
        - [`Datetime to date`](https://www.sqlservertutorial.net/sql-server-system-functions/convert-datetime-to-date/)
    - [`TRY_CONVERT`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-try_convert-function/)
    - [`TRY_PARSE`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-try_parse-function/)
    - [`CHOOSE`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-choose-function/)
    - [`ISNULL`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-isnull-function/)
    - [`ISNUMERIC`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-isnumeric-function/)
    - [`IIF`](https://www.sqlservertutorial.net/sql-server-system-functions/sql-server-iif-function/)

  * `String functions`
    - [`ASCII`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-ascii-function/)
    - [`CHAR`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-char-function/)
    - [`CHARINDEX`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-charindex-function/)
    - [`CONCAT`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-concat-function/)
    - [`CONCAT_WS`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-concat_ws-function/)
    - [`DIFFERENCE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-difference-function/)
    - [`FORMAT`](https://www.tutorialgateway.org/sql-format/)
    - [`LEFT`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-left-function/)
    - [`LEN`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-len-function/)
    - [`LOWER`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-lower-function/)
    - [`LTRIM`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-ltrim-function/)
    - [`NCHAR`](https://www.tutorialgateway.org/sql-nchar-function/)
    - [`PATINDEX`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-patindex-function/)
    - [`QUOTENAME`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-quotename-function/)
    - [`REPLACE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-quotename-function/)
    - [`REPLICATE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-replicate-function/)
    - [`REVERSE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-reverse-function/)
    - [`RIGHT`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-right-function/)
    - [`RTRIM`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-rtrim-function/)
    - [`SOUNDEX`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-soundex-function/)
    - [`SPACE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-space-function/)
    - [`STR`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-str-function/)
    - [`STRING_AGG`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-string_agg-function/)
    - [`STRING_ESCAPE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-string_escape-function/)
    - [`STRING_SPLIT`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-string_split-function/)
    - [`STUFF`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-stuff-function/)
    - [`SUBSTRING`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-substring-function/)
    - [`TRANSLATE`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-translate-function/)
    - [`TRIM`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-trim-function/)
    - [`UNICODE`](https://www.tutorialgateway.org/sql-unicode-function/)
    - [`UPPER`](https://www.sqlservertutorial.net/sql-server-string-functions/sql-server-upper-function/)

  * `Window functions`
    - [`CUME_DIST`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-cume_dist-function/)
    - [`DENSE_RANK`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-dense_rank-function/)
    - [`FIRST_VALUE`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-first_value-function/)
    - [`LAG`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-lag-function/)
    - [`LAST_VALUE`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-last_value-function/)
    - [`LEAD`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-lead-function/)
    - [`NTILE`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-ntile-function/)
    - [`PERCENT_RANK`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-percent_rank-function/)
    - [`RANK`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-rank-function/)
    - [`ROW_NUMBER`](https://www.sqlservertutorial.net/sql-server-window-functions/sql-server-rank-function/)