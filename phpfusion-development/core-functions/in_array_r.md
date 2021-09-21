# in_array_r()

Recursive in_array.

---

in_array_r( string $needle, array $haystack [, bool $strict ] ) : bool

## Parameters

$needle (string) (Required) The searched value.

$haystack (array) (Required) The array.

$strict (bool) (Optional) If the third parameter strict is set to true then the in_array() function will also check the types of the needle in the haystack. Default value: false

## Return Values

(bool)

## Examples

```php
$array = [
    'scripting' => ['php', 'python', 'ruby'],
    'oop'       => ['java', 'perl', 'c++']
];

if (in_array_r('php', $array)) {
    // 
}
```
