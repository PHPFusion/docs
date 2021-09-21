# opencollapsebody()

Create collapsing panel.

---

opencollapsebody( string $title, string $unique_id, string $grouping_id [, bool $active, string $class ] ) : string

## Parameters

$title (string) (Required) Panel title.

$unique_id (string) (Required) Panel ID.

$grouping_id (string) (Required) Parent's accordion ID.

$active (bool) (Optional) Panel state. Default value: false

$class (string) (Optional) Panel CSS class. Default value: ''

## Return Values

(string)

## Examples

```php
$collapse_id = 'test-group';
echo opencollapse($collapse_id);

echo opencollapsebody('Test 1', 'panel1', $collapse_id);
echo 'Content goes here';
echo closecollapsebody();

echo opencollapsebody('Test 2', 'panel2', $collapse_id, true); // this panel will be open
echo 'Content goes here';
echo closecollapsebody();

echo closecollapse();
```
