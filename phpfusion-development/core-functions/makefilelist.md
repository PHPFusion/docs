# makefilelist()

Create a list of files or folders and store them in an array.

---

makefilelist( string $folder [, string $filter, bool $sort, string $type, string $ext_filter ] ) : array

## Parameters

$folder (string) (Required) Path to folder.

$filter (string) (Optional) The names of the filtered folders and files separated by |, false to use default filter. Default value: ''

$sort (bool) (Optional) False if you don't want to sort the result. Default value: true

$type (string) (Optional) Possible value: files, folders. Default value: files

$ext_filter (string) (Optional) File extensions separated by |, only when $type is 'files'. Default value: ''

## Return Values

(array) Array of all items.

## Examples

```php
$infusions = makefilelist(INFUSIONS, FALSE, TRUE, 'folders');

foreach ($infusions as $folder) {
    //
}
```
