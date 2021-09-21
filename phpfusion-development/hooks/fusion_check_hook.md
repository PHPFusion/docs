# fusion_check_hook()

Checks if there is a hook by the $name and $function specified registered into the hook instance.

---

fusion_check_hook( string $name [, string $function ] ) : bool

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$function (string) (Optional) It checks if function in that hook exists. Default value: ''

## Return Values

(bool)

## Examples

```php
if (fusion_check_hook('test_hook')) {
    //
}
```
