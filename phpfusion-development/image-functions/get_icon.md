# get_icon()

Get the icon or `<i>` tag.

---

function get_icon(string $icon, string $class = "", string $tooltip = "") :string 

## Parameters

$icon (string) (Required) The name of the icon 

$class (string) (Optional) Additional class to be inserted into the i tag. Default value: ''

$tooltip (string) (Optional) The title of the icon. Default value: ''

## Return Values

(string) The glyph font icon contained `<i>` tag.

## Examples

```php
echo get_icon('search');
//<i class="fas fa-search"></i>
```

### Names of Icons in PHPFusion
This list is extensive but not exhaustive as it can be added with any names with set_icon() function.

TBA

