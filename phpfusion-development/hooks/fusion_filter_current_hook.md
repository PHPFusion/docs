# fusion_filter_current_hook()

If hook add once, and only intended to be used once, use this function.

---

fusion_filter_current_hook( string $name [, mixed $... ] ) : mixed

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$... (mixed) (Optional) Zero or more parameters to be passed.

## Return Values

(mixed)

## Examples

```php
fusion_filter_current_hook('test_hook')
```
