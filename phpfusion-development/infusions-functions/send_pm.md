# send_pm()

Sends a Private Message to specified user with email notification if the receiver has enabled it.

---

send_pm( int $to, int $from, string $subject, string $message [, string $smileys, bool $to_group ] ) : void

## Parameters

$to (int) (Required) Recepient either group_id or user_id.

$from (int) (Required) Sender's user id.

$subject (string) (Required) Message subject.

$message (string) (Required) Message body.

$smileys (string) (Optional) Use smileys or not. Possible values: y|n. Default value: y

$to_group (bool) (Optional) Set to true if sending to the entire user group's members. Default value: false

## Return Values

No value is returned.

## Examples

```php
// note if you set 0 to $from, message will be sent as message from system
send_pm(1, 0, 'Test', 'Test message');
```
