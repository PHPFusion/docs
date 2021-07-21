# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Search\Search_Engine
### Namespace: [\PHPFusion\Search](../namespaces/PHPFusion.Search.md)
---
**Summary:**

Class Search_Model

---
### Constants
* No constants found
---
### Properties
* [public $locale](../classes/PHPFusion.Search.Search_Engine.md#property_locale)
* [protected $available_modules](../classes/PHPFusion.Search.Search_Model.md#property_available_modules)
* [protected $form_config](../classes/PHPFusion.Search.Search_Model.md#property_form_config)
* [protected $search_result_array](../classes/PHPFusion.Search.Search_Model.md#property_search_result_array)
* [protected $site_search_count](../classes/PHPFusion.Search.Search_Model.md#property_site_search_count)
* [protected $navigation_result](../classes/PHPFusion.Search.Search_Model.md#property_navigation_result)
* [protected $items_count](../classes/PHPFusion.Search.Search_Model.md#property_items_count)
* [protected $global_string_count](../classes/PHPFusion.Search.Search_Model.md#property_global_string_count)
* [protected $memory_limit](../classes/PHPFusion.Search.Search_Model.md#property_memory_limit)
* [protected $memory_exhausted](../classes/PHPFusion.Search.Search_Model.md#property_memory_exhausted)
* [protected $fields_count](../classes/PHPFusion.Search.Search_Model.md#property_fields_count)
* [protected $swords](../classes/PHPFusion.Search.Search_Model.md#property_swords)
* [protected $c_swords](../classes/PHPFusion.Search.Search_Model.md#property_c_swords)
* [protected $i_swords](../classes/PHPFusion.Search.Search_Model.md#property_i_swords)
* [protected $swords_keys_for_query](../classes/PHPFusion.Search.Search_Model.md#property_swords_keys_for_query)
* [protected $swords_values_for_query](../classes/PHPFusion.Search.Search_Model.md#property_swords_values_for_query)
* [protected $conditions](../classes/PHPFusion.Search.Search_Model.md#property_conditions)
* [protected $fieldsvar](../classes/PHPFusion.Search.Search_Model.md#property_fieldsvar)
* [protected $rowstart](../classes/PHPFusion.Search.Search_Model.md#property_rowstart)
* [protected $search_text](../classes/PHPFusion.Search.Search_Model.md#property_search_text)
* [protected $search_method](../classes/PHPFusion.Search.Search_Model.md#property_search_method)
* [protected $search_date_limit](../classes/PHPFusion.Search.Search_Model.md#property_search_date_limit)
* [protected $search_fields](../classes/PHPFusion.Search.Search_Model.md#property_search_fields)
* [protected $search_sort](../classes/PHPFusion.Search.Search_Model.md#property_search_sort)
* [protected $search_order](../classes/PHPFusion.Search.Search_Model.md#property_search_order)
* [protected $search_chars](../classes/PHPFusion.Search.Search_Model.md#property_search_chars)
* [protected $forum_id](../classes/PHPFusion.Search.Search_Model.md#property_forum_id)
* [protected $search_type](../classes/PHPFusion.Search.Search_Model.md#property_search_type)
* [protected $search_param](../classes/PHPFusion.Search.Search_Model.md#property_search_param)
* [protected $composevars](../classes/PHPFusion.Search.Search_Model.md#property_composevars)
* [protected $search_instance](../classes/PHPFusion.Search.Search_Engine.md#property_search_instance)
* [protected $render_search](../classes/PHPFusion.Search.Search_Engine.md#property_render_search)
* [protected $search_no_result](../classes/PHPFusion.Search.Search_Engine.md#property_search_no_result)
* [protected $search_count](../classes/PHPFusion.Search.Search_Engine.md#property_search_count)
* [protected $search_item_wrapper](../classes/PHPFusion.Search.Search_Engine.md#property_search_item_wrapper)
* [protected $search_item](../classes/PHPFusion.Search.Search_Engine.md#property_search_item)
* [protected $search_item_list](../classes/PHPFusion.Search.Search_Engine.md#property_search_item_list)
* [protected $search_item_image](../classes/PHPFusion.Search.Search_Engine.md#property_search_item_image)
* [private $search_index](../classes/PHPFusion.Search.Search_Model.md#property_search_index)
* [private $search_mod](../classes/PHPFusion.Search.Search_Model.md#property_search_mod)
---
### Methods
* [public append_item_count()](../classes/PHPFusion.Search.Search_Model.md#method_append_item_count)
* [public search_striphtmlbbcodes()](../classes/PHPFusion.Search.Search_Model.md#method_search_striphtmlbbcodes)
* [public search_textfrag()](../classes/PHPFusion.Search.Search_Model.md#method_search_textfrag)
* [public search_stringscount()](../classes/PHPFusion.Search.Search_Model.md#method_search_stringscount)
* [public search_column()](../classes/PHPFusion.Search.Search_Model.md#method_search_column)
* [public search_conditions()](../classes/PHPFusion.Search.Search_Model.md#method_search_conditions)
* [public search_navigation()](../classes/PHPFusion.Search.Search_Model.md#method_search_navigation)
* [public search_globalarray()](../classes/PHPFusion.Search.Search_Model.md#method_search_globalarray)
* [public searchRequest()](../classes/PHPFusion.Search.Search_Model.md#method_searchRequest)
* [public load_search_modules()](../classes/PHPFusion.Search.Search_Model.md#method_load_search_modules)
* [public getInstance()](../classes/PHPFusion.Search.Search_Engine.md#method_getInstance)
* [public get_param()](../classes/PHPFusion.Search.Search_Engine.md#method_get_param)
* [protected __construct()](../classes/PHPFusion.Search.Search_Engine.md#method___construct)
* [protected init()](../classes/PHPFusion.Search.Search_Model.md#method_init)
* [protected cache_modules()](../classes/PHPFusion.Search.Search_Model.md#method_cache_modules)
* [protected displaySearchForm()](../classes/PHPFusion.Search.Search_Engine.md#method_displaySearchForm)
* [protected displayResults()](../classes/PHPFusion.Search.Search_Engine.md#method_displayResults)
* [protected loadDriver()](../classes/PHPFusion.Search.Search_Engine.md#method_loadDriver)
* [protected displayNoResults()](../classes/PHPFusion.Search.Search_Engine.md#method_displayNoResults)
* [private __clone()](../classes/PHPFusion.Search.Search_Engine.md#method___clone)
---
### Details
* File: [classes\PHPFusion\Search\Search_Engine.php](../files/classes.PHPFusion.Search.Search_Engine.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
  * \PHPFusion\Search\Search_Engine
---
## Properties
<a name="property_locale"></a>
#### public $locale : 
---
**Type:** 

**Details:**


<a name="property_available_modules"></a>
#### protected $available_modules : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_form_config"></a>
#### protected $form_config : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_result_array"></a>
#### protected $search_result_array : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_site_search_count"></a>
#### protected $site_search_count : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_navigation_result"></a>
#### protected $navigation_result : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_items_count"></a>
#### protected $items_count : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_global_string_count"></a>
#### protected $global_string_count : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_memory_limit"></a>
#### protected $memory_limit : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_memory_exhausted"></a>
#### protected $memory_exhausted : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_fields_count"></a>
#### protected $fields_count : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_swords"></a>
#### protected $swords : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_c_swords"></a>
#### protected $c_swords : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_i_swords"></a>
#### protected $i_swords : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_swords_keys_for_query"></a>
#### protected $swords_keys_for_query : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_swords_values_for_query"></a>
#### protected $swords_values_for_query : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_conditions"></a>
#### protected $conditions : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_fieldsvar"></a>
#### protected $fieldsvar : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_rowstart"></a>
#### protected $rowstart : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_text"></a>
#### protected $search_text : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_method"></a>
#### protected $search_method : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_date_limit"></a>
#### protected $search_date_limit : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_fields"></a>
#### protected $search_fields : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_sort"></a>
#### protected $search_sort : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_order"></a>
#### protected $search_order : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_chars"></a>
#### protected $search_chars : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_forum_id"></a>
#### protected $forum_id : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_type"></a>
#### protected $search_type : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_param"></a>
#### protected $search_param : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_composevars"></a>
#### protected $composevars : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_instance"></a>
#### protected $search_instance : 
---
**Type:** 

**Details:**


<a name="property_render_search"></a>
#### protected $render_search : 
---
**Type:** 

**Details:**


<a name="property_search_no_result"></a>
#### protected $search_no_result : 
---
**Type:** 

**Details:**


<a name="property_search_count"></a>
#### protected $search_count : 
---
**Type:** 

**Details:**


<a name="property_search_item_wrapper"></a>
#### protected $search_item_wrapper : 
---
**Type:** 

**Details:**


<a name="property_search_item"></a>
#### protected $search_item : 
---
**Type:** 

**Details:**


<a name="property_search_item_list"></a>
#### protected $search_item_list : 
---
**Type:** 

**Details:**


<a name="property_search_item_image"></a>
#### protected $search_item_image : 
---
**Type:** 

**Details:**


<a name="property_search_index"></a>
#### private $search_index : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)


<a name="property_search_mod"></a>
#### private $search_mod : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)



---
## Methods
<a name="method_append_item_count" class="anchor"></a>
#### public append_item_count() 

```
Static public append_item_count(  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_search_striphtmlbbcodes" class="anchor"></a>
#### public search_striphtmlbbcodes() 

```
Static public search_striphtmlbbcodes(  $text) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $text  |  |




<a name="method_search_textfrag" class="anchor"></a>
#### public search_textfrag() 

```
Static public search_textfrag(  $text) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $text  |  |




<a name="method_search_stringscount" class="anchor"></a>
#### public search_stringscount() 

```
Static public search_stringscount(  $text) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $text  |  |




<a name="method_search_column" class="anchor"></a>
#### public search_column() 

```
Static public search_column(  $field,   $field_module) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $field  |  |
| <code></code> | $field_module  |  |




<a name="method_search_conditions" class="anchor"></a>
#### public search_conditions() 

```
Static public search_conditions(  $field_module) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $field_module  |  |




<a name="method_search_navigation" class="anchor"></a>
#### public search_navigation() 

```
Static public search_navigation(  $rows) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $rows  |  |




<a name="method_search_globalarray" class="anchor"></a>
#### public search_globalarray() 

```
Static public search_globalarray(  $search_result) 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $search_result  |  |




<a name="method_searchRequest" class="anchor"></a>
#### public searchRequest() : string

```
public searchRequest(string  $key, integer  $flags = FILTER_DEFAULT) : string
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>integer</code> | $flags  |  |

**Returns:** string


<a name="method_load_search_modules" class="anchor"></a>
#### public load_search_modules() 

```
public load_search_modules() 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Returns the search engine instance

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)

**Returns:** null&#124;static


<a name="method_get_param" class="anchor"></a>
#### public get_param() : array&amp;#124;string

```
Static public get_param(string  $key = NULL) : array&amp;#124;string
```

**Summary**

Returns params

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array&#124;string


<a name="method___construct" class="anchor"></a>
#### protected __construct() 

```
protected __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)




<a name="method_init" class="anchor"></a>
#### protected init() 

```
protected init() 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)




<a name="method_cache_modules" class="anchor"></a>
#### protected cache_modules() 

```
protected cache_modules() 
```

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Model](../classes/PHPFusion.Search.Search_Model.md)




<a name="method_displaySearchForm" class="anchor"></a>
#### protected displaySearchForm() 

```
Static protected displaySearchForm() 
```

**Summary**

Controller for search form

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)




<a name="method_displayResults" class="anchor"></a>
#### protected displayResults() 

```
Static protected displayResults() 
```

**Summary**

Controller for display the search results

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)




<a name="method_loadDriver" class="anchor"></a>
#### protected loadDriver() 

```
Static protected loadDriver(string  $path) 
```

**Summary**

Load the search driver file
- Prevents string mutation

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $path  |  |




<a name="method_displayNoResults" class="anchor"></a>
#### protected displayNoResults() 

```
Static protected displayNoResults() 
```

**Summary**

Controller for omitting search

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)




<a name="method___clone" class="anchor"></a>
#### private __clone() 

```
private __clone() 
```

**Summary**

Prevents class cloning

**Details:**
* Inherited From: [\PHPFusion\Search\Search_Engine](../classes/PHPFusion.Search.Search_Engine.md)





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
