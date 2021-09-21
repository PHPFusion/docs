# openform()

The function should be able used to replace conventional `<form>` tags to
provide an enhanced feature to your application.

---

openform( string $form_name, string $method [, string $action_url, array $options ] ) : string

## Parameters

$form_name (string) (Required) Form ID.

$method (string) (Required) Possible value: post, get.

$action_url (string) (Optional) Form current uri. Default value: FORM_REQUEST

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| form_id | string | $form_name |  |
| class | string | '' | CSS class properties. |
| enctype | bool | false | Set true for allowing multipart. |
| max_tokens | int | $settings['form_tokens'] |  |
| inline | bool | false | Set true for making form inline. |
| on_submit | string | '' | Adds javascript function on form submit. |
| honeypot | bool | true | Enables honeypots to counter botting. |

## Return Values

(string)

## Examples

```php
echo openform('testform', 'post');
//
echo closeform();
```
