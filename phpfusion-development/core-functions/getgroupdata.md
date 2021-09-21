# getgroupdata()

Get the data of the access level or user group

---

getgroupdata( int $group_id ) : array

## Parameters

$group_id (int) (Required) The ID of the group or access level to which you want to get a name.

## Return Values

(array) The ID, name, icon and description of the given group, null if it does not exist.

## Examples

```php
foreach (getgroupdata(1) as $group) {
    //
}
```
