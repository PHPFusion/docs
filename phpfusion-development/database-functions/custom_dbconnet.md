# custom_dbconnet()

Connect to the another database.

---

custom_dbconnet( string $db_host, string $db_user, string $db_pass, string $db_name int $db_port, string $dbid ) : AbstractDatabaseDriver

## Parameters

$db_host (string) (Required) The MySQL server.

$db_user (string) (Required) The username.

$db_pass (string) (Required) The password.

$db_name (string) (Required) The name of the database that is to be selected.

$db_port (int) (Required) The TCP/IP port on which the MySQL server is listening.

$dbid (string) (Required) Any string or name.

## Return Values

(AbstractDatabaseDriver)

## Examples

```php
$connect = custom_dbconnet($db2_host, $db2_user, $db2_pass, $db2_name, 'customdb');
$result = $connect->query("...");

while ($data = dbarray($result)) {
    //
}
```
