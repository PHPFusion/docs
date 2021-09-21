# db_exists()

Check if a table exists.

---

db_exists( string $table ) : bool

## Parameters

$table (string) (Required) Table name. However, you can pass the table name with or without a prefix this function only check the prefixed tables of the PHPFusion.

## Return Values

(bool)

## Examples

```php
if (db_exists(DB_MESSAGES)) {
    //
}
```
