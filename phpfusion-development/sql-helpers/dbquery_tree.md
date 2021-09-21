# dbquery_tree()

Hierarchy ID to category output.

---

dbquery_tree( string $db, string $id_col, string $cat_col [, bool $filter, string $query_replace ] ) : array

## Parameters

$db (string) (Required) Table name.

$id_col (string) (Required) ID column.

$cat_col (string) (Required) Category column.

$filter (string) (Optional) Replace conditional structure. Default value: null

$query_replace (string) (Optional) Replace the entire query structure. Default value: null

## Return Values

(array) Returns cat-id relationships.

## Examples

```php
$data = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
/*
Array
(
    [0] => Array
        (
            [0] => 1
            [1] => 2
            [2] => 3
            ....
        )
)
*/
```
