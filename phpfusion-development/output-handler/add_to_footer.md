# add_to_footer()

Add content to the footer. This function adds the code directly before the `</body>` tag.

---

add_to_footer( string $tag ) : void

## Parameters

$tag (string) (Required) HTML tag.

## Return Values

No value is returned.

## Examples

```php
add_to_footer('<script src="path/to/file.js"></script>');
```
