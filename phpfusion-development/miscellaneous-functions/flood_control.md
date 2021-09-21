# flood_control()

With this function you are able to prevent users from flooding the system, typical spambots and others. This function should be used whenever users have the ability to post to the database.

---

flood_control( string $field, string $table, string $where [, bool $debug ] ) : bool

## Parameters

$field (string) (Required) The field in the table which holds the Unix timestamp. It is important that this is a Unix timestamp and not some other kind of timestamp!

$table (string) (Required) The table you are flood controlling and where the UNIX timestamp field is located in.

$where (string ) (Required) The where statement to select the right rows and the right timestamp.

$debug (bool) (Optional) Default value: false

## Return Values

(string)

## Examples

```php
require_once INCLUDES.'flood_include.php';

if (!flood_control('comment_datestamp', DB_COMMENTS, "comment_ip='".USER_IP."'")) {
    $result = dbquery("INSERT INTO ".DB_COMMENTS."
        (comment_item_id, comment_type, comment_name, comment_message, comment_datestamp, comment_ip) VALUES
        ('$cid', '$ctype', '$comment_name', '$comment_message', '".time()."', '".USER_IP."'
     )");
}
```
