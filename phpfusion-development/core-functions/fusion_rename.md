# fusion_rename()

Alternative to rename() that works on Windows.

---

fusion_rename( string $origin, string $target ) : void

## Parameters

$origin (string) (Required) The old name.

$target (string) (Required) The new name.

## Return Values

No value is returned.

## Examples

```php
fusion_rename(IMAGES.'articles/'.$file, IMAGES_A.$file)
```
