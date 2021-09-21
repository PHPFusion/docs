# theme_exists()

Check if a given theme exists and is valid.

---

theme_exists( string $theme ) : bool

## Parameters

$theme (string) (Required) The theme folder you want to check.

## Return Values

(bool) False if the theme does not exist and true if it does.

## Examples

```php
if (!theme_exists('my_theme')) {
    echo 'my_theme theme does not exist!';
}
```
