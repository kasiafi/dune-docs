SHOW SCHEMAS

## Synopsis

``` text
SHOW SCHEMAS [ FROM catalog ] [ LIKE pattern ]
```

## Description

List the schemas in `catalog` or in the current catalog.

`Specify a pattern <like_operator>`{.interpreted-text role="ref"} in the
optional `LIKE` clause to filter the results to the desired subset. For
example, the following query allows you to find schemas that have `3` as
the third character:

    SHOW SCHEMAS FROM tpch LIKE '__3%'
