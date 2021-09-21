# get_parent_array()

Get immediate parent array from dbquery_tree_full() result.

---

get_parent_array( array $data, int $child_id ) : array

## Parameters

$data (array) (Required) Results from dbquery_tree_full().

$child_id (int) (Required) Child ID.

## Return Values

(array)

## Examples

```php
$index = dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');
$parent_array = get_parent_array($index, 1);
/*
Array
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
*/
```
