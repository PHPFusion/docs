# get_theme_settings()

Fetch the settings from DB_SETTINGS_THEME.

---

get_theme_settings( string $theme_folder ) : mixed

## Parameters

$theme_folder (string) (Required) The name of the theme folder.

## Return Values

(array|bool) Associative array of settings or false if is empty.

## Examples

```php
$theme_settings = get_theme_settings('my_theme');

echo $theme_settings['facebook_url'];
```
