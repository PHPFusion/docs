# array_depth()

Get maximum depth of a hierarchy tree.

---

array_depth( array $array ) : int

## Parameters

$array (array) (Required) Results from dbquery_tree().

## Return Values

(int)

## Examples

```php
$array = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$array_depth = array_depth($array);
// 2
```
