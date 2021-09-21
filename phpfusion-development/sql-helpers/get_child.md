# get_child()

Get child IDs from dbquery_tree() result.

---

get_child( array $index, int $parent_id [, array $children ] ) : array

## Parameters

$index (array) (Required) Results from dbquery_tree().

$parent_id (int) (Required) Parent ID.

$children (array) (Optional) Default value: []

## Return Values

(array)

## Examples

```php
$index = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$child = get_child($index, 1);
/*
Array
(
)
*/
```
