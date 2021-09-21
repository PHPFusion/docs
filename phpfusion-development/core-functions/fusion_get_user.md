# fusion_get_user()

Get the data of any user by ID.

---

fusion_get_user( int $user_id [, string $key ] ) : mixed

## Parameters

$user_id (int) (Required) User ID.

$key (string) (Optional) The key of one column. Default value: null

## Return Values

(array|string) Associative array of all data or one column by key.

## Examples

```php
$userdata = fusion_get_user(1);

echo $userdata['user_name'];
// admin
```
