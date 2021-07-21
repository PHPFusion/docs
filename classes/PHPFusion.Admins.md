# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Admins
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Admin
This class is called in templates/admin_header.php
Determine how to we set variables on 3rd party script

---
### Constants
* No constants found
---
### Properties
* [public $admin_section_icons](../classes/PHPFusion.Admins.md#property_admin_section_icons)
* [public $admin_page_icons](../classes/PHPFusion.Admins.md#property_admin_page_icons)
* [private $instance](../classes/PHPFusion.Admins.md#property_instance)
* [private $admin_pages](../classes/PHPFusion.Admins.md#property_admin_pages)
* [private $locale](../classes/PHPFusion.Admins.md#property_locale)
* [private $admin_sections](../classes/PHPFusion.Admins.md#property_admin_sections)
* [private $admin_page_link](../classes/PHPFusion.Admins.md#property_admin_page_link)
* [private $current_page](../classes/PHPFusion.Admins.md#property_current_page)
* [private $comment_type](../classes/PHPFusion.Admins.md#property_comment_type)
* [private $submit_type](../classes/PHPFusion.Admins.md#property_submit_type)
* [private $submit_link](../classes/PHPFusion.Admins.md#property_submit_link)
* [private $link_type](../classes/PHPFusion.Admins.md#property_link_type)
* [private $submit_data](../classes/PHPFusion.Admins.md#property_submit_data)
* [private $folder_permissions](../classes/PHPFusion.Admins.md#property_folder_permissions)
* [private $custom_folders](../classes/PHPFusion.Admins.md#property_custom_folders)
---
### Methods
* [public __construct()](../classes/PHPFusion.Admins.md#method___construct)
* [public getInstance()](../classes/PHPFusion.Admins.md#method_getInstance)
* [public requestCache()](../classes/PHPFusion.Admins.md#method_requestCache)
* [public setAdminPages()](../classes/PHPFusion.Admins.md#method_setAdminPages)
* [public getAdminPages()](../classes/PHPFusion.Admins.md#method_getAdminPages)
* [public currentPage()](../classes/PHPFusion.Admins.md#method_currentPage)
* [public isActive()](../classes/PHPFusion.Admins.md#method_isActive)
* [public addAdminSection()](../classes/PHPFusion.Admins.md#method_addAdminSection)
* [public setAdminBreadcrumbs()](../classes/PHPFusion.Admins.md#method_setAdminBreadcrumbs)
* [public getAdminPageIcons()](../classes/PHPFusion.Admins.md#method_getAdminPageIcons)
* [public setAdminPageIcons()](../classes/PHPFusion.Admins.md#method_setAdminPageIcons)
* [public getLinkType()](../classes/PHPFusion.Admins.md#method_getLinkType)
* [public setLinkType()](../classes/PHPFusion.Admins.md#method_setLinkType)
* [public getSubmitType()](../classes/PHPFusion.Admins.md#method_getSubmitType)
* [public setSubmitType()](../classes/PHPFusion.Admins.md#method_setSubmitType)
* [public getSubmitData()](../classes/PHPFusion.Admins.md#method_getSubmitData)
* [public setSubmitData()](../classes/PHPFusion.Admins.md#method_setSubmitData)
* [public getSubmitLink()](../classes/PHPFusion.Admins.md#method_getSubmitLink)
* [public setSubmitLink()](../classes/PHPFusion.Admins.md#method_setSubmitLink)
* [public getCommentType()](../classes/PHPFusion.Admins.md#method_getCommentType)
* [public setCommentType()](../classes/PHPFusion.Admins.md#method_setCommentType)
* [public getFolderPermissions()](../classes/PHPFusion.Admins.md#method_getFolderPermissions)
* [public setFolderPermissions()](../classes/PHPFusion.Admins.md#method_setFolderPermissions)
* [public getCustomFolders()](../classes/PHPFusion.Admins.md#method_getCustomFolders)
* [public setCustomFolder()](../classes/PHPFusion.Admins.md#method_setCustomFolder)
* [public getAdminPageLink()](../classes/PHPFusion.Admins.md#method_getAdminPageLink)
* [public getCurrentPage()](../classes/PHPFusion.Admins.md#method_getCurrentPage)
* [public getAdminSections()](../classes/PHPFusion.Admins.md#method_getAdminSections)
* [public getAdminSectionIcons()](../classes/PHPFusion.Admins.md#method_getAdminSectionIcons)
* [public setAdminSectionIcons()](../classes/PHPFusion.Admins.md#method_setAdminSectionIcons)
* [public getAdminIcons()](../classes/PHPFusion.Admins.md#method_getAdminIcons)
* [public verticalAdminNav()](../classes/PHPFusion.Admins.md#method_verticalAdminNav)
* [public horizontalAdminNav()](../classes/PHPFusion.Admins.md#method_horizontalAdminNav)
* [public _currentPage()](../classes/PHPFusion.Admins.md#method__currentPage) - (deprecated)
* [public _isActive()](../classes/PHPFusion.Admins.md#method__isActive) - (deprecated)
* [public vertical_admin_nav()](../classes/PHPFusion.Admins.md#method_vertical_admin_nav) - (deprecated)
* [public horizontal_admin_nav()](../classes/PHPFusion.Admins.md#method_horizontal_admin_nav) - (deprecated)
* [public get_admin_icons()](../classes/PHPFusion.Admins.md#method_get_admin_icons) - (deprecated)
* [public get_admin_section_icons()](../classes/PHPFusion.Admins.md#method_get_admin_section_icons) - (deprecated)
---
### Details
* File: [classes\PHPFusion\Admins.php](../files/classes.PHPFusion.Admins.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\Admins
---
## Properties
<a name="property_admin_section_icons"></a>
#### public $admin_section_icons : array
---
**Type:** array
- default section icons
**Details:**


<a name="property_admin_page_icons"></a>
#### public $admin_page_icons : array
---
**Summary**

Default core administration pages

**Type:** array

**Details:**


<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**


<a name="property_admin_pages"></a>
#### private $admin_pages : 
---
**Type:** 

**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_admin_sections"></a>
#### private $admin_sections : array
---
**Type:** array

**Details:**


<a name="property_admin_page_link"></a>
#### private $admin_page_link : array
---
**Type:** array

**Details:**


<a name="property_current_page"></a>
#### private $current_page : 
---
**Summary**

Constructor class. No Params

**Type:** 

**Details:**


<a name="property_comment_type"></a>
#### private $comment_type : 
---
**Type:** 

**Details:**


<a name="property_submit_type"></a>
#### private $submit_type : 
---
**Type:** 

**Details:**


<a name="property_submit_link"></a>
#### private $submit_link : 
---
**Type:** 

**Details:**


<a name="property_link_type"></a>
#### private $link_type : 
---
**Type:** 

**Details:**


<a name="property_submit_data"></a>
#### private $submit_data : 
---
**Type:** 

**Details:**


<a name="property_folder_permissions"></a>
#### private $folder_permissions : 
---
**Type:** 

**Details:**


<a name="property_custom_folders"></a>
#### private $custom_folders : 
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
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance() : static
```

**Summary**

Add instance

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** static


<a name="method_requestCache" class="anchor"></a>
#### public requestCache() : string

```
public requestCache(string  $form_id, string  $form_type, integer  $item_id, array  $callback_fields = array(), integer  $cache_time = 30000) : string
```

**Summary**

Cache the Current Field Inputs within Login session.

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $form_id  |  |
| <code>string</code> | $form_type  |  |
| <code>integer</code> | $item_id  |  |
| <code>array</code> | $callback_fields  |  |
| <code>integer</code> | $cache_time  |  |

**Returns:** string


<a name="method_setAdminPages" class="anchor"></a>
#### public setAdminPages() 

```
public setAdminPages() 
```

**Summary**

Set admin sections

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)




<a name="method_getAdminPages" class="anchor"></a>
#### public getAdminPages() : array

```
public getAdminPages(integer  $page = NULL) : array
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page  |  |

**Returns:** array


<a name="method_currentPage" class="anchor"></a>
#### public currentPage() 

```
public currentPage() 
```

**Summary**

Build a return that always synchronize with the DB_ADMIN url.

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)




<a name="method_isActive" class="anchor"></a>
#### public isActive() : integer&amp;#124;string

```
public isActive() : integer&amp;#124;string
```

**Summary**

Determine which section is currently active.

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** integer&#124;string


<a name="method_addAdminSection" class="anchor"></a>
#### public addAdminSection() 

```
public addAdminSection(integer  $page, string  $section_title, string  $icon) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page  | 0-5 is core section pages. 6 and above are free to use. |
| <code>string</code> | $section_title  | Section title |
| <code>string</code> | $icon  | Section icon |




<a name="method_setAdminBreadcrumbs" class="anchor"></a>
#### public setAdminBreadcrumbs() 

```
public setAdminBreadcrumbs() 
```

**Summary**

Set admin breadcrumbs

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)




<a name="method_getAdminPageIcons" class="anchor"></a>
#### public getAdminPageIcons() : array

```
public getAdminPageIcons() : array
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** array


<a name="method_setAdminPageIcons" class="anchor"></a>
#### public setAdminPageIcons() 

```
public setAdminPageIcons(string  $rights, string  $icons) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  |  |
| <code>string</code> | $icons  |  |




<a name="method_getLinkType" class="anchor"></a>
#### public getLinkType() : array&amp;#124;mixed&amp;#124;null

```
public getLinkType(string  $type = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_setLinkType" class="anchor"></a>
#### public setLinkType() 

```
public setLinkType(string  $type, string  $link) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Link prefix |
| <code>string</code> | $link  | Link url |




<a name="method_getSubmitType" class="anchor"></a>
#### public getSubmitType() : array&amp;#124;mixed&amp;#124;null

```
public getSubmitType(string  $type = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Summary**

Get submit type

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | submit stype prefix |

**Returns:** array&#124;mixed&#124;null


<a name="method_setSubmitType" class="anchor"></a>
#### public setSubmitType() 

```
public setSubmitType(string  $type, string  $title) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Submissions prefix |
| <code>string</code> | $title  | Title |




<a name="method_getSubmitData" class="anchor"></a>
#### public getSubmitData() : array&amp;#124;mixed&amp;#124;null

```
public getSubmitData(string  $type = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_setSubmitData" class="anchor"></a>
#### public setSubmitData() 

```
public setSubmitData(string  $type, array  $options = array()) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Submissions prefix |
| <code>array</code> | $options  | array(infusion_name, link, submit_link, submit_locale, title,admin_link) |




<a name="method_getSubmitLink" class="anchor"></a>
#### public getSubmitLink() : array&amp;#124;mixed&amp;#124;null

```
public getSubmitLink(string  $type = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_setSubmitLink" class="anchor"></a>
#### public setSubmitLink() 

```
public setSubmitLink(string  $type, string  $link) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Submissions stype prefix |
| <code>string</code> | $link  | Admin submission url |




<a name="method_getCommentType" class="anchor"></a>
#### public getCommentType() : array&amp;#124;mixed&amp;#124;null

```
public getCommentType(string  $type = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_setCommentType" class="anchor"></a>
#### public setCommentType() 

```
public setCommentType(string  $type, string  $title) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Comment prefix |
| <code>string</code> | $title  | Title |




<a name="method_getFolderPermissions" class="anchor"></a>
#### public getFolderPermissions() 

```
public getFolderPermissions(string  $type = NULL) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Infusion name |




<a name="method_setFolderPermissions" class="anchor"></a>
#### public setFolderPermissions() 

```
public setFolderPermissions(string  $type, array  $options = array()) 
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Infusion name |
| <code>array</code> | $options  | array(image_folder => TRUE or FALSE) |




<a name="method_getCustomFolders" class="anchor"></a>
#### public getCustomFolders() : array&amp;#124;null

```
public getCustomFolders(string  $rights = NULL) : array&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  |  |

**Returns:** array&#124;null


<a name="method_setCustomFolder" class="anchor"></a>
#### public setCustomFolder() 

```
public setCustomFolder(string  $rights, array  $options = array()) 
```

**Summary**

A custom folder that appears in the file manager

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  |  |
| <code>array</code> | $options  | setCustomFolder('N', [['path' => IMAGES_N, 'URL' => fusion_get_settings('siteurl').'infusions/news/images/', 'alias' => 'news']]); |




<a name="method_getAdminPageLink" class="anchor"></a>
#### public getAdminPageLink() : array

```
public getAdminPageLink() : array
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** array


<a name="method_getCurrentPage" class="anchor"></a>
#### public getCurrentPage() : string

```
public getCurrentPage() : string
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** string


<a name="method_getAdminSections" class="anchor"></a>
#### public getAdminSections() : array

```
public getAdminSections() : array
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** array


<a name="method_getAdminSectionIcons" class="anchor"></a>
#### public getAdminSectionIcons() : string

```
public getAdminSectionIcons(integer  $page_number) : string
```

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page_number  |  |

**Returns:** string


<a name="method_setAdminSectionIcons" class="anchor"></a>
#### public setAdminSectionIcons() 

```
public setAdminSectionIcons(integer  $page, string  $icon) 
```

**Summary**

Replace admin page icons

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page  |  |
| <code>string</code> | $icon  |  |




<a name="method_getAdminIcons" class="anchor"></a>
#### public getAdminIcons() : boolean

```
public getAdminIcons(string  $admin_rights) : boolean
```

**Summary**

Get the administration page icons

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $admin_rights  |  |

**Returns:** boolean


<a name="method_verticalAdminNav" class="anchor"></a>
#### public verticalAdminNav() : string

```
public verticalAdminNav(boolean  $image_icon = FALSE) : string
```

**Summary**

Displays vertical collapsible administration navigation

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $image_icon  |  |

**Returns:** string


<a name="method_horizontalAdminNav" class="anchor"></a>
#### public horizontalAdminNav() : string

```
public horizontalAdminNav(boolean  $icon_only = FALSE) : string
```

**Summary**

Displays horizontal administration navigation

**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $icon_only  |  |

**Returns:** string


<a name="method__currentPage" class="anchor"></a>
#### (deprecated) - public _currentPage() 

```
public _currentPage() 
```

**Summary**

Build a return that always synchronize with the DB_ADMIN url.

**Deprecated**
Deprecateduse currentPage()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)




<a name="method__isActive" class="anchor"></a>
#### (deprecated) - public _isActive() : integer&amp;#124;string

```
public _isActive() : integer&amp;#124;string
```

**Summary**

Determine which section is currently active.

**Deprecated**
Deprecateduse isActive()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)

**Returns:** integer&#124;string


<a name="method_vertical_admin_nav" class="anchor"></a>
#### (deprecated) - public vertical_admin_nav() : string

```
public vertical_admin_nav(boolean  $image_icon = FALSE) : string
```

**Summary**

Displays vertical collapsible administration navigation

**Deprecated**
Deprecateduse verticalAdminNav()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $image_icon  |  |

**Returns:** string


<a name="method_horizontal_admin_nav" class="anchor"></a>
#### (deprecated) - public horizontal_admin_nav() : string

```
public horizontal_admin_nav(boolean  $icon_only = FALSE) : string
```

**Summary**

Displays horizontal administration navigation

**Deprecated**
Deprecateduse horizontalAdminNav()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $icon_only  |  |

**Returns:** string


<a name="method_get_admin_icons" class="anchor"></a>
#### (deprecated) - public get_admin_icons() : boolean

```
public get_admin_icons(string  $admin_rights) : boolean
```

**Summary**

Get the administration page icons

**Deprecated**
Deprecateduse getAdminIcons()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $admin_rights  |  |

**Returns:** boolean


<a name="method_get_admin_section_icons" class="anchor"></a>
#### (deprecated) - public get_admin_section_icons() : string

```
public get_admin_section_icons(integer  $page_number) : string
```

**Deprecated**
Deprecateduse getAdminSectionIcons()
**Details:**
* Inherited From: [\PHPFusion\Admins](../classes/PHPFusion.Admins.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page_number  |  |

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
