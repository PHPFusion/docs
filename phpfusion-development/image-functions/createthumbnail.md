# createthumbnail()

Create a thumbnail from an already uploaded image.

---

createthumbnail( int $filetype, string $origfile, string $thumbfile, int $new_w, int $new_h ) : void

## Parameters

$filetype (int) (Required) Possible value: 1 - .gif, 2 -  .jpg, 3 - .png, 4 - .webp

$origfile (string) (Required) The full path to the original file from which you want to create a thumbnail.

$thumbfile (string) (Required) The full path to the thumbnail file you want to create.

$new_w (int) (Required) Maximum width for thumbnail image.

$new_h (int) (Required) Maximum height for thumbnail image.

## Return Values

No value is returned.

## Examples

```php
require_once INCLUDES.'photo_functions_include.php';

$origfile = IMAGES.'phpfusion-icon.png';
$thumbfile = IMAGES.'phpfusion-icon_thumb.png';

createthumbnail(3, $origfile, $thumbfile, 100, 100);
```
