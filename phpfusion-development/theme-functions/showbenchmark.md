# showbenchmark()

Show benchmark and database performance.

---

showbenchmark( [ bool $show_sql_performance, string $performance_threshold ] ) : string

## Parameters

$show_sql_performance (bool) (Optional) Set true to popup SQL analysis modal. Default value: false

$performance_threshold (string) (Optional) Results that are slower than this value will be highlighted. Default value: 0.01

## Return Values

(string)

## Examples

```php
echo showbenchmark();
// Render time: 0.07051 seconds | Average: 0.15208 (-0.32572) seconds
```
