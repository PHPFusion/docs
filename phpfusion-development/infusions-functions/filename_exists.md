# filename_exists()

Checks if the file exists inside the folder. If not it will create a unique name for the file.

---

filename_exists( sting $directory [, string $file, array $options ] ) : string

## Parameters

$directory (string) (Required) The directory to check for the image.

$file (string) (Optional) The file in the directory you want to check.

$options (string) (Optional) dateformat - d,m,y, php date format constant, hash - false to remove hash string

## Return Values

(string) New unique filepath.

## Examples

```php
$file = filename_exists(IMAGES, 'test.png');
// do someting with file... (upload, copy etc.)
```
