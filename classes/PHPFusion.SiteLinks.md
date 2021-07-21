# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\SiteLinks
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class SiteLinks
Navigational Bar

---
### Constants
* [ MENU_DEFAULT_ID](../classes/PHPFusion.SiteLinks.md#constant_MENU_DEFAULT_ID)
---
### Properties
* [protected $position_opts](../classes/PHPFusion.SiteLinks.md#property_position_opts)
* [private $id](../classes/PHPFusion.SiteLinks.md#property_id)
* [private $instances](../classes/PHPFusion.SiteLinks.md#property_instances)
* [private $primary_cache_data](../classes/PHPFusion.SiteLinks.md#property_primary_cache_data)
* [private $optional_cache_data](../classes/PHPFusion.SiteLinks.md#property_optional_cache_data)
* [private $link_instances](../classes/PHPFusion.SiteLinks.md#property_link_instances)
---
### Methods
* [public getSiteLinksPosition()](../classes/PHPFusion.SiteLinks.md#method_getSiteLinksPosition)
* [public getSiteLinks()](../classes/PHPFusion.SiteLinks.md#method_getSiteLinks)
* [public getCurrentSiteLinks()](../classes/PHPFusion.SiteLinks.md#method_getCurrentSiteLinks)
* [public verifySiteLink()](../classes/PHPFusion.SiteLinks.md#method_verifySiteLink)
* [public deleteSiteLink()](../classes/PHPFusion.SiteLinks.md#method_deleteSiteLink)
* [public getLinkVisibility()](../classes/PHPFusion.SiteLinks.md#method_getLinkVisibility)
* [public setSubLinks()](../classes/PHPFusion.SiteLinks.md#method_setSubLinks)
* [public getSiteLinksData()](../classes/PHPFusion.SiteLinks.md#method_getSiteLinksData)
* [public getInstance()](../classes/PHPFusion.SiteLinks.md#method_getInstance)
* [public addMenuLink()](../classes/PHPFusion.SiteLinks.md#method_addMenuLink)
* [public addOptionalMenuLink()](../classes/PHPFusion.SiteLinks.md#method_addOptionalMenuLink)
* [public showSubLinks()](../classes/PHPFusion.SiteLinks.md#method_showSubLinks)
* [public getMenuParam()](../classes/PHPFusion.SiteLinks.md#method_getMenuParam)
* [public replaceMenuParam()](../classes/PHPFusion.SiteLinks.md#method_replaceMenuParam)
* [public setMenuParam()](../classes/PHPFusion.SiteLinks.md#method_setMenuParam)
* [public get_current_SiteLinks()](../classes/PHPFusion.SiteLinks.md#method_get_current_SiteLinks) - (deprecated)
* [private setLinks()](../classes/PHPFusion.SiteLinks.md#method_setLinks)
* [private getSubLinksUrl()](../classes/PHPFusion.SiteLinks.md#method_getSubLinksUrl)
* [private getLinkInstance()](../classes/PHPFusion.SiteLinks.md#method_getLinkInstance)
* [private showMenuLinks()](../classes/PHPFusion.SiteLinks.md#method_showMenuLinks)
---
### Details
* File: [classes\PHPFusion\SiteLinks.php](../files/classes.PHPFusion.SiteLinks.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\SiteLinks
---
## Constants
<a name="constant_MENU_DEFAULT_ID" class="anchor"></a>
###### MENU_DEFAULT_ID
```
MENU_DEFAULT_ID = 'DefaultMenu'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| param |  |  |
| return |  | A blank static is set up once for each available $options[&#039;id&#039;]
If same instance exists, options can be mutated to alter the behavior of the menu

Simple Usage: SiteLinks::setSublinks($sep, $class, $options)-&gt;showSubLinks();

So in order to add a cart icon, we must declare at theme. |

---
## Properties
<a name="property_position_opts"></a>
#### protected $position_opts : 
---
**Type:** 

**Details:**


<a name="property_id"></a>
#### private $id : 
---
**Type:** 

**Details:**


<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**


<a name="property_primary_cache_data"></a>
#### private $primary_cache_data : 
---
**Type:** 

**Details:**


<a name="property_optional_cache_data"></a>
#### private $optional_cache_data : 
---
**Type:** 

**Details:**


<a name="property_link_instances"></a>
#### private $link_instances : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getSiteLinksPosition" class="anchor"></a>
#### public getSiteLinksPosition() : array

```
Static public getSiteLinksPosition() : array
```

**Summary**

Get Site Links Position Options

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)

**Returns:** array


<a name="method_getSiteLinks" class="anchor"></a>
#### public getSiteLinks() : array

```
Static public getSiteLinks(integer  $id) : array
```

**Summary**

Get Sitelinks SQL Row

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  |  |

**Returns:** array


<a name="method_getCurrentSiteLinks" class="anchor"></a>
#### public getCurrentSiteLinks() : array&amp;#124;boolean

```
Static public getCurrentSiteLinks(string  $url = &quot;&quot;, string  $key = NULL) : array&amp;#124;boolean
```

**Summary**

Given a matching URL, fetch Sitelinks data

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | url to match (link_url) column |
| <code>string</code> | $key  | column data to output, blank for all |

**Returns:** array&#124;boolean


<a name="method_verifySiteLink" class="anchor"></a>
#### public verifySiteLink() : integer&amp;#124;null

```
Static public verifySiteLink(integer  $link_id) : integer&amp;#124;null
```

**Summary**

Link ID validation

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $link_id  |  |

**Returns:** integer&#124;null


<a name="method_deleteSiteLink" class="anchor"></a>
#### public deleteSiteLink() : boolean&amp;#124;mixed&amp;#124;null&amp;#124;resource

```
Static public deleteSiteLink(integer  $link_id) : boolean&amp;#124;mixed&amp;#124;null&amp;#124;resource
```

**Summary**

SQL Delete Site Link Action

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $link_id  |  |

**Returns:** boolean&#124;mixed&#124;null&#124;resource


<a name="method_getLinkVisibility" class="anchor"></a>
#### public getLinkVisibility() : array

```
Static public getLinkVisibility() : array
```

**Summary**

Get Group Array

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)

**Returns:** array


<a name="method_setSubLinks" class="anchor"></a>
#### public setSubLinks() : static

```
Static public setSubLinks(array  $options = array()) : static
```

**Summary**

Calling the SiteLinks instance with Custom Parameters

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $options  |  |

**Returns:** static


<a name="method_getSiteLinksData" class="anchor"></a>
#### public getSiteLinksData() : array

```
Static public getSiteLinksData(array  $options = array()) : array
```

**Summary**

Fetches Site Links Hierarchy Data - for a less support complexity

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $options  | - join
- link_position (array)
- condition
- group
- order |

**Returns:** array


<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $id = self::MENU_DEFAULT_ID) : static
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  |  |

**Returns:** static


<a name="method_addMenuLink" class="anchor"></a>
#### public addMenuLink() 

```
Static public addMenuLink(integer  $link_id, string  $link_name, integer  $link_cat, string  $link_url = &#039;&#039;, string  $link_icon = &#039;&#039;, boolean&amp;#124;FALSE  $link_active = FALSE, boolean&amp;#124;FALSE  $link_title = FALSE, boolean&amp;#124;FALSE  $link_disabled = FALSE, boolean&amp;#124;FALSE  $link_window = FALSE, string  $link_class = &#039;&#039;) 
```

**Summary**

Add a link to primary menu

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $link_id  |  |
| <code>string</code> | $link_name  |  |
| <code>integer</code> | $link_cat  |  |
| <code>string</code> | $link_url  |  |
| <code>string</code> | $link_icon  |  |
| <code>boolean&#124;FALSE</code> | $link_active  |  |
| <code>boolean&#124;FALSE</code> | $link_title  |  |
| <code>boolean&#124;FALSE</code> | $link_disabled  |  |
| <code>boolean&#124;FALSE</code> | $link_window  |  |
| <code>string</code> | $link_class  |  |




<a name="method_addOptionalMenuLink" class="anchor"></a>
#### public addOptionalMenuLink() 

```
Static public addOptionalMenuLink(integer  $link_id, string  $link_name, integer  $link_cat, string  $link_url = &#039;&#039;, string  $link_icon = &#039;&#039;, boolean&amp;#124;FALSE  $link_active = FALSE, boolean&amp;#124;FALSE  $link_title = FALSE, boolean&amp;#124;FALSE  $link_disabled = FALSE, boolean&amp;#124;FALSE  $link_window = FALSE, string  $link_class = &#039;&#039;) 
```

**Summary**

Add a link to secondary menu

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $link_id  |  |
| <code>string</code> | $link_name  |  |
| <code>integer</code> | $link_cat  |  |
| <code>string</code> | $link_url  |  |
| <code>string</code> | $link_icon  |  |
| <code>boolean&#124;FALSE</code> | $link_active  |  |
| <code>boolean&#124;FALSE</code> | $link_title  |  |
| <code>boolean&#124;FALSE</code> | $link_disabled  |  |
| <code>boolean&#124;FALSE</code> | $link_window  |  |
| <code>string</code> | $link_class  |  |




<a name="method_showSubLinks" class="anchor"></a>
#### public showSubLinks() : string

```
public showSubLinks(integer  $id) : string
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  |  |

**Returns:** string


<a name="method_getMenuParam" class="anchor"></a>
#### public getMenuParam() : mixed

```
Static public getMenuParam(mixed  $key = FALSE) : mixed
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  |  |

**Returns:** mixed


<a name="method_replaceMenuParam" class="anchor"></a>
#### public replaceMenuParam() 

```
Static public replaceMenuParam(string  $key, mixed  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>mixed</code> | $value  |  |




<a name="method_setMenuParam" class="anchor"></a>
#### public setMenuParam() 

```
Static public setMenuParam(string  $key, mixed  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>mixed</code> | $value  |  |




<a name="method_get_current_SiteLinks" class="anchor"></a>
#### (deprecated) - public get_current_SiteLinks() : array&amp;#124;boolean

```
Static public get_current_SiteLinks(string  $url = &quot;&quot;, string  $key = NULL) : array&amp;#124;boolean
```

**Summary**

Given a matching URL, fetch Sitelinks data

**Deprecated**
Deprecateduse getCurrentSiteLinks()
**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | url to match (link_url) column |
| <code>string</code> | $key  | column data to output, blank for all |

**Returns:** array&#124;boolean


<a name="method_setLinks" class="anchor"></a>
#### private setLinks() 

```
Static private setLinks() 
```

**Summary**

Init

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)




<a name="method_getSubLinksUrl" class="anchor"></a>
#### private getSubLinksUrl() : array

```
private getSubLinksUrl(array  $data, integer  $link_id) : array
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  |  |
| <code>integer</code> | $link_id  |  |

**Returns:** array


<a name="method_getLinkInstance" class="anchor"></a>
#### private getLinkInstance() : array

```
private getLinkInstance() : array
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)

**Returns:** array


<a name="method_showMenuLinks" class="anchor"></a>
#### private showMenuLinks() 

```
private showMenuLinks(  $id,   $data,   $linkclass = &#039;nav-link&#039;,   $dropdown = FALSE) 
```

**Details:**
* Inherited From: [\PHPFusion\SiteLinks](../classes/PHPFusion.SiteLinks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $id  |  |
| <code></code> | $data  |  |
| <code></code> | $linkclass  |  |
| <code></code> | $dropdown  |  |





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
