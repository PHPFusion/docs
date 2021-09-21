# dbconnect()

Connect to the database.

---

dbconnect( string $db_host, string $db_user, string $db_pass, string $db_name [, int $db_port, bool $halt_on_error ] ) : array

## Parameters

$db_host (string) (Required) The MySQL server.

$db_user (string) (Required) The username.

$db_pass (string) (Required) The password.

$db_name (string) (Required) The name of the database that is to be selected.

$db_port (int) (Optional) The TCP/IP port on which the MySQL server is listening. Default value: 3306

$halt_on_error (bool) (Optional) If it is true, the script will halt in case of error. Default value: false

## Return Values

(array) Returns a MySQL link identifier on success, or "Unable to establish connection to MySQL" on failure.

## Examples

```php
// Establish mySQL database connection
// The variables are stored in the config.php file
dbconnect($db_host, $db_user, $db_pass, $db_name);
```
