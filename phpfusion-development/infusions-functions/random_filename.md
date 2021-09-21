# random_filename()

Generate random filename. Protect filename from uploader by renaming file.

---

random_filename( string $filename ) : string

## Parameters

$filename (string) (Required) The filename.

## Return Values

(string)

## Examples

```php
echo random_filename('test.png');
// a3e90115.png
```
