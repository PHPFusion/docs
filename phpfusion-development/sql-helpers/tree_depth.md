# tree_depth()

Get the total max depths of dbtree().

---

tree_depth( array $data, string $field, string $match [, int $depth ] ) : int

## Parameters

$data (array) (Required) Results from dbtree().

$filed (string) (Required)

$match (string) (Required)

$depth (int) (Optional) Default value: 1

## Return Values

(int)

## Examples

```php
$data = dbtree(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$tree_depth = tree_depth($data, 'news_cat_id', 1);
```
