# upload_file()

File uploading.

---

upload_file( string $source_file, string $target_file, string $target_folder [, string $valid_ext, int $max_size, string $query, bool $replace_upload ] ) : array

## Parameters

$source_file (string) (Required) The key of the `$_FILE` which holds the uploaded file.

$target_file (string) (Required) Name for the uploaded file, leave this blank to use the uploaded file's name.

$target_folder (string) (Required) Folder the uploaded file will be moved to.

$valid_ext (string) (Optional) Valid file extensions for uploaded files. Default value: .zip,.rar,.tar,.bz2,.7z

$max_size (int) (Optional) Maximum allowed file size. Default value: 15000

$query (string) (Optional) DB Query when the file is uploaded. Default value: ''

$replace_upload (bool) (Optional) Replace the file if exists in the target folder. Default Value: false

## Return Values

(array) Array with information about the upload.

## Examples

```php
upload_file('test.zip', 'test.zip', DOWNLOADS);
```
