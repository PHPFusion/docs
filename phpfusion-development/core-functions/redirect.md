# redirect()

Redirect to internal or external URL.

---

redirect( string $location [, bool $delay, bool $script, int $code ] ) : void

## Parameters

$location (string) (Required) Destination URL

$delay (bool) (Optional) Meta refresh delay. Default value: false

$script (bool) (Optional) Set true if you want to redirect via javascript. Default value: false

$code (int) (Optional) HTTP status code to send. Default value: 200

## Return Values

No value is returned.

## Examples

```php
// Redirect to internal URL
redirect(BASEDIR.'page.php');

// Redirect to external URL
redirect('http://example.com/');
```
