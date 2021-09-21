# dbquery_insert()

MYSQL Row modifiers. Insert/Update/Delete.

---

dbquery_insert( string $table, array $inputdata, string $mode [, array $options ] ) : mixed

## Parameters

$table (string) (Required) Table name.

$inputdata (array) (Required)

$mode (string) (Required) Possible value: save, update, delete

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| debug | bool | false | If true, do nothing, just show the SQL. |
| primary_key | string | '' | Name of primary key column. If it is empty, column will detected automatically. |
| no_unique | bool | false | If true, primary key column will be not removed from $inputdata. |
| keep_session | bool | false | If true, defender will not unset field sessions. |

## Return Values

(int|false) If an error happens, it returns false. Otherwise, if $mode is `save`, and the primary key column is incremented automatically, this function returns the last inserted id. In other cases it always returns 0.

## Examples

```php
$inputdata = [
    'settings_name'  => 'option',
    'settings_value' => 2,
    'settings_inf'   => 'downloads'
];

dbquery_insert(DB_SETTINGS_INF, $inputdata, 'update');
```
