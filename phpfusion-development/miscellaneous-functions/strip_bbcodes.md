# strip_bbcodes()

Strip declared BBCodes and their content away from quoted messages.

---

strip_bbcodes( string $text ) : string

## Parameters

$text (string) (Required) A string containing text with bbcodes.

## Return Values

(string)

## Examples

```php
require_once INCLUDES.'bbcode_include.php';

$text = 'This is a text with some [b]bold[/b] text and a [url=phpfusion.com]link[/url]. But we have some [hide]"this text is hidden"[/hide] hidden text.';

echo strip_bbcodes($text);
// This is a text with some [b]bold[/b] text and a [url=phpfusion.com]link[/url]. But we have some hidden text.
```
