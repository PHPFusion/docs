# get_depth()

Get current depth from dbquery_tree() result.

---

get_depth( array $index, int $child_id [, int $depth ] ) : array

## Parameters

$index (array) (Required) Results from dbquery_tree().

$child_id (int) (Required) Child ID.

$depth (int) (Optional) Default value: null

## Return Values

(array)

## Examples

```php
$index = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$depth = get_depth($index, 1);
// 1
```
