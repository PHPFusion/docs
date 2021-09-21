# tab_active()

Current active tab selector.

---

tab_active( array $array, int $default_active [, string $getname ] ) : string

## Parameters

$array (array) (Required) Multidimension array consisting of keys title, id, icon.

$default_active (int) (Required) 0 if link_mode is false, `$_GET` if link_mode is true.

$getname (string) (Optional) Set getname and turn tabs into link that listens to getname. Default value: null

## Return Values

(string)

## Examples

```php
$tab['title'][] = 'Tab 1';
$tab['id'][] = 'tab1';
$tab['icon'][] = 'fa fa-cog';

$tab['title'][] = 'Tab 2';
$tab['id'][] = 'tab2';
$tab['icon'][] = 'fa fa-folder';

$tab_active = tab_active($tab, 0);

echo opentab($tab, $tab_active, 'testtab');

echo opentabbody($tab['title'][0], 'tab1', $tab_active);
echo 'Tab 1 content goes here';
echo closetabbody();

echo opentabbody($tab['title'][1], 'tab2', $tab_active);
echo 'Tab 2 content goes here';
echo closetabbody();

echo closetab();
```
