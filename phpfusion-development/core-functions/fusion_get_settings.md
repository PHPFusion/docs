# fusion_get_settings()

Fetch the settings from the database.

---

fusion_get_settings( [ string $key ] ) : mixed

## Parameters

$key (string) (Optional) The key of one setting. Default value: null

## Return Values

(array|string) Associative array of settings or one setting by key.

## Examples

```php
$settings = fusion_get_settings();
echo $settings['siteurl'];
// http://example.com/
```
