# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Page\Composer\PageComposer
### Namespace: [\PHPFusion\Page\Composer](../namespaces/PHPFusion.Page.Composer.md)
---
**Summary:**

Class PageComposer - Framework
Binds Network files

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
* [public displayContent()](../classes/PHPFusion.Page.Composer.PageComposer.md#method_displayContent)
* [protected loadComposerData()](../classes/PHPFusion.Page.PageModel.md#method_loadComposerData)
* [protected cacheWidget()](../classes/PHPFusion.Page.PageModel.md#method_cacheWidget)
* [protected calculateSpan()](../classes/PHPFusion.Page.PageModel.md#method_calculateSpan)
* [protected deleteCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_deleteCustomPage)
* [protected verifyCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_verifyCustomPage)
* [protected validatePageSql()](../classes/PHPFusion.Page.Composer.PageComposer.md#method_validatePageSql)
* [private executePageSql()](../classes/PHPFusion.Page.Composer.PageComposer.md#method_executePageSql)
* [private executePageRedirect()](../classes/PHPFusion.Page.Composer.PageComposer.md#method_executePageRedirect)
* [private composeDefaultPage()](../classes/PHPFusion.Page.Composer.PageComposer.md#method_composeDefaultPage)
---
### Details
* File: [classes\PHPFusion\Page\Composer\PageComposer.php](../files/classes.PHPFusion.Page.Composer.PageComposer.md)
* Package: Page\Composer
* Class Hierarchy:  
  * [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
  * [\PHPFusion\Page\PageAdmin](../classes/PHPFusion.Page.PageAdmin.md)
  * \PHPFusion\Page\Composer\PageComposer
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




<a name="method_displayContent" class="anchor"></a>
#### public displayContent() 

```
Static public displayContent() 
```

**Summary**

Display Composer need to echo

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\PageComposer](../classes/PHPFusion.Page.Composer.PageComposer.md)




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


<a name="method_validatePageSql" class="anchor"></a>
#### protected validatePageSql() 

```
Static protected validatePageSql() 
```

**Summary**

SQL update or save data
Composer Mode Required - pg_settings, pg_composer, pg_content

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\PageComposer](../classes/PHPFusion.Page.Composer.PageComposer.md)




<a name="method_executePageSql" class="anchor"></a>
#### private executePageSql() 

```
Static private executePageSql() 
```

**Summary**

Update/Insert and Redirect Sequence - Non Composer

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\PageComposer](../classes/PHPFusion.Page.Composer.PageComposer.md)




<a name="method_executePageRedirect" class="anchor"></a>
#### private executePageRedirect() 

```
Static private executePageRedirect() 
```

**Summary**

Execute page redirect

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\PageComposer](../classes/PHPFusion.Page.Composer.PageComposer.md)




<a name="method_composeDefaultPage" class="anchor"></a>
#### private composeDefaultPage() 

```
Static private composeDefaultPage() 
```

**Summary**

Run sync between default and composer tables

**Details:**
* Inherited From: [\PHPFusion\Page\Composer\PageComposer](../classes/PHPFusion.Page.Composer.PageComposer.md)





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
