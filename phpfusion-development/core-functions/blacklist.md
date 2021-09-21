# blacklist()

UF blacklist for SQL - same as groupaccess() but $field is the user_id column.

---

blacklist( string $field ) : string

## Parameters

$field (string) (Required) User ID field.

## Return Values

(string) It can return an empty condition if the user_blacklist field is not installed.

## Examples

```php
$result = dbquery("SELECT user_id, user_name
    FROM ".DB_USERS."
    WHERE ".blacklist('user_id')."
");
```
