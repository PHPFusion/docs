# dbnextid()

Get the next auto_increment id of a table.

---

dbnextid( string $table ) : int

## Parameters

$table (string) (Required) Database table.

## Return Values

(int)

## Examples

```php
echo dbnextid(DB_TABLE);
```
