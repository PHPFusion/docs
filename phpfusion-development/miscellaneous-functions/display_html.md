# display_html()

Display set of buttons.

---

display_html( string $formname, string $textarea [, bool $html, bool $colors, bool $images, string $folder ] ) : string

## Parameters

$formname (string) (Required) The name of the form you are using the HTML buttons for.

$textarea (string) (Required) The name of the textarea which html will be inserted to.

$html (bool) (Optional) Setting this to true will display the HTML buttons, set false to prevent them from displaying. Default value: true

$colors (bool) (Optional) Setting true will display the HTML colors, set false to prevent them from displaying. Default value: true

$images (bool) (Optional) Setting true will display the select field with images, set false to prevent them from displaying. Default value: true

$folder (string) (Optional) If you have $images set to true, use this to define what image folder you want to get images from. Default value: ''

## Return Values

(string)

## Examples

```php
echo openform('testform', 'post');
echo form_textarea('test_textarea');
echo display_html('testform', 'test_textarea');
echo closeform();
```
