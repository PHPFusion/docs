# badge()

Creates badge.

---

badge( string $label [, array $options ] ) : string

## Parameters

$label (string) (Required) Text inside the label.

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| class | string | '' | CSS class. |
| icon | string | '' | Icon CSS class. Eg. fa fa-beer. |

## Return Values

(string)

## Examples

```php
echo badge('Badge');
// <span class='badge'>Badge</span>
```
