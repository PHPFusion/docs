# dbtree()

Get hierarchy array with injected child key.

---

dbtree( string $db, string $id_col, string $cat_col [, string $cat_value, bool $filter ] ) : array

## Parameters

$db (string) (Required) Table name.

$id_col (string) (Required) ID column.

$cat_col (string) (Required) Category column.

$cat_value (string) (Optional) Category value. Default value: null

$filter (string) (Optional) Replace conditional structure. Default value: null

## Return Values

(array)

## Examples

```php
$data = dbtree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
/*
Array
(
)
*/
```
