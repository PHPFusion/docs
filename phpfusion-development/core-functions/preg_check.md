# preg_check()

Custom preg_match function.

---

preg_check( string $expression, mixed $value ) : bool

## Parameters

$expression (string) (Required) The expression to search for.

$value (mixed) (Required) The input string.

## Return Values

(bool) False when value is an array.

## Examples

```php
$value = 'abc123';

if (preg_check("/^[0-9A-Za-z]+$/", $value)) {
    //
}
```
