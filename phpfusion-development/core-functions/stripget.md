# stripget()

Prevent any possible XSS attacks via `$_GET`.

---

stripget( string $check_url ) : bool

## Parameters

$check_url (array|string) (Required) String or array to be stripped.

## Return Values

(bool) True if the URL is not secure.

## Examples

```php
if (stripget($_GET)) {
    //
}
```

<div class="alert alert-info">
This function is used in maincore.php so basically there is no need to call this function manually.
</div>
