# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Page\PageController
### Namespace: [\PHPFusion\Page](../namespaces/PHPFusion.Page.md)
---
**Summary:**

Got html construct. So need to use PageView.

**Description:**

Class PageController

---
### Constants
* No constants found
---
### Properties
* [protected $adminComposerOpts](../classes/PHPFusion.Page.PageModel.md#property_adminComposerOpts)
* [protected $composerData](../classes/PHPFusion.Page.PageModel.md#property_composerData)
* [protected $widgets](../classes/PHPFusion.Page.PageModel.md#property_widgets)
* [protected $data](../classes/PHPFusion.Page.PageModel.md#property_data)
* [protected $rowData](../classes/PHPFusion.Page.PageModel.md#property_rowData)
* [protected $colData](../classes/PHPFusion.Page.PageModel.md#property_colData)
* [protected $gridData](../classes/PHPFusion.Page.PageModel.md#property_gridData)
* [protected $info](../classes/PHPFusion.Page.PageController.md#property_info)
* [private $pageInstance](../classes/PHPFusion.Page.PageModel.md#property_pageInstance)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Page.PageModel.md#method_getInstance)
* [public loadCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_loadCustomPage)
* [public queryCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_queryCustomPage)
* [public displayCustomPageSelector()](../classes/PHPFusion.Page.PageModel.md#method_displayCustomPageSelector)
* [public displayWidget()](../classes/PHPFusion.Page.PageController.md#method_displayWidget)
* [public displayContentHTML()](../classes/PHPFusion.Page.PageController.md#method_displayContentHTML)
* [protected loadComposerData()](../classes/PHPFusion.Page.PageModel.md#method_loadComposerData)
* [protected cacheWidget()](../classes/PHPFusion.Page.PageModel.md#method_cacheWidget)
* [protected calculateSpan()](../classes/PHPFusion.Page.PageModel.md#method_calculateSpan)
* [protected deleteCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_deleteCustomPage)
* [protected verifyCustomPage()](../classes/PHPFusion.Page.PageModel.md#method_verifyCustomPage)
* [protected setPageInfo()](../classes/PHPFusion.Page.PageController.md#method_setPageInfo)
---
### Details
* File: [classes\PHPFusion\Page\PageController.php](../files/classes.PHPFusion.Page.PageController.md)
* Package: PHPFusion\Page
* Class Hierarchy: 
  * [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)
  * \PHPFusion\Page\PageController
---
## Properties
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


<a name="property_info"></a>
#### protected $info : 
---
**Type:** 

**Details:**


<a name="property_pageInstance"></a>
#### private $pageInstance : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Page\PageModel](../classes/PHPFusion.Page.PageModel.md)



---
## Methods
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




<a name="method_displayWidget" class="anchor"></a>
#### public displayWidget() : mixed&amp;#124;string&amp;#124;null

```
Static public displayWidget(array  $colData) : mixed&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Page\PageController](../classes/PHPFusion.Page.PageController.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $colData  |  |

**Returns:** mixed&#124;string&#124;null


<a name="method_displayContentHTML" class="anchor"></a>
#### public displayContentHTML() : string

```
Static public displayContentHTML(array  $colData) : string
```

**Summary**

Core page content display driver

**Details:**
* Inherited From: [\PHPFusion\Page\PageController](../classes/PHPFusion.Page.PageController.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $colData  |  |

**Returns:** string


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


<a name="method_setPageInfo" class="anchor"></a>
#### protected setPageInfo() 

```
Static protected setPageInfo(integer  $page_id) 
```

**Summary**

Set page variables

**Details:**
* Inherited From: [\PHPFusion\Page\PageController](../classes/PHPFusion.Page.PageController.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $page_id  |  |





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
