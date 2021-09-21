# parse_image_dir()

Parse and force image/ to own directory.

---

parse_image_dir( string $data [, string $prefix_ ] ) : string

## Parameters

$data (string) (Required) String to parse.

$prefix_ (string) (Optional) Image folder. Default value: ''

## Return Values

(string) Parsed string.

## Examples

```php
$data = 'Text <img src="images/img.png" alt="img">';

echo parse_image_dir($data, IMAGES_N);
// Text <img src="infusions/news/images/img.png" alt="img">
```
