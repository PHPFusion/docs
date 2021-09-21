# get_rowstart()

Get max rowstart from a query to prevent renumbering pagenav.

---

get_rowstart( string $key, int $max_limit ) : int

## Parameters

$key (string) (Required) `$_GET` key.

$max_limit (int) (Required) Max limit.

## Return Values

(int)

## Examples

```php
$max_rows = 10;
$rowstart = get_rowstart('rowstart', $max_rows);

echo makepagenav($rowstart, 24, $max_rows);
```
