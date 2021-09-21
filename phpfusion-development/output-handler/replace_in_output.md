# replace_in_output()

Replace something in the output using regexp.

---

replace_in_output( string $target, string $replace [, string $modifiers ] ) : void

## Parameters

$target (string) (Required) What you want to replace.

$replace (string) (Required) This is what it will be replaced with.

$modifiers (string) (Optional) The pattern to search for as a string.

## Return Values

No value is returned.

## Examples

```php
$target = '<!--news_prepost_2-->';
$replace = '<!--news_prepost_2-->n<br />Hello world!';
 
replace_in_output($target, $replace);
```
