# set_admin_pass()

Set password of the currently logged in an administrator.

---

set_admin_pass( string $password ) : bool

The function will set the `$_COOKIE[COOKIE_PREFIX.'admin']` if the submitted admin password matches the user's admin password in `$userdata['user_admin_password']`.

## Parameters

$password (string) (Required) Any password.

## Return Values

(bool) True if the password matches the user's admin password or if the admin's cookie or session is set and is valid

## Examples

```php
set_admin_pass('SECRET_PASSWORD');
```
