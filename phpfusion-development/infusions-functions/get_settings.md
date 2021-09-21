# get_settings()

Get all the settings for the given infusion.

---

get_settings( string $settings_inf [, string $key ] ) : mixed

## Parameters

$settings_inf (string) (Required) The infusion you'll get the settings for.

$key (string) (Optional) The key of one setting. Default value: null

## Return Values

(array|string) Associative array of settings or one setting by key.

## Examples

```php
$blog_settings = get_settings('blog');

echo $blog_settings['blog_thumb_ratio'];
// 0
```
