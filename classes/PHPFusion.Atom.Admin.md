# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Atom\Admin
### Namespace: [\PHPFusion\Atom](../namespaces/PHPFusion.Atom.md)
---
**Summary:**

Administration Page for Theme Settings
Class Admin

---
### Constants
* No constants found
---
### Properties
* [private $locale](../classes/PHPFusion.Atom.Admin.md#property_locale)
---
### Methods
* [public __construct()](../classes/PHPFusion.Atom.Admin.md#method___construct)
* [public themeWidgetExists()](../classes/PHPFusion.Atom.Admin.md#method_themeWidgetExists)
* [public displayThemeEditor()](../classes/PHPFusion.Atom.Admin.md#method_displayThemeEditor)
* [public verifyTheme()](../classes/PHPFusion.Atom.Admin.md#method_verifyTheme)
* [public displayThemeList()](../classes/PHPFusion.Atom.Admin.md#method_displayThemeList)
* [public themeInstallable()](../classes/PHPFusion.Atom.Admin.md#method_themeInstallable)
* [public adminThemesList()](../classes/PHPFusion.Atom.Admin.md#method_adminThemesList)
* [public themeUploader()](../classes/PHPFusion.Atom.Admin.md#method_themeUploader)
---
### Details
* File: [classes\PHPFusion\Atom\Admin.php](../files/classes.PHPFusion.Atom.Admin.md)
* Package: PHPFusion\Atom
* Class Hierarchy:
  * \PHPFusion\Atom\Admin
---
## Properties
<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)




<a name="method_themeWidgetExists" class="anchor"></a>
#### public themeWidgetExists() : boolean

```
Static public themeWidgetExists(string  $theme_name) : boolean
```

**Summary**

Check if a theme widget file exist

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme_name  |  |

**Returns:** boolean


<a name="method_displayThemeEditor" class="anchor"></a>
#### public displayThemeEditor() 

```
Static public displayThemeEditor(string  $theme_name) 
```

**Summary**

The Theme Editor - Manage UI

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme_name  |  |




<a name="method_verifyTheme" class="anchor"></a>
#### public verifyTheme() : boolean

```
Static public verifyTheme(string  $theme_name) : boolean
```

**Summary**

Verify theme exist

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme_name  |  |

**Returns:** boolean


<a name="method_displayThemeList" class="anchor"></a>
#### public displayThemeList() 

```
Static public displayThemeList() 
```

**Summary**

Display available site themes

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)




<a name="method_themeInstallable" class="anchor"></a>
#### public themeInstallable() : boolean

```
Static public themeInstallable(string  $theme_name, boolean  $admin = FALSE) : boolean
```

**Summary**

Verify that theme exist and not active

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme_name  |  |
| <code>boolean</code> | $admin  |  |

**Returns:** boolean


<a name="method_adminThemesList" class="anchor"></a>
#### public adminThemesList() 

```
Static public adminThemesList() 
```

**Summary**

Display available admin themes

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)




<a name="method_themeUploader" class="anchor"></a>
#### public themeUploader() 

```
Static public themeUploader() 
```

**Summary**

Upload site/admin theme

**Details:**
* Inherited From: [\PHPFusion\Atom\Admin](../classes/PHPFusion.Atom.Admin.md)





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
