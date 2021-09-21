# user_blacklisted()

Check if user was blacklisted by a member.

---

user_blacklisted( int $user_id ) : bool

## Parameters

$user_id (id) (Required) User ID.

## Return Values

(bool) True if the user is blacklisted.

## Examples

```php
$user_id = 3;

if (user_blacklisted($user_id)) {
    echo 'User is blacklisted.';
}
```
