# fusion_filter_hook()

Return output from running all available hooks added under the same namespace in one go and return array.

---

fusion_filter_hook( string $name [, mixed $... ] ) : array

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$... (mixed) (Optional) Zero or more parameters to be passed.

## Return Values

(array)

## Examples

```php
foreach (fusion_filter_hook('test_hook') as $data) {
    //
}
```
