# tree_index()

Get index information from dbquery_tree_full().

---

tree_index( array $data ) : array

## Parameters

$data (array) (Required) Array generated from dbquery_tree_full().

## Return Values

(array)

## Examples

```php
$data = dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$tree_index = tree_index($data);
/*
Array
(
    [0] => Array
        (
            [0] => 1
            [1] => 2
            [2] => 3
            ....
        )
)
*/
```
