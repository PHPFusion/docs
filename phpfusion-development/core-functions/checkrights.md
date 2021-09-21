# checkrights()

Check if an Administrator has the correct rights assigned.

---

checkrights( string $rights ) : bool

## Parameters

$rights (string) (Required) Rights you want to check for the administrator.

## Return Values

(bool) True if the user is administrator with rights defined in $rights.

## Examples

```php
if (checkrights('M')) {
    echo 'User has access to User Management.';
}
```
