# make_page_breadcrumbs()

Hierarchy Page Breadcrumbs, generates breadcrumbs on all your category needs.

---

make_page_breadcrumbs( array $tree_index, array $tree_full, string $id_col, string $title_col [, string $getname ] ) : void

## Parameters

$tree_index (array) (Required) tree_index(dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent')).

$tree_full (array) (Required) dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent').

$id_col (string) (Required) news_cat_id.

$title_col (string) (Required) news_cat_name.

$getname (string) (Optional) The name of the `$_GET` parameter. Default value: rownav

## Return Values

No value is returned.

## Examples

```php
$tree_index = tree_index(dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent'));
$tree_full = dbquery_tree_full(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent');

make_page_breadcrumbs($tree_index, $tree_full, 'news_cat_id', 'news_cat_name');
```
