# fusion_get_locale()

Fetch a locales.

---

fusion_get_locale( [ string $key, mixed $include_file ] ) : mixed

## Parameters

$key (string) (Optional) The key of one locale. Default value: null

$include_file (string|array) (Optional) The full path of the file which to be included. Default value: ''

## Return Values

(array|string) Associative array of locales or one locale by key.

## Examples

```php
$locale = fusion_get_locale();
echo $locale['welcome'];
// Welcome back
```

<div class="alert alert-info">
The global.php file is loaded automatically.
</div>
