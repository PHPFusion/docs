# set_setting()

Update a setting for the given infusion or create it if the setting does not exist.

---

set_setting( string $setting_name, string $setting_value, string $setting_inf ) : bool

## Parameters

$setting_name (string) (Required) The name of the setting, must be unique for each infusion.

$setting_value (string) (Required) The value of the setting.

$setting_inf (string) (Required) The infusion name this setting belongs to.

## Return Values

(bool) Returns true on successful update / insert or false on error.

## Examples

```php
set_setting('allow_upload', 1, 'my_infusion');
```
