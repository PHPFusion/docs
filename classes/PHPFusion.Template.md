# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Template
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

PHPFusion Template

---
### Constants
* [ DEFAULT_ID](../classes/PHPFusion.Template.md#constant_DEFAULT_ID)
---
### Properties
* [private $instance](../classes/PHPFusion.Template.md#property_instance)
* [private $template](../classes/PHPFusion.Template.md#property_template)
* [private $locale](../classes/PHPFusion.Template.md#property_locale)
* [private $block](../classes/PHPFusion.Template.md#property_block)
* [private $block_render](../classes/PHPFusion.Template.md#property_block_render)
* [private $block_source](../classes/PHPFusion.Template.md#property_block_source)
* [private $tag](../classes/PHPFusion.Template.md#property_tag)
* [private $key](../classes/PHPFusion.Template.md#property_key)
* [private $locale_list](../classes/PHPFusion.Template.md#property_locale_list)
* [private $raw_block](../classes/PHPFusion.Template.md#property_raw_block)
* [private $raw_tag](../classes/PHPFusion.Template.md#property_raw_tag)
* [private $block_count](../classes/PHPFusion.Template.md#property_block_count)
* [private $registered_templates](../classes/PHPFusion.Template.md#property_registered_templates)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Template.md#method_getInstance)
* [public set_key()](../classes/PHPFusion.Template.md#method_set_key)
* [public set_file()](../classes/PHPFusion.Template.md#method_set_file)
* [public get_block()](../classes/PHPFusion.Template.md#method_get_block)
* [public register_template()](../classes/PHPFusion.Template.md#method_register_template)
* [public set_template()](../classes/PHPFusion.Template.md#method_set_template)
* [public set_text()](../classes/PHPFusion.Template.md#method_set_text)
* [public set_locale()](../classes/PHPFusion.Template.md#method_set_locale)
* [public set_block()](../classes/PHPFusion.Template.md#method_set_block)
* [public fetch_block()](../classes/PHPFusion.Template.md#method_fetch_block)
* [public set_tag()](../classes/PHPFusion.Template.md#method_set_tag)
* [public fetch_tag()](../classes/PHPFusion.Template.md#method_fetch_tag)
* [public get_output()](../classes/PHPFusion.Template.md#method_get_output)
* [private __construct()](../classes/PHPFusion.Template.md#method___construct)
* [private __clone()](../classes/PHPFusion.Template.md#method___clone)
* [private assign_template_locales()](../classes/PHPFusion.Template.md#method_assign_template_locales)
---
### Details
* File: [classes\PHPFusion\Template.php](../files/classes.PHPFusion.Template.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Template
---
## Constants
<a name="constant_DEFAULT_ID" class="anchor"></a>
###### DEFAULT_ID
```
DEFAULT_ID = 'Default'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**


<a name="property_template"></a>
#### private $template : 
---
**Type:** 

**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_block"></a>
#### private $block : 
---
**Type:** 

**Details:**


<a name="property_block_render"></a>
#### private $block_render : 
---
**Type:** 

**Details:**


<a name="property_block_source"></a>
#### private $block_source : 
---
**Type:** 

**Details:**


<a name="property_tag"></a>
#### private $tag : 
---
**Type:** 

**Details:**


<a name="property_key"></a>
#### private $key : 
---
**Type:** 

**Details:**


<a name="property_locale_list"></a>
#### private $locale_list : 
---
**Type:** 

**Details:**


<a name="property_raw_block"></a>
#### private $raw_block : 
---
**Type:** 

**Details:**


<a name="property_raw_tag"></a>
#### private $raw_tag : 
---
**Type:** 

**Details:**


<a name="property_block_count"></a>
#### private $block_count : 
---
**Type:** 

**Details:**


<a name="property_registered_templates"></a>
#### private $registered_templates : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $key = self::DEFAULT_ID) : static
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_set_key" class="anchor"></a>
#### public set_key() 

```
Static public set_key(string  $key) 
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |




<a name="method_set_file" class="anchor"></a>
#### public set_file() 

```
public set_file(array  $folder_arr = array()) 
```

**Summary**

Set all files to be used in a template.

**Description**

There is a caveat that file names cannot be same or else it will be overridden

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $folder_arr  |  |




<a name="method_get_block" class="anchor"></a>
#### public get_block() : array

```
public get_block() : array
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)

**Returns:** array


<a name="method_register_template" class="anchor"></a>
#### public register_template() 

```
public register_template(string  $template_file_path) 
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $template_file_path  |  |




<a name="method_set_template" class="anchor"></a>
#### public set_template() 

```
public set_template(string  $template_file_path) 
```

**Summary**

Define the instance to read a specific HTML file

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $template_file_path  | Template File Source |




<a name="method_set_text" class="anchor"></a>
#### public set_text() 

```
public set_text(string  $text) 
```

**Summary**

Defines the instance to read a specific text

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  |  |




<a name="method_set_locale" class="anchor"></a>
#### public set_locale() 

```
public set_locale(array  $locales = array()) 
```

**Summary**

Defines the instance to replace locales

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $locales  |  |




<a name="method_set_block" class="anchor"></a>
#### public set_block() 

```
public set_block(string  $block_id, array  $value = array()) 
```

**Summary**

Sets to repeat on a subitem defined in the HTML markup  - {block_id.{<subitem_html>}}
This function adds a subitem for every set_block used

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $block_id  | The name of the unique block id |
| <code>array</code> | $value  | The replacements sets |




<a name="method_fetch_block" class="anchor"></a>
#### public fetch_block() : array&amp;#124;mixed&amp;#124;null

```
public fetch_block(integer  $block_id = NULL, string  $html_tag = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Summary**

Fetches an entire block of tags

**Description**

Every time this function is used with a block_id specified, it will traverse to the second count to mimic the set_block.

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $block_id  |  |
| <code>string</code> | $html_tag  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_set_tag" class="anchor"></a>
#### public set_tag() 

```
public set_tag(string  $html_tag, string  $value) 
```

**Summary**

Sets a tag to string conversion

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $html_tag  | {%tag%} in html file is 'tag' |
| <code>string</code> | $value  | the value of the string |




<a name="method_fetch_tag" class="anchor"></a>
#### public fetch_tag() : array&amp;#124;mixed&amp;#124;null

```
public fetch_tag(string  $html_tag = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Summary**

Fetches a tag

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $html_tag  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_get_output" class="anchor"></a>
#### public get_output() : string

```
public get_output() : string
```

**Summary**

Renders the output
Any unused blocks will not be parsed and deleted. This is useful to remove a div wrapper if condition fails.

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)

**Returns:** string - The final HTML markup


<a name="method___construct" class="anchor"></a>
#### private __construct() 

```
private __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)




<a name="method___clone" class="anchor"></a>
#### private __clone() 

```
private __clone() 
```

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)




<a name="method_assign_template_locales" class="anchor"></a>
#### private assign_template_locales() : array

```
private assign_template_locales(array  $array) : array
```

**Summary**

Locale Replacement with Template Macro
Macro Pattern - {[locale_keys]}
Recursively parse array into an array

**Details:**
* Inherited From: [\PHPFusion\Template](../classes/PHPFusion.Template.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |

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
