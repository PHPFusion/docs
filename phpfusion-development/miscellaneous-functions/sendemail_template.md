# sendemail_template()

Send email with template

---

sendemail_template( string $template_key, string $subject, string $message, string $user, string $receiver, string $thread_url, string $toemail [, string $sender, string $fromemail ] ) : bool

## Parameters

$template_key (string) (Required) Template key.

$subject (string) (Required) Email subject.

$message (string) (Required) Email message.

$user (string) (Required) Username.

$receiver (string) (Required) The name of the receiver.

$thread_url (string) (Required) Forum thread url.

$toemail (string) (Required) The mail of the receiver.

$sender (string) (Optional) Sender's name. Default value: ''

$fromemail (string) (Optional) Sender's email. Default value: ''

## Return Values

(bool) True, if email was sent.

## Examples

```php
require_once INCLUDES.'sendmail_include.php';

$toname = 'Joe User';
$tomail = 'joe@example.net';
$subject = 'Here is the subject';
$message = 'This is the mail body.';

sendemail_template('CONTACT', $subject, $message, '', $toname, '', $tomail);
```
