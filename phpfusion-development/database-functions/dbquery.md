# dbquery()

Send a database query.

---

dbquery( string $query [, array $parameters ] ) : mixed

## Parameters

$query (string) (Required) A SQL query,

$parameters (array) (Optional) Parameter identifier. The statement template can contain zero or more named (:name) or question mark (?) parameter markers for which real values will be substituted when the statement is executed. Default value: []

## Return Values

(string|bool) The result of query or false on error.

## Examples

```php
$result = dbquery("SELECT * FROM ".DB_TABLE." WHERE 1=1");

// with parameters
$result = dbquery("SELECT * FROM ".DB_TABLE." WHERE field=:name", [
    ':name' => 'value'
]);
```
