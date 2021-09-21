# form_text()

Generates a text input.

---

form_text( string $input_name [, string $label, string $input_value, array $options ] ) : string

## Parameters

$input_name (string) (Required) Name of the input, by default it's also used as the ID for the input.

$label (string) (Optional) Input label. Default value: ''

$input_value (string) (Optional) The value to be displayed. Default value: ''

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| type | string | text | Possible value: text, number, password, email, url, color, date, datetime, datetime-local, month, range, search, tel, time, week. |
| required | bool | false | Whether this field is required during form submission. |
| label_icon | string | '' |  |
| feedback_icon | string | '' |  |
| safemode | bool | false |  |
| regex | string | '' |  |
| regex_error_text | string | '' |  |
| callback_check | bool | false |  |
| input_id | string | $input_name |  |
| placeholder | string | '' | A placeholder for the field. |
| deactivate | bool | false | Disable the input and set it as readonly. |
| width | string | '' | Accepts px or % values. |
| inner_width | string | '' | Accepts px or % values. |
| class | string | '' |  |
| inner_class | string | '' |  |
| inline | bool | false |  |
| min_length | int | 1 |  |
| max_length | int | 200 |  |
| number_min | int | 0 |  |
| number_max | int | 0 |  |
| number_step | int | 1 |  |
| icon | string | '' |  |
| autocomplete_off | bool | false |  |
| tip | string | '' | Displays a tip by the label. |
| ext_tip | string | '' | Displays a tip at the bottom of the input. |
| append_button | bool | false |  |
| append_value | string | '' |  |
| append_form_value | string | '' |  |
| append_size | string | '' |  |
| append_class | string | btn-default |  |
| append_type | string | submit |  |
| append_id | string | p-{input_id}-append |  |
| append_button_name | string | p-submit-{input_id}-append |  |
| append_button_id | string | {input_id}-append-btn |  |
| prepend_button | bool | false |  |
| prepend_value | string | '' |  |
| prepend_form_value | string | '' |  |
| prepend_size | string | '' |  |
| prepend_class | string | btn-default |  |
| prepend_type | string | submit |  |
| prepend_id | string | p-{input_id}-prepend |  |
| prepend_button_name | string | p-submit-{input_id}-prepend |  |
| prepend_button_id | string | {input_id}-prepend-btn |  |
| error_text | string | '' |  |
| delimiter | string | , |  |
| stacked | string | '' |  |
| group_size | string | '' | Possible value: sm, md, lg |
| password_strength | bool | false |  |
| data | array | [] |  |
| append_html | string | '' |  |
| censor_words | bool | true |  |
| password_toggle | bool | true |  |
| descript | bool | true |  |

## Return Values

(string)

## Examples

```php
echo form_text('text_field', 'Text Field');
```
