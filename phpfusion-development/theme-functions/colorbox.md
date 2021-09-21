# colorbox()

Display image in colorbox.

---

colorbox( string $img_path, string $img_title [, bool $responsive, string $class, bool $as_text ] ) : string

## Parameters

$img_path (string) (Required) The path to image.

$img_title (string) (Required) Image title.

$responsive (bool) (Optional) Add img-responsive class. Default value: true

$class (string) (Optional) CSS class. Default value: ''

$as_text (bool) (Optional) Show clickable text instead image. Default value: false

## Return Values

(string)

## Examples

```php
echo colorbox(IMAGES.'phpfusion-icon.png', 'Logo');
```
