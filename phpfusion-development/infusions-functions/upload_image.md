# upload_image()

Image uploading.

---

upload_image( string $source_image, string $target_name, string $target_folder [, int $target_width, int $target_height, int $max_size, bool $delete_original, bool $thumb1, bool $thumb2, int $thumb1_ratio, string $thumb1_folder, string $thumb1_suffix, int $thumb1_width, int $thumb1_height, int $thumb2_ratio, string $thumb2_folder, string $thumb2_suffix, int $thumb2_width, int $thumb2_height, string $query, array $allowed_extensions, bool $replace_upload ] ) : array

## Parameters

$source_image (string) (Required) Key for the uploaded file in the `$_FILES` array.

$target_name (string) (Required) Name of the uploaded image, leave this blank to use the original image name.

$target_folder (string) (Required) The folder you are uploading the image to.

$target_width (int) (Optional) Maximum allowed width of image in pixels. Default value: 1800

$target_height (int) (Optional) Maximum allowed height of image in pixels. Default value: 1600

$max_size (int) (Optional) Max size of image in bytes. Default value: 150000

$delete_original (bool) (Optional) Set this to true if you wish the original image to be deleted after upload. Default value: false

$thumb1 (bool) (Optional) Set this to true if you wish to generate a thumbnail number 1. Default value: true

$thumb2 (bool) (Optional) Set this to true if you wish to generate a thumbnail number 2. Default value: true

$thumb1_ratio (int) (Optional) Image ratio for the first thumbnail. 0 means original image ratio, 1 means square image ratio. Default value: 0

$thumb1_folder (string) (Optional) Folder for the first thumbnail. Default value: IMAGES

$thumb1_suffix (string) (Optional) Text which will be appended at the end of the image name of the first thumbnail. Default value: `_t1`

$thumb1_width (int) (Optional) Width of first thumbnail in pixels. Default value: 100

$thumb1_height (int) (Optional) Height of first thumbnail in pixels. Default value: 100

$thumb2_ratio (int) (Optional) Image ratio for the second thumbnail. 0 means original image ratio, 1 means square image ratio. Default value: 0

$thumb2_folder (string) (Optional) Folder for the second thumbnail. Default value: IMAGES

$thumb2_suffix (string) (Optional) Text which will be appended at the end of the image name of the second thumbnail. Default value: `_t2`

$thumb2_width (int) (Optional) Width of second thumbnail in pixels. Default value: 400

$thumb2_height (int) (Optional) Height of first thumbnail in pixels. Default value: 300

$query (string) (Optional) DB Query when the image is uploaded. Default value: ''

$allowed_extensions (array) (Optional) Allowed image extensions. Default value: ['.jpg', '.jpeg', '.png', '.png', '.svg', '.gif', '.bmp']

$replace_upload (bool) (Optional) Replace image if exists in the target folder. Default value: false

## Return Values

(array) Array with information about the upload.

## Examples

```php
upload_image('test.png', 'test.png', IMAGES);
```
