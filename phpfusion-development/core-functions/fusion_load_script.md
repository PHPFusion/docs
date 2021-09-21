# fusion_load_script()

Cached script loader. This function will cache the path that has been added and avoid duplicates.

---

fusion_load_script( string $file_path [, string $file_type, bool $html, bool $cached ] ) : string

## Parameters

$file_path (string) (Required) The source file.

$file_type (string) (Optional) Possible value: script, css. Default value: script

$html (bool) (Optional) Return as html tags instead add to output handler. Default value: false

$cached (bool) (Optional) False to invalidate browser's cache. Default value: true

## Return Values

(string)

## Examples

```php
//By default, it automatically adds html to the header

fusion_load_script(BASEDIR.'path/to/file.js');
// <script src='path/to/file.js?v=657588474'></script>

fusion_load_script(BASEDIR.'path/to/file.js', 'css');
// <link rel='stylesheet' href='path/to/file.css?v=7855858585' media='all'>
```
