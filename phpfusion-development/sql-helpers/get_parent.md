# get_parent()

Get immediate parent ID from dbquery_tree() result.

---

get_parent( array $index, int $child_id ) : int

## Parameters

$index (array) (Required) Results from dbquery_tree().

$child_id (int) (Required) Child ID.

## Return Values

(int)

## Examples

```php
$index = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$parent = get_parent($index, 1);
// 0
```
