# fusion_set_cookie()

Send a cookie with "samesite" support.

---

fusion_set_cookie( string $name, string $value, int $expires, string $path, string $domain [, bool $secure, bool $httponly, string $samesite ] ) : void

## Parameters

$name (string) (Required) The name of the cookie.

$value (string) (Required) The value of the cookie.

$expires (int) (Required) The time the cookie expires.

$path (string) (Required) The path on the server in which the cookie will be available on.

$domain (string) (Required) The (sub)domain that the cookie is available to.

$secure (bool) (Optional) Whether the client should send back the cookie only over HTTPS or null to auto-enable this when the request is already using HTTPS.

$httponly (bool) (Optional) Whether the cookie will be made accessible only through the HTTP protocol.

$samesite (string|null) (Optional) Whether the cookie will be available for cross-site requests. Possible value: none|lax|strict

## Return Values

No value is returned.

## Examples

```php
fusion_set_cookie(COOKIE_PREFIX.'test', 'value', time() + 31536000, '/', '', FALSE, FALSE, 'lax');
```
