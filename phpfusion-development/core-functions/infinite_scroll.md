# infinite_scroll()

Infinite scroll pagination.

---

infinite_scroll( string $scroll_url, int $rowstart, int $count [, string $getname, string $http_query ] ) : string

## Parameters

$scroll_url (string) (Required) The ajax script that loads the content.

$rowstart (int) (Required) The number of the first listed item.

$count (int) (Required) The number of entries displayed on one page.

$getname (string) (Optional) The name of the `$_GET` parameter that contains the start number. Default value: rowstart

$http_query (string) (Optional) Additional http query. Default value: ''

## Return Values

(string) Infinite scroll.

## Examples

```php
$total_rows = dbcount("(download_id)", DB_DOWNLOADS);
$rowstart = isset($_GET['rowstart']) && isnum($_GET['rowstart']) && ($_GET['rowstart'] <= $total_rows) ? $_GET['rowstart'] : 0;

echo infinite_scroll(BASEDIR.'scroll.php', $rowstart, $total_rows);
```

**scroll.php**

```php
<?php
require_once __DIR__.'/maincore.php';

$limit = 15;
$rowstart = isset($_GET['rowstart']) ? $_GET['rowstart'] : 0;

$result = dbquery("SELECT *
    FROM ".DB_DOWNLOADS."
    ORDER BY download_datestamp DESC LIMIT $rowstart, $limit
");

while ($data = dbarray($result)) {
    //
}
```
