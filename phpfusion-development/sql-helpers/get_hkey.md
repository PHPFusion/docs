# get_hkey()

Get tree root ID of a child via SQL. Alternative function to get_root().

---

get_hkey( string $db, string $id_col, string $cat_col, int $current_id ) : int

## Parameters

$db (string) (Required) Table name.

$id_col (string) (Required) ID column.

$cat_col (string) (Required) Category column.

$current_id (string) (Required) The current id of the item.

## Return Values

(int)

## Examples

```php
$root = get_hkey(DB_NEWS_CATS, 'news_cat_id', 'news_cat_parent', 1);
// 1
```
