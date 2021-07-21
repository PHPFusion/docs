# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Panels
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
---
### Constants
* [ PANEL_LEFT](../classes/PHPFusion.Panels.md#constant_PANEL_LEFT)
* [ PANEL_U_CENTER](../classes/PHPFusion.Panels.md#constant_PANEL_U_CENTER)
* [ PANEL_L_CENTER](../classes/PHPFusion.Panels.md#constant_PANEL_L_CENTER)
* [ PANEL_RIGHT](../classes/PHPFusion.Panels.md#constant_PANEL_RIGHT)
* [ PANEL_AU_CENTER](../classes/PHPFusion.Panels.md#constant_PANEL_AU_CENTER)
* [ PANEL_BL_CENTER](../classes/PHPFusion.Panels.md#constant_PANEL_BL_CENTER)
* [ PANEL_USER1](../classes/PHPFusion.Panels.md#constant_PANEL_USER1)
* [ PANEL_USER2](../classes/PHPFusion.Panels.md#constant_PANEL_USER2)
* [ PANEL_USER3](../classes/PHPFusion.Panels.md#constant_PANEL_USER3)
* [ PANEL_USER4](../classes/PHPFusion.Panels.md#constant_PANEL_USER4)
---
### Properties
* [private $panel_instance](../classes/PHPFusion.Panels.md#property_panel_instance)
* [private $panel_name](../classes/PHPFusion.Panels.md#property_panel_name)
* [private $panel_excluded](../classes/PHPFusion.Panels.md#property_panel_excluded)
* [private $panels_cache](../classes/PHPFusion.Panels.md#property_panels_cache)
* [private $available_panels](../classes/PHPFusion.Panels.md#property_available_panels)
* [private $hide_all](../classes/PHPFusion.Panels.md#property_hide_all)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Panels.md#method_getInstance)
* [public cachePanels()](../classes/PHPFusion.Panels.md#method_cachePanels)
* [public addPanel()](../classes/PHPFusion.Panels.md#method_addPanel)
* [public displayPanel()](../classes/PHPFusion.Panels.md#method_displayPanel)
* [public getPanelExcluded()](../classes/PHPFusion.Panels.md#method_getPanelExcluded)
* [public getAvailablePanels()](../classes/PHPFusion.Panels.md#method_getAvailablePanels)
* [public hidePanel()](../classes/PHPFusion.Panels.md#method_hidePanel)
* [public hideAll()](../classes/PHPFusion.Panels.md#method_hideAll)
* [public getSitePanel()](../classes/PHPFusion.Panels.md#method_getSitePanel)
* [public checkPanelStatus()](../classes/PHPFusion.Panels.md#method_checkPanelStatus)
* [public hide_panel()](../classes/PHPFusion.Panels.md#method_hide_panel) - (deprecated)
* [private wildcardMatch()](../classes/PHPFusion.Panels.md#method_wildcardMatch)
---
### Details
* File: [classes\PHPFusion\Panels.php](../files/classes.PHPFusion.Panels.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\Panels
---
## Constants
<a name="constant_PANEL_LEFT" class="anchor"></a>
###### PANEL_LEFT
```
PANEL_LEFT = 1
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_U_CENTER" class="anchor"></a>
###### PANEL_U_CENTER
```
PANEL_U_CENTER = 2
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_L_CENTER" class="anchor"></a>
###### PANEL_L_CENTER
```
PANEL_L_CENTER = 3
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_RIGHT" class="anchor"></a>
###### PANEL_RIGHT
```
PANEL_RIGHT = 4
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_AU_CENTER" class="anchor"></a>
###### PANEL_AU_CENTER
```
PANEL_AU_CENTER = 5
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_BL_CENTER" class="anchor"></a>
###### PANEL_BL_CENTER
```
PANEL_BL_CENTER = 6
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_USER1" class="anchor"></a>
###### PANEL_USER1
```
PANEL_USER1 = 7
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_USER2" class="anchor"></a>
###### PANEL_USER2
```
PANEL_USER2 = 8
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_USER3" class="anchor"></a>
###### PANEL_USER3
```
PANEL_USER3 = 9
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PANEL_USER4" class="anchor"></a>
###### PANEL_USER4
```
PANEL_USER4 = 10
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_panel_instance"></a>
#### private $panel_instance : 
---
**Type:** 

**Details:**


<a name="property_panel_name"></a>
#### private $panel_name : 
---
**Type:** 

**Details:**


<a name="property_panel_excluded"></a>
#### private $panel_excluded : 
---
**Type:** 

**Details:**


<a name="property_panels_cache"></a>
#### private $panels_cache : 
---
**Type:** 

**Details:**


<a name="property_available_panels"></a>
#### private $available_panels : 
---
**Type:** 

**Details:**


<a name="property_hide_all"></a>
#### private $hide_all : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : \PHPFusion\Panels&amp;#124;null

```
Static public getInstance(boolean  $set_info = TRUE) : \PHPFusion\Panels&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $set_info  |  |

**Returns:** <a href="../classes/PHPFusion.Panels.html">\PHPFusion\Panels</a>&#124;null


<a name="method_cachePanels" class="anchor"></a>
#### public cachePanels() : array

```
Static public cachePanels() : array
```

**Summary**

Cache panels

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)

**Returns:** array


<a name="method_addPanel" class="anchor"></a>
#### public addPanel() 

```
Static public addPanel(  $panel_name,   $panel_content,   $panel_side,   $panel_access,   $panel_order) 
```

**Summary**

Add Panel to List of Panels to be cached

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $panel_name  |  |
| <code></code> | $panel_content  |  |
| <code></code> | $panel_side  |  |
| <code></code> | $panel_access  |  |
| <code></code> | $panel_order  |  |




<a name="method_displayPanel" class="anchor"></a>
#### public displayPanel() : string

```
Static public displayPanel(integer  $panel_id) : string
```

**Summary**

Display a panel given a panel id

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $panel_id  |  |

**Returns:** string


<a name="method_getPanelExcluded" class="anchor"></a>
#### public getPanelExcluded() : array

```
Static public getPanelExcluded() : array
```

**Summary**

Get excluded panel list

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)

**Returns:** array


<a name="method_getAvailablePanels" class="anchor"></a>
#### public getAvailablePanels() : array

```
Static public getAvailablePanels(array  $excluded_panels = array()) : array
```

**Summary**

Get all available panels

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $excluded_panels  |  |

**Returns:** array


<a name="method_hidePanel" class="anchor"></a>
#### public hidePanel() 

```
public hidePanel(  $side) 
```

**Summary**

Hide panel

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $side  | - 'LEFT', 'RIGHT', 'U_CENTER', 'L_CENTER', 'AU_CENTER', 'BL_CENTER', 'USER1', 'USER2', 'USER3', 'USER4' |




<a name="method_hideAll" class="anchor"></a>
#### public hideAll() 

```
public hideAll() 
```

**Summary**

Hide all panels

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)




<a name="method_getSitePanel" class="anchor"></a>
#### public getSitePanel() 

```
public getSitePanel() 
```

**Summary**

Cache and generate Panel Constants

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)




<a name="method_checkPanelStatus" class="anchor"></a>
#### public checkPanelStatus() : boolean

```
Static public checkPanelStatus(string  $side) : boolean
```

**Summary**

Check panel exclusions in certain page, which will be dropped sooner or later
Because we will need page composition database soon

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $side  |  |

**Returns:** boolean


<a name="method_hide_panel" class="anchor"></a>
#### (deprecated) - public hide_panel() 

```
public hide_panel(  $side) 
```

**Summary**

Hide panel

**Deprecated**
Deprecateduse hidePanel()
**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $side  | - 'LEFT', 'RIGHT', 'U_CENTER', 'L_CENTER', 'AU_CENTER', 'BL_CENTER', 'USER1', 'USER2', 'USER3', 'USER4' |




<a name="method_wildcardMatch" class="anchor"></a>
#### private wildcardMatch() : false&amp;#124;integer

```
private wildcardMatch(  $source,   $pattern) : false&amp;#124;integer
```

**Details:**
* Inherited From: [\PHPFusion\Panels](../classes/PHPFusion.Panels.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $source  |  |
| <code></code> | $pattern  |  |

**Returns:** false&#124;integer



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
