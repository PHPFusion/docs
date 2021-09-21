# fusion_get_userdata()

Fetch user data of the currently logged-in user from DB_USERS.

---

fusion_get_userdata( [ string $key ] ) : mixed

## Parameters

$key (string) (Optional) The key of one column. Default value: null

## Return Values

(array|string) Associative array of all data or one column by key.

## Examples

```php
$userdata = fusion_get_userdata();
echo $userdata['user_name'];
// admin
```
