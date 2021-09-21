# opentabbody()

Creates tab body.

---

opentabbody( string $tab, string $tab_id [, string $link_active_arrkey, bool $link, string $key ] ) : string

## Parameters

$tab (string) (Required) Deprecated, for compatibility only.

$tab_id (string) (Required) Tab id from $tab['id'].

$link_active_arrkey (string) (Required) tab_active() function or the `$_GET` request to match the $tab['id'].

$link (bool) (Optional) Deprecated, for compatibility only. False for jquery, true for php (will reload page). Default value: false

$key (string) (Optional) Set getname and turn tabs into link that listens to getname. Default value: section

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
