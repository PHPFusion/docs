# multilang_column()

Multilang column.

---

multilang_column( string $column ) : string

## Parameters

$column (string) (Required)

## Return Values

(string)

## Examples

```php
$result = dbquery("
    SELECT * FROM ".DB_NEWS."
    WHERE ".multilang_column('news_subject')." = '".$data['news_subject']."'
");
```
