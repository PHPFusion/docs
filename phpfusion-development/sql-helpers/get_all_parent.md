# get_all_parent()

Get parent IDs from dbquery_tree() result.

---

get_all_parent( array $index, int $child_id [, array $list ] ) : mixed

## Parameters

$index (array) (Required) Results from dbquery_tree().

$child_id (int) (Required) Child ID.

$list (array) (Optional) Default value: []

## Return Values

(array|int)

## Examples

```php
$index = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$parent = get_all_parent($index, 1);
// 0
```
