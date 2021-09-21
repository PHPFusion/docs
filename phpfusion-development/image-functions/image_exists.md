# image_exists()

Find another available image name based on the image in the folder.

---

image_exists( string $dir, string $image ) : string

## Parameters

$dir (string) (Required) The directory to check for the image, remember a / at the end of the directory path.

$image (string) (Required) The image inside the directory you want to check for.

## Return Values

(string)

## Examples

```php
require_once INCLUDES.'photo_functions_include.php';

echo image_exists(IMAGES, 'phpfusion-icon.png');
// phpfusion-icon_1.png
```
