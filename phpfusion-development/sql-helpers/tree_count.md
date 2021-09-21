# tree_count()

Count result from dbquery_tree().

---

tree_count( array $data [, string $column_name, string $value_to_match ] ) : int

## Parameters

$data (array) (Required) Results from dbquery_tree().

$column_name (string) (Optional) Default value: null

$value_to_match (string) (Optional) Default value: null

## Return Values

(int)

## Examples

```php
$data = dbquery_tree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$tree_count = tree_count($data);
// 1
```
