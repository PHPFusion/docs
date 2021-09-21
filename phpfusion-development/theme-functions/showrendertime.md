# showrendertime()

Show PHPFusion performance.

---

showrendertime( [ bool $queries ] ) : string

## Parameters

$queries (bool) (Optional) The number of queries used on the current page. Default value: true

## Return Values

(string)

## Examples

```php
echo showrendertime();
// Render time: 0.06983 seconds | Average: 0.12833 (-0.02836) seconds | Queries: 32
```
