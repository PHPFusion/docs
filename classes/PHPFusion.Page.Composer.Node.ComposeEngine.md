# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Page\Composer\Node\ComposeEngine
### Namespace: [\PHPFusion\Page\Composer\Node](../namespaces/PHPFusion.Page.Composer.Node.md)
---
**Summary:**

Class PageAdmin

---
### Constants
* No constants found
---
### Properties
* [protected $locale](../classes/PHPFusion.Page.PageAdmin.md#property_locale)
* [protected $textarea_options](../classes/PHPFusion.Page.PageAdmin.md#property_textarea_options)
* [protected $is_editing](../classes/PHPFusion.Page.PageAdmin.md#property_is_editing)
* [protected $adminComposerOpts](../classes/PHPFusion.Page.PageModel.md#property_adminComposerOpts)
* [protected $composerData](../classes/PHPFusion.Page.PageModel.md#property_composerData)
* [protected $widgets](../classes/PHPFusion.Page.PageModel.md#property_widgets)
* [protected $data](../classes/PHPFusion.Page.PageModel.md#property_data)
* [protected $rowData](../classes/PHPFusion.Page.PageModel.md#property_rowData)
* [protected $colData](../classes/PHPFusion.Page.PageModel.md#property_colData)
* [protected $gridData](../classes/PHPFusion.Page.PageModel.md#property_gridData)
* [private $pageInstance](../classes/PHPFusion.Page.PageModel.md#property_pageInstance)
* [private $allowed_admin_pages](../classes/PHPFusion.Page.PageAdmin.md#property_allowed_admin_pages)
* [private $current_section](../classes/PHPFusion.Page.PageAdmin.md#property_current_section)
* [private $current_status](../classes/PHPFusion.Page.PageAdmin.md#property_current_status)
* [private $current_action](../classes/PHPFusion.Page.PageAdmin.md#property_current_action)
* [private $current_page_id](../classes/PHPFusion.Page.PageAdmin.md#property_current_page_id)
* [private $composer_mode](../classes/PHPFusion.Page.PageAdmin.md#property_composer_mode)
* [private $allowed_composer_mode](../classes/PHPFusion.Page.PageAdmin.md#property_allowed_composer_mode)
* [private $composer_exclude](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#property_composer_exclude)
---
### Methods
* [public getAllowedComposerMode()](../classes/PHPFusion.Page.PageAdmin.md#method_getAllowedComposerMode)
* [public getComposerAdminInstance()](../classes/PHPFusion.Page.PageAdmin.md#method_getComposerAdminInstance)
* [public setPageAdminConfig()](../classes/PHPFusion.Page.PageAdmin.md#method_setPageAdminConfig)
* [public displayPage()](../classes/PHPFusion.Page.PageAdmin.md#method_displayPage)
* [public getComposerMode()](../classes/PHPFusion.Page.PageAdmin.md#method_getComposerMode)
* [public getInstance()](../classes/PHPFusion.Page.PageModel.md#method_getInstance)
* [public loadCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_loadCustomPage)
* [public queryCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_queryCustomPage)
* [public displayCustomPageSelector()](../classes/PHPFusion.Page.PageModel.md#method_displayCustomPageSelector)
* [public getComposerExclude()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_getComposerExclude)
* [public displayContent()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_displayContent)
* [protected loadComposerData()](../classes/PHPFusion.Page.PageModel.md#method_loadComposerData)
* [protected cacheWidget()](../classes/PHPFusion.Page.PageModel.md#method_cacheWidget)
* [protected calculateSpan()](../classes/PHPFusion.Page.PageModel.md#method_calculateSpan)
* [protected deleteCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_deleteCustomPage)
* [protected verifyCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_verifyCustomPage)
* [protected executeRowDelete()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_executeRowDelete)
* [protected executeRowDuplicate()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_executeRowDuplicate)
* [protected validateRowData()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_validateRowData)
* [protected executeRowUpdate()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_executeRowUpdate)
* [protected getColData()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_getColData)
* [protected executeColDuplicate()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_executeColDuplicate)
* [protected getWidgetIcon()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_getWidgetIcon)
* [protected drawCols()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_drawCols)
* [private displayRowForm()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_displayRowForm)
* [private displayColForm()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_displayColForm)
* [private displayWidgetForm()](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md#method_displayWidgetForm)
---
### Details
* File: [classes\PHPFusion\Page\Composer\Node\ComposeEngine.php](../files/classes.PHPFusion.Page.Composer.Node.ComposeEngine.md)
* Package: Default
* Class Hierarchy:  
  * [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
  * [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)
  * \PHPFusion\Page\Composer\Node\ComposeEngine
---
## Properties
<a name="property_locale"></a>
#### protected $locale : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_textarea_options"></a>
#### protected $textarea_options : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_is_editing"></a>
#### protected $is_editing : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_adminComposerOpts"></a>
#### protected $adminComposerOpts : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_composerData"></a>
#### protected $composerData : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_widgets"></a>
#### protected $widgets : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_data"></a>
#### protected $data : array
---
**Type:** array
- default custom page data
**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_rowData"></a>
#### protected $rowData : array
---
**Type:** array
- default grid row data
**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_colData"></a>
#### protected $colData : array
---
**Type:** array
- default grid column data
**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_gridData"></a>
#### protected $gridData : array
---
**Type:** array
the row information
**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_pageInstance"></a>
#### private $pageInstance : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)


<a name="property_allowed_admin_pages"></a>
#### private $allowed_admin_pages : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_current_section"></a>
#### private $current_section : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_current_status"></a>
#### private $current_status : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_current_action"></a>
#### private $current_action : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_current_page_id"></a>
#### private $current_page_id : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_composer_mode"></a>
#### private $composer_mode : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_allowed_composer_mode"></a>
#### private $allowed_composer_mode : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)


<a name="property_composer_exclude"></a>
#### private $composer_exclude : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getAllowedComposerMode" class="anchor"></a>
#### public getAllowedComposerMode() : array

```
Static public getAllowedComposerMode() : array
```

**Summary**

Returns list of administration mode

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)

**Returns:** array


<a name="method_getComposerAdminInstance" class="anchor"></a>
#### public getComposerAdminInstance() : object

```
Static public getComposerAdminInstance() : object
```

**Summary**

Return page composer object

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)

**Returns:** object


<a name="method_setPageAdminConfig" class="anchor"></a>
#### public setPageAdminConfig() 

```
Static public setPageAdminConfig() 
```

**Summary**

Init

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)




<a name="method_displayPage" class="anchor"></a>
#### public displayPage() 

```
public displayPage() 
```

**Summary**

Display page

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)




<a name="method_getComposerMode" class="anchor"></a>
#### public getComposerMode() : string

```
Static public getComposerMode() : string
```

**Summary**

Get page administration mode

**Details:**
* Inherited From: [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)

**Returns:** string


<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance() : static
```

**Summary**

Return page composer object

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)

**Returns:** static


<a name="method_loadCustomPage" class="anchor"></a>
#### public loadCustomPage() : \PHPFusion\Page\array;

```
Static public loadCustomPage(integer  $id) : \PHPFusion\Page\array;
```

**Summary**

Displays a single custom page data

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  | page_id |

**Returns:** \PHPFusion\Page\array;


<a name="method_queryCustomPage" class="anchor"></a>
#### public queryCustomPage() : mixed

```
Static public queryCustomPage(integer  $id = NULL) : mixed
```

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  |  |

**Returns:** mixed


<a name="method_displayCustomPageSelector" class="anchor"></a>
#### public displayCustomPageSelector() 

```
Static public displayCustomPageSelector() 
```

**Summary**

Displays Custom Page Selector

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)




<a name="method_getComposerExclude" class="anchor"></a>
#### public getComposerExclude() : array

```
Static public getComposerExclude() : array
```

**Summary**

Get the page composer exclude string

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)

**Returns:** array


<a name="method_displayContent" class="anchor"></a>
#### public displayContent() 

```
Static public displayContent() 
```

**Summary**

Display content

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_loadComposerData" class="anchor"></a>
#### protected loadComposerData() 

```
Static protected loadComposerData() 
```

**Summary**

Load page composer data

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)




<a name="method_cacheWidget" class="anchor"></a>
#### protected cacheWidget() : array

```
Static protected cacheWidget() : array
```

**Summary**

Cache widgets info and object

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)

**Returns:** array


<a name="method_calculateSpan" class="anchor"></a>
#### protected calculateSpan() : string

```
Static protected calculateSpan(integer  $max_column_limit) : string
```

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $max_column_limit  | Max grid count per row |

**Returns:** string


<a name="method_deleteCustomPage" class="anchor"></a>
#### protected deleteCustomPage() 

```
protected deleteCustomPage(integer  $pageid) 
```

**Summary**

SQL delete page

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $pageid  |  |




<a name="method_verifyCustomPage" class="anchor"></a>
#### protected verifyCustomPage() : boolean

```
Static protected verifyCustomPage(integer  $id) : boolean
```

**Summary**

Authenticate the page ID is valid

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  |  |

**Returns:** boolean


<a name="method_executeRowDelete" class="anchor"></a>
#### protected executeRowDelete() 

```
Static protected executeRowDelete() 
```

**Summary**

Deletes row and associated columns

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_executeRowDuplicate" class="anchor"></a>
#### protected executeRowDuplicate() 

```
Static protected executeRowDuplicate() 
```

**Summary**

Duplicate row and associated columns

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_validateRowData" class="anchor"></a>
#### protected validateRowData() 

```
Static protected validateRowData() 
```

**Summary**

Validate row data

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_executeRowUpdate" class="anchor"></a>
#### protected executeRowUpdate() 

```
Static protected executeRowUpdate() 
```

**Summary**

Execute row update

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_getColData" class="anchor"></a>
#### protected getColData() : array&amp;#124;mixed

```
Static protected getColData() : array&amp;#124;mixed
```

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)

**Returns:** array&#124;mixed


<a name="method_executeColDuplicate" class="anchor"></a>
#### protected executeColDuplicate() 

```
Static protected executeColDuplicate() 
```

**Summary**

Duplicate a Column

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_getWidgetIcon" class="anchor"></a>
#### protected getWidgetIcon() : string

```
Static protected getWidgetIcon(string  $widget_icon_path) : string
```

**Summary**

Get widget icon

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $widget_icon_path  |  |

**Returns:** string


<a name="method_drawCols" class="anchor"></a>
#### protected drawCols() 

```
Static protected drawCols(array  $colData) 
```

**Summary**

Internal Administration Column Renderer

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $colData  |  |




<a name="method_displayRowForm" class="anchor"></a>
#### private displayRowForm() 

```
Static private displayRowForm() 
```

**Summary**

Display row form

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_displayColForm" class="anchor"></a>
#### private displayColForm() 

```
Static private displayColForm() 
```

**Summary**

Widget selection menu

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)




<a name="method_displayWidgetForm" class="anchor"></a>
#### private displayWidgetForm() 

```
Static private displayWidgetForm() 
```

**Summary**

Display widget form

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\Node\ComposeEngine](../classes/PHPFusion.Page.Composer.Node.ComposeEngine.md)





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
