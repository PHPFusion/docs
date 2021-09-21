# thumbnail()

Show image thumbnail.

---

thumbnail( string $src, string $size [, bool $url, bool $colorbox, bool $responsive, string $class ] ) : string

## Parameters

$src (string) (Required) The path to image.

$size (string) (Required) Image size.

$url (bool) (Optional) Make image clickable. Default value: false

$colorbox (bool) (Optional) Allow colorbox(). Default value: false

$responsive (bool) (Optional) Add img-responsive class. Default value: true

$class (string) (Optional) CSS class. Default value: ''

## Return Values

(string)

## Examples

```php
echo thumbnail(IMAGES.'phpfusion-icon.png', '100px');
```
