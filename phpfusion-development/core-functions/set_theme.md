# set_theme()

Set a valid theme.

---

set_theme( string $theme ) : void

## Parameters

$theme (string) (Required) The theme folder you want to set.

## Return Values

No value is returned.

## Examples

```php
set_theme('my_theme');
```

<div class="alert alert-info">
This function can only be called once, in the maincore.php, as it sets CONSTANTS which can not be set again!
</div>
