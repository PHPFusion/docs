# fusion_apply_hook()

Run the hooks without any output.

---

fusion_apply_hook( string $name [, mixed $... ] ) : mixed

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$... (mixed) (Optional) Zero or more parameters to be passed.

## Return Values

(mixed)

## Examples

```php
fusion_apply_hook('test_hook');
```
