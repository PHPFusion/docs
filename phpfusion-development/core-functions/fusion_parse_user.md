# fusion_parse_user()

Tag a user by simply just posting his name like @Nick and if found, returns a tooltip.

---

fusion_parse_user( string $user_name [, string $tooltip ] ) : string

## Parameters

$user_name (string) (Required) @Nick.

$tooltip (string) (Optional) Additional info (E.g. `$userdata['user_lastvisit']-120 < TIME ? 'Online' : 'Offline'`). Default value: ''

## Return Values

(string) Tooltip with info.

## Examples

```php
$user_name = '@Nick';

echo fusion_parse_user($user_name);
```
