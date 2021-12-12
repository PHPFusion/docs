# format_date()

Replacement for strftime().

---

format_date( string $format, int $time ) : string

## Parameters

$file (string) (Required) Dateformat.


$time (int) (Required) Timestamp.

## Return Values

(string)

## Examples

```php
format_date("%V,%G,%Y", strtotime("12/30/2002"));
```
