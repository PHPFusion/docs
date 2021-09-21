# fusion_get_contents()

cURL method to get any contents for Apache that does not support SSL for remote paths.

---

fusion_get_contents( string $url ) : mixed

## Parameters

$url (string) (Required)

## Return Values

(bool|string)

## Examples

```php
$data = fusion_get_contents('https://example.com/data');
```
