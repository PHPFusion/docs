# getnotices()

Retrievs all notices for the group identified by the key provided.

---

getnotices( [ string $key, bool $delete ] ) : array

## Parameters

$key (string) (Optional) The key identifying a group or more holding notices, by default the page name in which the notice was set. Default value: FUSION_SELF

$delete (bool) (Optional) Whether to delete or keep a notice message after it was accessed. This only works if the notice was set or added while having $remove_after_access set to false. Default value: true

## Return Values

(array) The notices for the group identified by the provided key.

## Examples

```php
// common usage
echo rendernotices(getnotices());

// or you can create own function
foreach (getnotices() as $notices) {
    //
}
```
