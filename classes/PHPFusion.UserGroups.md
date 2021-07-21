# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\UserGroups
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class UserGroups

---
### Constants
* No constants found
---
### Properties
* [private $instance](../classes/PHPFusion.UserGroups.md#property_instance)
* [private $info](../classes/PHPFusion.UserGroups.md#property_info)
---
### Methods
* [public getInstance()](../classes/PHPFusion.UserGroups.md#method_getInstance)
* [public setGroup()](../classes/PHPFusion.UserGroups.md#method_setGroup)
* [public showGroup()](../classes/PHPFusion.UserGroups.md#method_showGroup)
* [protected setGroupInfo()](../classes/PHPFusion.UserGroups.md#method_setGroupInfo)
---
### Details
* File: [classes\PHPFusion\UserGroups.php](../files/classes.PHPFusion.UserGroups.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\UserGroups
---
## Properties
<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**


<a name="property_info"></a>
#### private $info : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Get the UserGroups Instance

**Details:**
* Inherited From: [\PHPFusion\UserGroups](../classes/PHPFusion.UserGroups.md)

**Returns:** null&#124;static


<a name="method_setGroup" class="anchor"></a>
#### public setGroup() : null&amp;#124;\PHPFusion\UserGroups&amp;#124;static

```
public setGroup(integer  $group_id, boolean  $set_info = TRUE) : null&amp;#124;\PHPFusion\UserGroups&amp;#124;static
```

**Summary**

Set the group id and trigger setGroupInfo

**Details:**
* Inherited From: [\PHPFusion\UserGroups](../classes/PHPFusion.UserGroups.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group_id  |  |
| <code>boolean</code> | $set_info  |  |

**Returns:** null&#124;<a href="../classes/PHPFusion.UserGroups.html">\PHPFusion\UserGroups</a>&#124;static


<a name="method_showGroup" class="anchor"></a>
#### public showGroup() 

```
public showGroup() 
```

**Summary**

Render the global or custom template

**Details:**
* Inherited From: [\PHPFusion\UserGroups](../classes/PHPFusion.UserGroups.md)




<a name="method_setGroupInfo" class="anchor"></a>
#### protected setGroupInfo() : array

```
protected setGroupInfo(integer  $group_id) : array
```

**Summary**

Fetch group information

**Details:**
* Inherited From: [\PHPFusion\UserGroups](../classes/PHPFusion.UserGroups.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group_id  |  |

**Returns:** array



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
