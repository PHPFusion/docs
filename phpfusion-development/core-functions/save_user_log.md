# save_user_log()

Log user actions.

---

save_user_log( int $user_id, string $column_name, string $new_value, string $old_value ) : void

## Parameters

$user_id (int) (Required) User ID.

$column_name (string) (Required) Affected column.

$new_value (string) (Required) New value.

$old_value (string) (Required) Old value.

## Return Values

No value is returned.

## Examples

```php
$userdata = fusion_get_userdata();

save_user_log($userdata['user_id'], 'user_name', 'NewName', $userdata['user_name']);
```
