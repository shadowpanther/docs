---
editable: false
---

# LEFT



#### Syntax {#syntax}


```
LEFT( string, number )
```

#### Description {#description}
Returns a string that contains the number of characters specified in `number` from the beginning of the string `string`.

**Argument types:**
- `string` — `String`
- `number` — `Integer`


**Return type**: `String`

#### Example {#examples}

```
LEFT("Computer", 4) = "Comp"
```


#### Data source support {#data-source-support}

`Materialized Dataset`, `ClickHouse 19.13`, `Microsoft SQL Server 2017 (14.0)`, `MySQL 5.6`, `Oracle Database 12c (12.1)`, `PostgreSQL 9.3`, `YDB`.
