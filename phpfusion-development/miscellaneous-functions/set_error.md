# set_error()

Saves the error to the database.

---

set_error( int $error_level, string $error_message, string $error_file, int $error_line ) : void

## Parameters

$error_level (int) (Required) Severity

$error_message (string) (Required) $e->message

$error_file (string) (Required) The file in question, run a debug_backtrace()[2] in the file

$error_line (string) (Required) The line in question, run a debug_backtrace()[2] in the file

## Return Values

No value is returned.

## Examples

```php
set_error(2, 'Error message', debug_backtrace()[1]['file'], debug_backtrace()[1]['line']);
```

<div class="alert alert-info">
1 = E_ERROR, 2 = E_WARNING, 4 = E_PARSE, 8 = E_NOTICE, 16 = E_CORE_ERROR, 32 = E_CORE_WARNING = 32, 64 = E_COMPILE_ERROR, 128 = E_COMPILE_WARNING, 256 = E_USER_ERROR, 512 = E_USER_WARNING, 1024 = E_USER_NOTICE, 2047 = E_ALL, 2048 = E_STRICT
</div>
