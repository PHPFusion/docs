# add_to_jquery()

Add javascript source code to the output. Code will be placed in footer and will be minified.

---

add_to_jquery( string $code ) : void

## Parameters

$code (string) (Required) JS code.

## Return Values

No value is returned.

## Examples

```php
// you can call directly jquery code or add any javascript
add_to_jquery('
$(".block").removeClass(".p-0");

function jsfunction() {
    //
}
');
```
