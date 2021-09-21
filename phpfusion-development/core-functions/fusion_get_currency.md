# fusion_get_currency()

Get currency symbol by using a 3-letter ISO 4217 currency code.

---

fusion_get_currency( [ string $iso, bool $description ] ) : mixed

## Parameters

$iso (string) (Optional) 3-letter ISO 4217. Default value: null

$description (bool) (Optional) Set to false for just symbol. Default value: true

## Return Values

(array|string) Array of currencies or string with one currency.

## Examples

```php
$currency = fusion_get_currency();

echo $currency['AED'];
// Emirati Dirham (د.إ)
```
