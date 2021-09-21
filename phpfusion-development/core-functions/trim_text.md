# trim_text()

Pure trim function.

---

trim_text( string $text [, int $length ] ) : string

## Parameters

$text (string) (Required) String to trim.

$length (int) (Optional) The number of characters. Default value: 300

## Return Values

(string) Trimmed text.

## Examples

```php
$text = 'The big brown fox jumped over the lazy dog';

echo trim_text($text, 10);
// The big brown...
```
