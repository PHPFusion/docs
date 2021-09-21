# add_handler()

Add a new output handler function.

---

add_handler( callback $callback ) : void

## Parameters

$callback (callback) (Required) The name of a function or other callable object

## Return Values

No value is returned.

## Examples

```php
add_handler(function ($output = '') {
    return preg_replace("/<meta name='theme-color' content='#ffffff'>/i", '<meta name="theme-color" content="#000.">', $output);
});
```
