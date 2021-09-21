# stripfilename()

Strips a given filename from any unwanted characters and symbols.

---

stripfilename( string $filename ) : string

## Parameters

$filename (string) (Required) Filename you want to strip. Remember to remove the file extension before parsing it through this function.

## Return Values

(string) The filename stripped and ready for use.

## Examples

```php
$filename = 'I am-Ã… test file!!!??.jpg';

// File name without file extension
$filename = preg_replace('/\\.[^.\\s]{3,4}$/', '', $filename);

echo stripfilename($filename);

// i_am-_test_file
```
