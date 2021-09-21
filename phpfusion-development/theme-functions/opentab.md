# opentab()

Create tabs.

---

opentab( array $tab, string $link_active_arrkey, string $id [, bool $link, string $class, string $getname, array $cleanup_GET, bool $remember ] ) : string

## Parameters

$tab (array) (Required) Multidimension array consisting of keys title, id, icon.

$link_active_arrkey (string) (Required) tab_active() function or the `$_GET` request to match the $tab['id'].

$id (string) (Required) Unique ID.

$link (bool) (Optional) False for jquery, true for php (will reload page). Default value: false

$class (string) (Optional) CSS class for the nav. Default value: ''

$getname (string) (Optional) Set getname and turn tabs into the link that listens to getname. Default value: section

$cleanup_GET (array) (Optional) The request key that needs to be deleted. Default value: []

$remember (bool) (Optional) Set to true to automatically remember tab using cookie. Default value: false

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
