# get_image()

Get the imagepath or `<img>` tag.

---

get_image( string $image [, string $alt, string $style, string $title, string $atts ] ) : string

## Parameters

$image (string) (Required) The name of the image. Default system images: up, down, imagenotfound, left, right, noavatar, panel_on, panel_off

$alt (string) (Optional) The alt attribute of the image. Default value: ''

$style (string) (Optional) The style attribute of the image. Default value: ''

$title (string) (Optional) The title attribute of the image. Default value: ''

$atts (string) (Optional) Custom attributes of the image. Default value: ''

## Return Values

(string) The path of the image if the first argument is given, but others not. Otherwise, `<img>` tag.

## Examples

```php
echo get_image('noavatar');
// images/avatars/no-avatar.jpg
```
