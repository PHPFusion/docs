# getuserlevel()

Get a user level's name by the numeric code of level.

---

getuserlevel( int $userlevel ) : mixed

## Parameters

$userlevel (int) (Required) Level code.

## Return Values

(string|null) The name of the given user level, null if it does not exist.

## Examples

```php
echo getuserlevel(-102);
// Administrator
```

<div class="alert alert-info">
This function will not work on user group names, for that purpose we recommend you to use the getgroupname().
</div>
