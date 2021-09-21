# fusion_get_language_switch()

Get language switch arrays.

---

fusion_get_language_switch( void ) : array

## Parameters

No parameters.

## Return Values

(array)

## Examples

```php
$language_switch = fusion_get_language_switch();

if (!empty($language_switch)) {
    foreach ($language_switch as $folder => $langData) {
        //
    }
}
```
