# handle_output()

Execute the output handlers.

---

handle_output( string $output ) : string

## Parameters

$output (string) (Required) Page output.

## Return Values

(string)

## Examples

```php
$output = 'page output...';

handle_output($output);
```

<div class="alert alert-info">
he function is called in footer.php as the last step before sending the output to the client.
</div>
