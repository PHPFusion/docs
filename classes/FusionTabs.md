# [PHPFusion Docs](../home.md)

# Class: \FusionTabs
### Namespace: [\](../namespaces/default.md)
---
---
### Constants
* No constants found
---
### Properties
* [private $remember](../classes/FusionTabs.md#property_remember)
* [private $cookie_prefix](../classes/FusionTabs.md#property_cookie_prefix)
* [private $cookie_name](../classes/FusionTabs.md#property_cookie_name)
* [private $link_mode](../classes/FusionTabs.md#property_link_mode)
---
### Methods
* [public tabActive()](../classes/FusionTabs.md#method_tabActive)
* [public tabIndex()](../classes/FusionTabs.md#method_tabIndex)
* [public setRemember()](../classes/FusionTabs.md#method_setRemember)
* [public openTab()](../classes/FusionTabs.md#method_openTab)
* [public openTabBody()](../classes/FusionTabs.md#method_openTabBody)
* [public closeTabBody()](../classes/FusionTabs.md#method_closeTabBody)
* [public closeTab()](../classes/FusionTabs.md#method_closeTab)
---
### Details
* File: [theme_functions_include.php](../files/theme_functions_include.md)
* Package: Default
* Class Hierarchy:
  * \FusionTabs
---
## Properties
<a name="property_remember"></a>
#### private $remember : 
---
**Type:** 

**Details:**


<a name="property_cookie_prefix"></a>
#### private $cookie_prefix : 
---
**Type:** 

**Details:**


<a name="property_cookie_name"></a>
#### private $cookie_name : 
---
**Type:** 

**Details:**


<a name="property_link_mode"></a>
#### private $link_mode : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_tabActive" class="anchor"></a>
#### public tabActive() : string

```
Static public tabActive(array  $array, integer  $default_active, string  $getname = NULL) : string
```

**Summary**

Current active tab selector.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  | Multidimension array consisting of keys title, id, icon. |
| <code>integer</code> | $default_active  | 0 if link_mode is false, $_GET if link_mode is true. |
| <code>string</code> | $getname  | Set getname and turn tabs into link that listens to getname. |

**Returns:** string


<a name="method_tabIndex" class="anchor"></a>
#### public tabIndex() : integer

```
Static public tabIndex(array  $array, string  $default_active, boolean  $getname = FALSE) : integer
```

**Summary**

Get current active tab index

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |
| <code>string</code> | $default_active  |  |
| <code>boolean</code> | $getname  |  |

**Returns:** integer


<a name="method_setRemember" class="anchor"></a>
#### public setRemember() 

```
public setRemember(boolean  $value) 
```

**Summary**

Automatically remember tab using cookie.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $value  |  |




<a name="method_openTab" class="anchor"></a>
#### public openTab() : string

```
public openTab(array  $tab_title, string  $link_active_arrkey, string  $id, boolean  $link = FALSE, string  $class = FALSE, string  $getname = &#039;section&#039;, array  $cleanup_get = array()) : string
```

**Summary**

Render tab links.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $tab_title  | Multidimension array consisting of keys title, id, icon. |
| <code>string</code> | $link_active_arrkey  | tab_active() function or the $_GET request to match the $tabs['id']. |
| <code>string</code> | $id  | Unique ID. |
| <code>boolean</code> | $link  | False for jquery, true for php (will reload page). |
| <code>string</code> | $class  | CSS class for the nav. |
| <code>string</code> | $getname  | Set getname and turn tabs into the link that listens to getname. |
| <code>array</code> | $cleanup_get  | The request key that needs to be deleted.

Example:
$tabs['title'][] = "Tab 1";
$tabs['id'][] = "tab1";
$tabs['title'][] = "Tab 2";
$tabs['id'][] = "tab2";
$tab_active = tab_active($tabs, 0);

Jquery:
echo opentab($tabs, $tab_active, 'myTab', FALSE, 'nav-pills', 'ref', ['action', 'subaction']);

PHP:
echo opentab($tabs, $_GET['ref'], 'myTab', TRUE, 'nav-pills', 'ref', ['action', 'subaction']);
echo opentab($tabs, $_GET['ref'], 'myTab', TRUE, 'nav-pills', 'ref', ['*']); // clear all |

**Returns:** string


<a name="method_openTabBody" class="anchor"></a>
#### public openTabBody() : string

```
public openTabBody(string  $id, string  $link_active_arrkey = NULL, string  $key = &#039;section&#039;) : string
```

**Summary**

Creates tab body.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  | Tab id from $tabs['id']. |
| <code>string</code> | $link_active_arrkey  | tab_active() function or the $_GET request to match the $tabd['id']. |
| <code>string</code> | $key  | Set getname and turn tabs into link that listens to getname. |

**Returns:** string


<a name="method_closeTabBody" class="anchor"></a>
#### public closeTabBody() : string

```
public closeTabBody() : string
```

**Summary**

Close tab body.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)

**Returns:** string


<a name="method_closeTab" class="anchor"></a>
#### public closeTab() : string

```
public closeTab(array  $options = array()) : string
```

**Summary**

Close tab.

**Details:**
* Inherited From: [\FusionTabs](../classes/FusionTabs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $options  |  |

**Returns:** string



---

### Top Namespaces

* [\Defender](../namespaces/Defender.html.md)
* [\PHPFusion](../namespaces/PHPFusion.html.md)

---

### Reports
* [Errors - 1023](../reports/errors.md)
* [Markers - 6](../reports/markers.md)
* [Deprecated - 36](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2021-07-21 using [phpDocumentor](http://www.phpdoc.org/) and [fr3nch13/phpdoc-markdown](https://github.com/fr3nch13/phpdoc-markdown)
