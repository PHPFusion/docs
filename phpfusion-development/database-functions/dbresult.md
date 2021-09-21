# dbresult()

Fetch the first column of a specific row.

---

dbresult( mixed $result, int $row ) : mixed

## Parameters

$result (string) (Required) The query resource that is being evaluated. This result comes from a call to [dbquery()](dbquery.md).

$row (int) (Required) The row number from the result that's being retrieved. Row numbers start at 0.

## Return Values

(string|bool) The contents of one column from a MySQL result set or false on failure.

## Examples

```php
$result = dbquery("SELECT user_name FROM ".DB_USERS);

if ($result) {
    echo dbresult($result, 1);
}
// The name of the second user
```
