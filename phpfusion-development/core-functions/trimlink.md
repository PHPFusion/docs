# trimlink()

Prevent strings from growing to long and breaking the layout.

---

trimlink( string $text, int $length ) : string

## Parameters

$text (string) (Required) String to trim.

$length (int) (Required) Max length of the string.

## Return Values

(string) String trimmed to the given length.

## Examples

```php
$text = 'The big brown fox jumped over the lazy dog';

echo trimlink($text, 10);
// The big...
```
