# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Installer\Infusions
### Namespace: [\PHPFusion\Installer](../namespaces/PHPFusion.Installer.md)
---
**Summary:**

Class Infusions

---
### Constants
* No constants found
---
### Properties
* [private $locale](../classes/PHPFusion.Installer.Infusions.md#property_locale)
* [private $instance](../classes/PHPFusion.Installer.Infusions.md#property_instance)
* [private $inf](../classes/PHPFusion.Installer.Infusions.md#property_inf)
---
### Methods
* [public loadConfiguration()](../classes/PHPFusion.Installer.Infusions.md#method_loadConfiguration)
* [public getInstance()](../classes/PHPFusion.Installer.Infusions.md#method_getInstance)
* [public loadInfusion()](../classes/PHPFusion.Installer.Infusions.md#method_loadInfusion)
* [public loadUpgrade()](../classes/PHPFusion.Installer.Infusions.md#method_loadUpgrade)
* [public infuse()](../classes/PHPFusion.Installer.Infusions.md#method_infuse)
* [public defuse()](../classes/PHPFusion.Installer.Infusions.md#method_defuse)
* [protected adminpanel_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_adminpanel_infuse)
* [protected dropcol_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_dropcol_infuse)
* [protected sitelink_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_sitelink_infuse)
* [protected mlt_insertdbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_insertdbrow_infuse)
* [protected mlt_adminpanel_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_adminpanel_infuse)
* [protected mlt_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_infuse)
* [protected altertable_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_altertable_infuse)
* [protected updatedbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_updatedbrow_infuse)
* [protected newtable_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_newtable_infuse)
* [protected newcol_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_newcol_infuse)
* [protected insertdbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_insertdbrow_infuse)
* [protected deldbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_deldbrow_infuse)
---
### Details
* File: [classes\PHPFusion\Installer\Infusions.php](../files/classes.PHPFusion.Installer.Infusions.md)
* Package: PHPFusion\Installer
* Class Hierarchy:
  * \PHPFusion\Installer\Infusions
---
## Properties
<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**


<a name="property_inf"></a>
#### private $inf : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_loadConfiguration" class="anchor"></a>
#### public loadConfiguration() 

```
Static public loadConfiguration() 
```

**Summary**

Version 7 compatible infusions load constants.

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Get Instance

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)

**Returns:** null&#124;static


<a name="method_loadInfusion" class="anchor"></a>
#### public loadInfusion() : array

```
Static public loadInfusion(string  $folder) : array
```

**Summary**

Load Infusion according to Infusion Standard Developer Kit

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  |  |

**Returns:** array


<a name="method_loadUpgrade" class="anchor"></a>
#### public loadUpgrade() : array

```
Static public loadUpgrade(string  $folder, string  $upgrade_file_path) : array
```

**Summary**

Load upgrade folder

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  |  |
| <code>string</code> | $upgrade_file_path  |  |

**Returns:** array


<a name="method_infuse" class="anchor"></a>
#### public infuse() : mixed&amp;#124;null

```
public infuse(  $folder) : mixed&amp;#124;null
```

**Summary**

Execute Installation according to Infusion Standard Developer Kit

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
* Uses:
 * [adminpanel_infuse]()
 * [dropcol_infuse]()
 * [sitelink_infuse]()
 * [mlt_insertdbrow_infuse]()
 * [mlt_adminpanel_infuse]()
 * [mlt_infuse]()
 * [altertable_infuse]()
 * [updatedbrow_infuse]()
 * [newtable_infuse]()
 * [newcol_infuse]()
 * [insertdbrow_infuse]()
 * [deldbrow_infuse]()
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $folder  |  |

**Returns:** mixed&#124;null


<a name="method_defuse" class="anchor"></a>
#### public defuse() 

```
public defuse(  $folder) 
```

**Summary**

Defuse

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $folder  |  |




<a name="method_adminpanel_infuse" class="anchor"></a>
#### protected adminpanel_infuse() : boolean

```
Static protected adminpanel_infuse(array  $inf) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_dropcol_infuse" class="anchor"></a>
#### protected dropcol_infuse() : boolean

```
protected dropcol_infuse(array  $inf) : boolean
```

**Summary**

Drop column

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_sitelink_infuse" class="anchor"></a>
#### protected sitelink_infuse() : boolean

```
protected sitelink_infuse(array  $inf) : boolean
```

**Summary**

Add Sitelinks

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_insertdbrow_infuse" class="anchor"></a>
#### protected mlt_insertdbrow_infuse() : boolean

```
protected mlt_insertdbrow_infuse(array  $inf) : boolean
```

**Summary**

Register Multilang rights

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_adminpanel_infuse" class="anchor"></a>
#### protected mlt_adminpanel_infuse() : boolean

```
protected mlt_adminpanel_infuse(array  $inf) : boolean
```

**Summary**

Register Multilang Admin Pages

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_infuse" class="anchor"></a>
#### protected mlt_infuse() : boolean

```
protected mlt_infuse(array  $inf) : boolean
```

**Summary**

Multilanguage Insert Rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_altertable_infuse" class="anchor"></a>
#### protected altertable_infuse() : boolean

```
protected altertable_infuse(array  $inf) : boolean
```

**Summary**

Change table structure

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_updatedbrow_infuse" class="anchor"></a>
#### protected updatedbrow_infuse() : boolean

```
protected updatedbrow_infuse(array  $inf) : boolean
```

**Summary**

Update Row Record

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_newtable_infuse" class="anchor"></a>
#### protected newtable_infuse() : boolean

```
protected newtable_infuse(array  $inf) : boolean
```

**Summary**

Install New Table

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_newcol_infuse" class="anchor"></a>
#### protected newcol_infuse() : boolean

```
protected newcol_infuse(array  $inf) : boolean
```

**Summary**

Insert New Column

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_insertdbrow_infuse" class="anchor"></a>
#### protected insertdbrow_infuse() : boolean

```
protected insertdbrow_infuse(array  $inf) : boolean
```

**Summary**

Insert Rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_deldbrow_infuse" class="anchor"></a>
#### protected deldbrow_infuse() : boolean

```
protected deldbrow_infuse(array  $inf) : boolean
```

**Summary**

Delete rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean



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
