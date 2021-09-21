# is_json()

Checks whether a string is JSON or not.

---

is_json( string $string ) : bool

## Parameters

$string (string) (Required) The string to be checked.

## Return Values

(bool)

## Examples

```php
$string = '{"name":"John", "age":30, "car":null}';

if (is_json($string)) {
    echo 'String is JSON.';
}
// String is JSON.
```
