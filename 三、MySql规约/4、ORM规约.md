ORM规约
=====


#### 1. 【强制】在表查询中,一律不要使用 * 作为查询的字段列表,需要哪些字段必须明确写明。

> 说明: 1 ) 增加查询分析器解析成本。2 ) 增减字段容易与 resultMap 配置不一致。

