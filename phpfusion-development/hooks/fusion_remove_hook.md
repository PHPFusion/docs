# fusion_remove_hook()

Remove hook.

---

fusion_remove_hook( string $name, string $function [, int $que, array $default_args, int $accepted_args ] ) : bool

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$function (string) (Optional) If you specify function name, it removes only that function from hook.

$que (int) (Optional) Values 1-10, where 1 runs first and 10 runs last. Default value: 10

## Return Values

(bool)

## Examples

```php
fusion_remove_hook('test_hook');
```
