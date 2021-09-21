# new_array()

Shorthand to build/combines an array.

---

new_array( array $array [, array $array2 ] ) : array

## Parameters

$array (array) (Required) Initial array to create with keys named in a non-multidimensional single array. This will create a multidimensional blank array.

$array2 (array) (Optional) Override. An array default value that consist of keys and defined values. Default value: []

## Return Values

(array)

## Examples

```php
$new_array = new_array(
    ['column', 'coumn2', 'column3'],
    ['column' => 'default']
);

/*
Array
(
    [column] => default
    [coumn2] => 
    [column3] => 
)
*/
```
