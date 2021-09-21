# groupaccess()

Getting the access levels used when asking the database for data.

---

groupaccess( string $field [, string $delim ] ) : string

## Parameters

$field (string) (Required) MySQL's field from which you want to check access.

$delim (string) (Optional) Delimiter. Default value: ,

## Return Values

(string) The part of WHERE clause, always returns a condition.

## Examples

```php
$result = dbquery("SELECT item, access
    FROM ".DB_TABLE."
    WHERE ".groupaccess('access')."
    ORDER BY item DESC
");
```
