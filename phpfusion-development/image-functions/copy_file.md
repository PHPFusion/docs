# copy_file()

Copy a file from any source to any destination.

---

copy_file( string $source, string $destination ) : mixed

## Parameters

$source (string) (Required) Copy file from URL

$destination (string) (Required) Destination folder.

## Return Values

(mixed)

## Examples

```php
require_once INCLUDES.'photo_functions_include.php';

copy_file(IMAGES.'phpfusion-icon.png', IMAGES.'avatars/');
```
