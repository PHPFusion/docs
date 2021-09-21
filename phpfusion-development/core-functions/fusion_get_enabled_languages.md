# fusion_get_enabled_languages()

Get the array of enabled languages.

---

fusion_get_enabled_languages( void ) : array

## Parameters

No parameters.

## Return Values

(array)

## Examples

```php
$languages = fusion_get_enabled_languages();

if (count($languages) > 1) {
    foreach ($languages as $language_folder => $language_name) {
        //
    }
}
```
