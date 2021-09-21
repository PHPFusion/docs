# get_root()

Get tree root ID of a child from dbquery_tree() result.

---

get_root( array $index, int $child_id ) : int

## Parameters

$index (array) (Required) Results from dbquery_tree().

$child_id (int) (Required) Child ID.

## Return Values

(int)

## Examples

```php
$index = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$root = get_root($index, 1);
// 1
```
