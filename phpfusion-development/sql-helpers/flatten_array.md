# flatten_array()

To flatten any multidimensional array.

---

flatten_array( array $array ) : array

## Parameters

$array (array) (Required) Multidimensional array.

## Return Values

(array)

## Examples

```php
$array[] = [
    'title' => 'Test',
    'page'  => 2
];
$array = flatten_array($array);
/*
Array
(
    [title] => Test
    [page] => 2
)
*/
```
