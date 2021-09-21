# alert()

Creates an alert bar.

---

alert( string $title [, array $options ] ) : string

## Parameters

$title (string) (Required) Text inside the alert.

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| class | string | alert-danger | CSS class. |
| dismiss | bool | false | Enable dismissal of an alert. |

## Return Values

(string)

## Examples

```php
echo alert('This is a danger alert!');
// <div class='alert alert-danger'>This is a danger alert!</div>
```
