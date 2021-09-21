# check_admin_pass()

Check if admin password matches userdata.

---

check_admin_pass( string $password ) : bool

## Parameters

$password (string) (Required) Password.

## Return Values

(bool) This function will return true if the password matches the user's admin password or if the admin's cookie or session is set and is valid.

## Examples

```php
if (check_admin_pass('SECRET_PASSWORD')) {
    //
}
```
