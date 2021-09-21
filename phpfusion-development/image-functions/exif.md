# exif()

Get information about a specific image.

---

exif( string $image_path ) : mixed

## Parameters

$image_path (string) (Required) Path to the image.

## Return Values

(array|bool) False, if the image does not exist.

## Examples

```php
require_once INCLUDES.'photo_functions_include.php';

$image_path = IMAGES.'phpfusion-icon.png';

exif($image_path);
/*
Array
(
    [width] => 295
    [height] => 99
    [mime] => image/png
    [channels] =>
    [bits] => 8
    [make] => No information available
    [model] => No information available
    [exposure] => No information available
    [aperture] => No information available
    [date] => No information available
    [iso] => No information available
)
*/
```
