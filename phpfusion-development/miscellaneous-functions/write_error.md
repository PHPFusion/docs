# write_error()

Write error to file.

---

write_error( string $error_message, string $error_file, int $error_line ) : void

## Parameters

$error_message (string) (Required) $e->message

$error_file (string) (Required) The file in question, run a debug_backtrace()[2] in the file

$error_line (string) (Required) The line in question, run a debug_backtrace()[2] in the file

## Return Values

No value is returned.

## Examples

```php
write_error('Error message', debug_backtrace()[1]['file'], debug_backtrace()[1]['line']);
```
