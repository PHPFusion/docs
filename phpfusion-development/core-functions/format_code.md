# format_code()

Add correct amount of spaces and tabs inside code.

---

format_code( string $text ) : string

## Parameters

$text (string) (Required) The text you want to format.

## Return Values

(string) Formatted code.

## Examples

```php
$text = '   Indent goes here.';

echo format_code($text);
// &nbsp; &nbsp;Indent goes here.
```
