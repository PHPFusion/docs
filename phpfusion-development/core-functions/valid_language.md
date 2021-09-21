# valid_language()

Check if a given language is valid or if exists.

---

valid_language( string $lang [, bool $file_check ] ) : bool

## Parameters

$lang (string) (Required) The name of the language.

$file_check (bool) (Optional) Intended to be used when enabling languages in Admin Panel. Default value: false

## Return Values

(bool)

## Examples

```php
if (valid_language('English')) {
    echo 'The language is valid and ready to use.';
}
```
