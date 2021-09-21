# descript()

Sanitize text and remove a potentially dangerous HTML and JavaScript.

---

descript( string $text [, bool $strip_tags, bool $strip_scripts ] ) : string

## Parameters

$text (string) (Required) String to be descripted.

$strip_tags (bool) (Optional) Removes potentially dangerous HTML tags. Default value: true

$strip_scripts (bool) (Optional) Removes `<script>` tags. Default value: true

## Return Values

(string) Sanitized and safe string.

## Examples

```php
$text = 'Text <a href="javascript:function()">click</a> <i onload=xss></i> <script>javascript code</script>';

echo descript($text);
// Text &lt;a href=&quot;nojavascript...function()&quot;&gt;click&lt;/a&gt; &lt;i &gt;&gt;&lt;/i&gt; javascript code
```
