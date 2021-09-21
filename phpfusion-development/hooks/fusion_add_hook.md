# fusion_add_hook()

Add a hook.

---

fusion_add_hook( string $name, string $function [, int $que, array $default_args, int $accepted_args ] ) : bool

## Parameters

$name (string) (Required) The name of the hook, this is your identifier.

$function (string) (Required) The callback function to run when the filter runs.

$que (int) (Optional) Values 1-10, where 1 runs first and 10 runs last. Default value: 10

$default_args (array) (Optional) The default state of parameter during adding hook. Default value: []

$accepted_args (int) (Optional) The limitation of the hook parameters the hook can accept. Default value: 1

## Return Values

(bool)

## Examples

```php
function do_something() {
    //
}

fusion_add_hook('test_hook', 'do_something');
```
