# Manage Data with T-SQL

### Logical query processing
 From -> WHERE -> Group By -> Having -> SELECT -> ORDER BY
### 这个logical query processing 背后的影响:
1. 由于Select出现在Where的后边， 我们在SELECT当中使用的Alias就没法用了，因为是在后边定义的。
这个导致的后果就是我们必须在Where statment当中使用公式或者计算本身
2. Having这个clause出现在Group by的后边，这个其实用来filter group的

## Filtering date and time data
### 标准日期格式 
只有20190203 YYYYMMDD在SQL SERVER当中才是标准格式， 2019-02-03是不算的。


## 1.3 Implement functions and aggregate data
* scalar-valued functions return a single value and table-valued functions return a table result.
#### Type conversion functions
* CAST
> CAST([Source Expression] AS Format): CAST('100' AS INT)
* Convert








# Query Data with advanced T-SQL components
## Subquery and apply
# Program Databases by using T-SQL
