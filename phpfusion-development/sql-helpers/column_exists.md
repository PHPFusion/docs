# column_exists()

Determine whether column exists in a table.

---

column_exists( string $table, string $column [, bool $add_prefix ] ) : bool

## Parameters

$table (string) (Required) Table name.

$column (string) (Required) Column name.

$add_prefix (bool) (Optional) Delimiter. Default value: true

## Return Values

(bool)

## Examples

```php
if (column_exists(DB_USERS, 'user_name')) {
    //
}
```
