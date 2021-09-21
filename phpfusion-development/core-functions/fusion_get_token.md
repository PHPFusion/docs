# fusion_get_token()

Get form tokens.

---

fusion_get_token( string $form_id [, int $max_tokens ] ) : string

## Parameters

$form_id (string) (Required) Form ID.

$max_tokens (int) (Optional) Max tokens. Default value: 5

## Return Values

(string)

## Examples

```php
echo fusion_get_token('fusionform', 5);
// 1-1600889268-e2f1342970bae8a8db5e767e7c004ed5a72558c82ba
```
