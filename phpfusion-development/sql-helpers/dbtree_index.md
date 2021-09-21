# dbtree_index()

Lighter version of dbtree() with only id and child key.

---

dbtree( string $db, string $id_col, string $cat_col [, string $cat_value ] ) : array

## Parameters

$db (string) (Required) Table name.

$id_col (string) (Required) ID column.

$cat_col (string) (Required) Category column.

$cat_value (string) (Optional) Category value. Default value: null

## Return Values

(array)

## Examples

```php
$data = dbtree_index(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
/*
Array
(
    [1] => Array
        (
            [news_cat_id] => 1
            [news_cat_parent] => 0
            [news_cat_name] => Bugs
            [news_cat_image] => bugs.svg
            [news_cat_visibility] => 0
            [news_cat_draft] => 0
            [news_cat_sticky] => 0
            [news_cat_language] => English
        )
    ....
)
*/
```
