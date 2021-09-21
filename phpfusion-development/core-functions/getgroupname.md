# getgroupname()

Get the name of the access level or user group.

---

getgroupname( int $group_id [, bool $return_desc, bool $return_icon ] ) : mixed

## Parameters

$group_id (int) (Required) The ID of the group or access level to which you want to get a name.

$return_desc (bool) (Optional) If true, description will be returned instead of name. Default value: false

$return_icon (bool) (Optional) If true, icon will be returned next to name. Default value: false

## Return Values

(string|null) The name or icon or description of the given group, null if it does not exist.

## Examples

```php
echo getgroupname(1, false, true);
// <i class='fa fa-user'></i> Group Name
```
