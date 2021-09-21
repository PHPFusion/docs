# translate_lang_names()

Translate locale folder name into localized language or folder name if is not localized.

---

translate_lang_names( [ string $language ] ) : mixed

## Parameters

$language (string) (Optional) Default value: null

## Return Values

(string|array) If $language is not set, it returns a full array.

## Examples

```php
echo translate_lang_names('Slovak');
// Slovenčina
```
