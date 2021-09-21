# checkgroup()

Check if user is assigned to the specified user group(s).

---

checkgroup( int $group [, string $delim ] ) : bool

## Parameters

$group (int) (Required) The group number you want to check for the user.

$delim (string) (Optional) Delimiter. Default value: ,

## Return Values

(bool) True if the user is in the group.

## Examples

```php
$group = -101;

if (checkgroup($group)) {
    //
}

// You can also check multiple groups
$groups = '-103,2';
if (checkgroup($groups)) {
    //
}
```
