# fusion_get_function()

Load any function and return its value.

---

openside ( string $function [, mixed $... ] ) : mixed

## Parameters

$function (string) (Required) Function name.

$... (mixed) (optional) Zero or more parameters to be passed, depending on function.

## Return Values

(string)

## Examples

```php
$html = fusion_get_function('opentable', 'Title');
```
