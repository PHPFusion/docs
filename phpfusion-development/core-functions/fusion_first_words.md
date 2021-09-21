# fusion_first_words()

Trim a text to a number of words.

---

fusion_first_words( string $text, int $limit [, string $suffix ] ) : string

## Parameters

$text (string) (Required) String to trim.

$limit (int) (Required) The number of words.

$suffix (string) (Optional) If $text is longer than $limit, $suffix will be appended. Default value: `&hellip;`

## Return Values

(string) String trimmed to the given length.

## Examples

```php
$text = 'The big brown fox jumped over the lazy dog';

echo fusion_first_words($text, 5);
// The big brown fox jumped…
```
