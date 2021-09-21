# fusion_get_groups()

Gets array of all access levels and user groups.

---

fusion_get_groups( [ array $remove ] ) : array

## Parameters

$remove (array) (Optional) Array of groups you want to exclude from output. Default value: []

## Return Values

(array) Array of all access levels and user groups.

## Examples

```php
foreach (fusion_get_groups() as $key => $group_name) {
    //
}
```
