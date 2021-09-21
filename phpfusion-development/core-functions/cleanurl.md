# cleanurl()

Clean the URL and prevents entities in server globals.

---

cleanurl( string $url ) : string

## Parameters

$url (string) (Required) URL.

## Return Values

(string) $url clean and ready for use XHTML strict and without any dangerous code.

## Examples

```php
$url = 'http://example.com/?this=that&that=this<&tagg>';

echo cleanurl($url);
// http://www.test.com?this=that&that=this&tagg
```
