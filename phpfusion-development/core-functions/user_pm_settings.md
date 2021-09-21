# user_pm_settings()

Fetch user PM settings.

---

user_pm_settings( int $user_id [, string $key ] ) : mixed

## Parameters

$user_id (int) (Required) User ID.

$key (string) (Optional) The key of one column. Default value: null

## Return Values

(array|string) Associative array of all data or one column by key.

## Examples

```php
$pm_settings = user_pm_settings(1);

echo $pm_settings['user_pm_email_notify'];
// 1
```
