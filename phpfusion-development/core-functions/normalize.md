# normalize()

Replaces special characters in a string with their "non-special" counterpart.

---

normalize( string $value ) : string

## Parameters

$value (string) (Required) The input string.

## Return Values

(string) Normalized string.

## Examples

```php
$value = "Random string: úäľščťžýá";

echo normalize($value);
// Random string: ualsctzya
```
