# get_http_response_code()

Get HTTP response code.

---

get_http_response_code( string $url ) : mixed

## Parameters

$url (string) (Required) URL.

## Return Values

(bool|string)

## Examples

```php
$url = 'https://www.google.com/';

if (get_http_response_code($url) == 200) {
    //
}
```
