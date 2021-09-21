# dbarray()

Fetch one row as an associative array.

---

dbarray( mixed $result ) : array

## Parameters

$result (string) (Required) The query resource that is being evaluated. This result comes from a call to dbquery().

## Return Values

(array) Returns an associative array of strings that corresponds to the fetched row.

## Examples

```php
$result = dbquery("SELECT * FROM ".DB_TABLE);

if (dbrows($result) > 0) {
    while ($data = dbarray($result)) {
        //
    }
}
```
