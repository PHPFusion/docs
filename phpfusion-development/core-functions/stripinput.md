# stripinput()

Prevents HTML in unwanted places

---

stripinput( mixed $text ) : mixed

## Parameters

$text (string|array) (Required) String or array to be stripped.

## Return Values

(string|array) The given string decoded as non HTML text.

## Examples

```php
$text = '<a href="www.example.com"><strong>Here is a site</strong></a>';

echo stripinput($text);
// <a href="www.example.com"><strong>Here is a site</strong></a>
```
