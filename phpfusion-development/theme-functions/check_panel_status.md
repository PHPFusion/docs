# check_panel_status()

Checks the panel status for given side.

---

check_panel_status( string $side ) : bool

## Parameters

$side (string) (Required) Possible value: left, right, upper, aupper, lower, blower, user1, user2, user3, user4

## Return Values

(bool)

## Examples

```php
if (check_panel_status('left')) {
    //
}
```
