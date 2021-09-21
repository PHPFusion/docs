# getuserstatus()

Get a user status by the numeric code of status.

---

getuserstatus( int $userstatus ) : mixed

## Parameters

$userstatus (int) (Required) Status code 0 - 8.

## Return Values

(string|null) The name of the given user status, null if it does not exist.

## Examples

```php
echo getuserstatus(5);
// Cancelled
```

<div class="alert alert-info">
0 - Active, 1 - Banned, 2 - Unactivated, 3 - Suspended, 4 - Security Banned, 5 - Cancelled, 6 - Anonymous, 7 - Deactivated, 8 - Inactive
</div>
