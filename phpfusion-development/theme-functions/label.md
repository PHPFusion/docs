# label()

Creates label.

---

label( string $label [, array $options ] ) : string

## Parameters

$label (string) (Required) Text inside the label.

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| class | string | label-default | CSS class. |
| icon | string | '' | Icon CSS class. Eg. fa fa-beer. |

## Return Values

(string)

## Examples

```php
echo label('Default');
// <span class='label label-default'>Default</span>
```
