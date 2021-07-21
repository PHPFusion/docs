# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\OutputHandler
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
---
### Constants
* No constants found
---
### Properties
* [public $pageHeadTags](../classes/PHPFusion.OutputHandler.md#property_pageHeadTags)
* [public $pageFooterTags](../classes/PHPFusion.OutputHandler.md#property_pageFooterTags)
* [public $jqueryTags](../classes/PHPFusion.OutputHandler.md#property_jqueryTags)
* [public $cssTags](../classes/PHPFusion.OutputHandler.md#property_cssTags)
* [public $pageTitle](../classes/PHPFusion.OutputHandler.md#property_pageTitle)
* [private $pageMeta](../classes/PHPFusion.OutputHandler.md#property_pageMeta)
* [private $outputHandlers](../classes/PHPFusion.OutputHandler.md#property_outputHandlers)
---
### Methods
* [public setTitle()](../classes/PHPFusion.OutputHandler.md#method_setTitle)
* [public addToTitle()](../classes/PHPFusion.OutputHandler.md#method_addToTitle)
* [public setMeta()](../classes/PHPFusion.OutputHandler.md#method_setMeta)
* [public addToMeta()](../classes/PHPFusion.OutputHandler.md#method_addToMeta)
* [public addToHead()](../classes/PHPFusion.OutputHandler.md#method_addToHead)
* [public addToFooter()](../classes/PHPFusion.OutputHandler.md#method_addToFooter)
* [public replaceInOutput()](../classes/PHPFusion.OutputHandler.md#method_replaceInOutput)
* [public addHandler()](../classes/PHPFusion.OutputHandler.md#method_addHandler)
* [public addToJQuery()](../classes/PHPFusion.OutputHandler.md#method_addToJQuery)
* [public addToCss()](../classes/PHPFusion.OutputHandler.md#method_addToCss)
* [public getTitle()](../classes/PHPFusion.OutputHandler.md#method_getTitle)
* [public handleOutput()](../classes/PHPFusion.OutputHandler.md#method_handleOutput)
---
### Details
* File: [classes\PHPFusion\OutputHandler.php](../files/classes.PHPFusion.OutputHandler.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\OutputHandler
---
## Properties
<a name="property_pageHeadTags"></a>
#### public $pageHeadTags : string
---
**Summary**

Additional tags to the html head

**Type:** string

**Details:**


<a name="property_pageFooterTags"></a>
#### public $pageFooterTags : string
---
**Summary**

Additional contents to the footer

**Type:** string

**Details:**


<a name="property_jqueryTags"></a>
#### public $jqueryTags : string
---
**Summary**

Additional javascripts

**Type:** string

**Details:**


<a name="property_cssTags"></a>
#### public $cssTags : string
---
**Summary**

Additional css

**Type:** string

**Details:**


<a name="property_pageTitle"></a>
#### public $pageTitle : string
---
**Summary**

The title in the "title" tag

**Type:** string

**Details:**


<a name="property_pageMeta"></a>
#### private $pageMeta : array&lt;mixed,string&gt;
---
**Summary**

Associative array of meta tags

**Type:** array&lt;mixed,string&gt;

**Details:**


<a name="property_outputHandlers"></a>
#### private $outputHandlers : array&lt;mixed,callback&gt;
---
**Summary**

PHP code to execute using eval replace anything in the output

**Type:** array&lt;mixed,callback&gt;

**Details:**



---
## Methods
<a name="method_setTitle" class="anchor"></a>
#### public setTitle() 

```
Static public setTitle(string  $title = &quot;&quot;) 
```

**Summary**

Set the new title of the page

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $title  |  |




<a name="method_addToTitle" class="anchor"></a>
#### public addToTitle() 

```
Static public addToTitle(string  $addition = &quot;&quot;) 
```

**Summary**

Append something to the title of the page

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $addition  |  |




<a name="method_setMeta" class="anchor"></a>
#### public setMeta() 

```
Static public setMeta(string  $name, string  $content = &quot;&quot;) 
```

**Summary**

Set a meta tag by name

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>string</code> | $content  |  |




<a name="method_addToMeta" class="anchor"></a>
#### public addToMeta() 

```
Static public addToMeta(string  $name, string  $addition = &quot;&quot;) 
```

**Summary**

Append something to a meta tag

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>string</code> | $addition  |  |




<a name="method_addToHead" class="anchor"></a>
#### public addToHead() 

```
Static public addToHead(string  $tag = &quot;&quot;) 
```

**Summary**

Add content to the html head

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |




<a name="method_addToFooter" class="anchor"></a>
#### public addToFooter() 

```
Static public addToFooter(string  $tag = &quot;&quot;) 
```

**Summary**

Add content to the footer

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |




<a name="method_replaceInOutput" class="anchor"></a>
#### public replaceInOutput() 

```
Static public replaceInOutput(string  $target, string  $replace, string  $modifiers = &quot;&quot;) 
```

**Summary**

Replace something in the output using regexp

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $target  | Regexp pattern without delimiters |
| <code>string</code> | $replace  | The new content |
| <code>string</code> | $modifiers  | Regexp modifiers |




<a name="method_addHandler" class="anchor"></a>
#### public addHandler() 

```
Static public addHandler(callback  $callback) 
```

**Summary**

Add a new output handler function

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>callback</code> | $callback  | The name of a function or other callable object |




<a name="method_addToJQuery" class="anchor"></a>
#### public addToJQuery() 

```
Static public addToJQuery(string  $tag = &quot;&quot;) 
```

**Summary**

Add javascript source code to the output

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |




<a name="method_addToCss" class="anchor"></a>
#### public addToCss() 

```
Static public addToCss(string  $tag = &quot;&quot;) 
```

**Summary**

Add css code to the output

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |




<a name="method_getTitle" class="anchor"></a>
#### public getTitle() 

```
Static public getTitle() 
```

**Summary**

Get Current Page Title

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)




<a name="method_handleOutput" class="anchor"></a>
#### public handleOutput() : string

```
Static public handleOutput(string  $output) : string
```

**Summary**

Execute the output handlers

**Details:**
* Inherited From: [\PHPFusion\OutputHandler](../classes/PHPFusion.OutputHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $output  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| global |  | array $locale |


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
