# encode_code()

Encode and format code inside `<code>` tag.

---

encode_code( string $text ) : string

## Parameters

$text (string) (Required) String with code.

## Return Values

(string) Encoded and formatted code.

## Examples

```php
$text = '<code><!DOCTYPE html>
    <html>
    <head>
        Test
    </head>
    <body>
        code
    </body>
</html></code>';

echo encode_code($text);
/*
<pre><code>&lt;!DOCTYPE html&gt;
&nbsp; &nbsp; &lt;html&gt;
&nbsp; &nbsp; &lt;head&gt;
&nbsp; &nbsp; &nbsp; &nbsp; Test
&nbsp; &nbsp; &lt;/head&gt;
&nbsp; &nbsp; &lt;body&gt;
&nbsp; &nbsp; &nbsp; &nbsp; code
&nbsp; &nbsp; &lt;/body&gt;
&lt;/html&gt;</code></pre>
*/
```
