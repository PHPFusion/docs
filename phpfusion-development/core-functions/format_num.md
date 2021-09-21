# format_num()

Formats a number in a numeric acronym, and rounding.

---

format_num( int $value [, int $decimals, string $dec_point, string $thousand_sep, bool $round, bool $acryonym ] ) : string

## Parameters

$value (int) (Required) Number to format.

$decimals (int) (Optional) The number of decimals. Default value: null

$dec_point (string) (Optional) Decimal point. Default value: .

$thousand_sep (string) (Optional) Thousands separator. Default value: ,

$round (bool) (Optional) Round number. Default value: true

$acryonym (bool) (Optional) Acronym. Default value: true

## Return Values

(string)

## Examples

```php
echo format_num(67475845858);
// 67.48b
```
