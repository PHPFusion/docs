# display_bbcodes()

Display BBCode buttons for a given textarea.

---

display_bbcodes($width [, string $textarea_name, string $inputform_name, string $selected ] ) : string

## Parameters

$width (string) (Required) Width of the DIV which holds all the BBCode buttons.

$textarea_name (string) (Optional) The name of the textarea the BBCodes will be inserted to. Default value: message

$inputform_name (string) (Optional) The name of the form the BBCodes will be inserted to. Default value: inputform

$selected (string) (Optional) Show only certain BBCodes separated by |. Dedfault value: ''

## Return Values

(string)

## Examples

```php
echo openform('testform', 'post');
echo form_textarea('test_textarea');
echo display_bbcodes('100%', 'testform', 'test_textarea');
echo closeform();
```
