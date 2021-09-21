# modalfooter()

Adds a modal footer in between openmodal and closemodal.

---

modalfooter( string $content [, bool $dismiss ] ) : string

## Parameters

$content (string) (Required) Footer content.

$dismiss (bool) (Optional) Enable dismissal of modal. Default value: false

## Return Values

(string)

## Examples

```php
echo openmodal('test_modal', 'Title', ['button_id' => 'modal_testing']);
echo 'Content goes here';
echo modalfooter('Footer content goes here');
echo closemodal();

echo '<button type="button" id="modal_testing">Open modal</button>';
```
