# users_groupaccess()

Check if user has access to the group.

---

users_groupaccess( int $group_id ) : bool

## Parameters

$group_id (int) (Required) The ID of the group.

## Return Values

(bool) True if the user has access.

## Examples

```php
$id = 1;

if (users_groupaccess($id)) {
    echo 'User has access to '.getgroupname($id);
}
```
