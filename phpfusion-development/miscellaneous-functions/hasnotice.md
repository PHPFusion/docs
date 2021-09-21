# hasnotice()

Checks whether a group identified by the key provided has any notices.

---

hasnotice( [ string $key ] ) : bool

## Parameters

$key (string) (Optional) The key identifying a group or more holding notices, by default the page name in which the notice was set. Default value: FUSION_SELF

## Return Values

(bool) Ture if the group has any notices.

## Examples

```php
if (hasnotice(FUSION_SELF)) {
    //
}
```
