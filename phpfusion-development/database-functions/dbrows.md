# dbrows()

Count the number of rows in a given database query.

---

dbrows( mixed $result ) : int

## Parameters

$result (string) (Required) The query resource that is being evaluated. This result comes from a call to dbquery().

## Return Values

(int) The number of rows in a result set or false on failure.

## Examples

```php
$result = dbquery("SELECT * FROM ".DB_TABLE);
$rows = dbrows($result);

echo $rows;
// The number of rows in the table
```
