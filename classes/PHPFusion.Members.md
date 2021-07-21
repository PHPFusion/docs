# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Members
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Members

---
### Constants
* No constants found
---
### Properties
* [protected $filters](../classes/PHPFusion.Members.md#property_filters)
* [private $instance](../classes/PHPFusion.Members.md#property_instance)
* [private $locale](../classes/PHPFusion.Members.md#property_locale)
* [private $max_rows](../classes/PHPFusion.Members.md#property_max_rows)
* [private $default_info](../classes/PHPFusion.Members.md#property_default_info)
* [private $sortby](../classes/PHPFusion.Members.md#property_sortby)
* [private $orderby](../classes/PHPFusion.Members.md#property_orderby)
* [private $sort_order](../classes/PHPFusion.Members.md#property_sort_order)
* [private $search_text](../classes/PHPFusion.Members.md#property_search_text)
* [private $rowstart](../classes/PHPFusion.Members.md#property_rowstart)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Members.md#method_getInstance)
* [public display_members()](../classes/PHPFusion.Members.md#method_display_members)
* [public setFilters()](../classes/PHPFusion.Members.md#method_setFilters)
* [protected getMembers()](../classes/PHPFusion.Members.md#method_getMembers)
* [private __construct()](../classes/PHPFusion.Members.md#method___construct)
* [private getMemberRows()](../classes/PHPFusion.Members.md#method_getMemberRows)
* [private getSelectors()](../classes/PHPFusion.Members.md#method_getSelectors)
* [private getJoins()](../classes/PHPFusion.Members.md#method_getJoins)
* [private getConditions()](../classes/PHPFusion.Members.md#method_getConditions)
* [private getFilters()](../classes/PHPFusion.Members.md#method_getFilters)
* [private getGroupBy()](../classes/PHPFusion.Members.md#method_getGroupBy)
* [private getOrderBy()](../classes/PHPFusion.Members.md#method_getOrderBy)
* [private getLimit()](../classes/PHPFusion.Members.md#method_getLimit)
* [private __clone()](../classes/PHPFusion.Members.md#method___clone)
---
### Details
* File: [classes\PHPFusion\Members.php](../files/classes.PHPFusion.Members.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Members
---
## Properties
<a name="property_filters"></a>
#### protected $filters : 
---
**Type:** 

**Details:**


<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_max_rows"></a>
#### private $max_rows : 
---
**Type:** 

**Details:**


<a name="property_default_info"></a>
#### private $default_info : 
---
**Type:** 

**Details:**


<a name="property_sortby"></a>
#### private $sortby : 
---
**Type:** 

**Details:**


<a name="property_orderby"></a>
#### private $orderby : 
---
**Type:** 

**Details:**


<a name="property_sort_order"></a>
#### private $sort_order : 
---
**Type:** 

**Details:**


<a name="property_search_text"></a>
#### private $search_text : 
---
**Type:** 

**Details:**


<a name="property_rowstart"></a>
#### private $rowstart : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static&amp;#124;null

```
Static public getInstance(boolean  $set_info = TRUE) : static&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $set_info  |  |

**Returns:** static&#124;null


<a name="method_display_members" class="anchor"></a>
#### public display_members() : array&amp;#124;null

```
public display_members() : array&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)
##### Throws:
| Type | Description |
| ---- | ----------- |
| \Exception |  |

**Returns:** array&#124;null


<a name="method_setFilters" class="anchor"></a>
#### public setFilters() 

```
public setFilters(array  $filters = array()) 
```

**Summary**

Set custom filters

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $filters  | Indexes:
'select' - query selection,
'condition', - query condition
'order', - order
'limit', - limitations
'join' - join statements |




<a name="method_getMembers" class="anchor"></a>
#### protected getMembers() : mixed

```
protected getMembers() : mixed
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** mixed


<a name="method___construct" class="anchor"></a>
#### private __construct() 

```
private __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)




<a name="method_getMemberRows" class="anchor"></a>
#### private getMemberRows() : integer

```
private getMemberRows() : integer
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** integer


<a name="method_getSelectors" class="anchor"></a>
#### private getSelectors() : string

```
private getSelectors() : string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** string


<a name="method_getJoins" class="anchor"></a>
#### private getJoins() : mixed&amp;#124;string

```
private getJoins() : mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** mixed&#124;string


<a name="method_getConditions" class="anchor"></a>
#### private getConditions() : string

```
private getConditions() : string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** string


<a name="method_getFilters" class="anchor"></a>
#### private getFilters() : string

```
private getFilters() : string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** string


<a name="method_getGroupBy" class="anchor"></a>
#### private getGroupBy() : mixed&amp;#124;string

```
private getGroupBy() : mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** mixed&#124;string


<a name="method_getOrderBy" class="anchor"></a>
#### private getOrderBy() : mixed&amp;#124;string

```
private getOrderBy() : mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** mixed&#124;string


<a name="method_getLimit" class="anchor"></a>
#### private getLimit() : integer&amp;#124;mixed

```
private getLimit() : integer&amp;#124;mixed
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)

**Returns:** integer&#124;mixed


<a name="method___clone" class="anchor"></a>
#### private __clone() 

```
private __clone() 
```

**Details:**
* Inherited From: [\PHPFusion\Members](../classes/PHPFusion.Members.md)





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
