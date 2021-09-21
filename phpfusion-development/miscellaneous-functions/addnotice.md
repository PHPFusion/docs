# addnotice()

Adds a notice message to the group identified by the key provided.

---

addnotice( $status, $value [, string $key, bool $remove_after_access ] ) : void

## Parameters

$status (string) (Required) The status of the message. Possible values: warning|info|success|danger

$value (string) (Required) The message.

$key (string) (Optional) The key identifying a group or more holding notices, by default the page name in which the notice was set. Default value: FUSION_SELF

$remove_after_access (bool) (Optional) Whether the notice should be automatically removed after it was displayed once, if set to false when getnotices() is called you have the option to keep the notice even after it was accesed. Default value: true

## Return Values

No value is returned.

## Examples

```php
addnotice('success', 'Settings has been updated.');
```
