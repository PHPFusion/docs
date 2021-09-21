# dbquery_order()

Table rows ordering.

---

dbquery_order( string $dbname, int $current_order, string $order_col [, int $current_id, string $id_col, int $current_category, string $cat_col, bool $multilang, string $multilang_col, string $mode ] ) : mixed

## Parameters

$dbname (string) (Required) Table name.

$current_order (int) (Required)

$order_col (string) (Required)

$current_id (int) (Optional) Default value: 0

$id_col (string) (Optional) Default value: null

$current_category (int) (Optional) Default value: 0

$cat_col (string) (Optional) Default value: null

$multilang (bool) (Optional) Default value: false

$multilang_col (string) (Optional) Default value: ''

$mode (string) (Optional) Possible value: save, update, delete. Default value: update

## Return Values

(mixed)

## Examples

```php
dbquery_order(DB_PHOTOS, $data['photo_order'], 'photo_order', $data['photo_id'], 'photo_id', NULL, NULL, FALSE, '', 'update');
```
