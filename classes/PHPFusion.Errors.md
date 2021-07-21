# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Errors
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Errors
PHPFusion Error Handling

---
### Constants
* [ E_ERROR](../classes/PHPFusion.Errors.md#constant_E_ERROR)
* [ E_WARNING](../classes/PHPFusion.Errors.md#constant_E_WARNING)
* [ E_PARSE](../classes/PHPFusion.Errors.md#constant_E_PARSE)
* [ E_NOTICE](../classes/PHPFusion.Errors.md#constant_E_NOTICE)
* [ E_CORE_ERROR](../classes/PHPFusion.Errors.md#constant_E_CORE_ERROR)
* [ E_CORE_WARNING](../classes/PHPFusion.Errors.md#constant_E_CORE_WARNING)
* [ E_COMPILE_ERROR](../classes/PHPFusion.Errors.md#constant_E_COMPILE_ERROR)
* [ E_COMPILE_WARNING](../classes/PHPFusion.Errors.md#constant_E_COMPILE_WARNING)
* [ E_USER_ERROR](../classes/PHPFusion.Errors.md#constant_E_USER_ERROR)
* [ E_USER_WARNING](../classes/PHPFusion.Errors.md#constant_E_USER_WARNING)
* [ E_USER_NOTICE](../classes/PHPFusion.Errors.md#constant_E_USER_NOTICE)
* [ E_ALL](../classes/PHPFusion.Errors.md#constant_E_ALL)
* [ E_STRICT](../classes/PHPFusion.Errors.md#constant_E_STRICT)
---
### Properties
* [public $no_notice](../classes/PHPFusion.Errors.md#property_no_notice)
* [public $compressed](../classes/PHPFusion.Errors.md#property_compressed)
* [private $instances](../classes/PHPFusion.Errors.md#property_instances)
* [private $locale](../classes/PHPFusion.Errors.md#property_locale)
* [private $error_status](../classes/PHPFusion.Errors.md#property_error_status)
* [private $posted_error_id](../classes/PHPFusion.Errors.md#property_posted_error_id)
* [private $delete_status](../classes/PHPFusion.Errors.md#property_delete_status)
* [private $rows](../classes/PHPFusion.Errors.md#property_rows)
* [private $rowstart](../classes/PHPFusion.Errors.md#property_rowstart)
* [private $error_id](../classes/PHPFusion.Errors.md#property_error_id)
* [private $errors](../classes/PHPFusion.Errors.md#property_errors)
* [private $new_errors](../classes/PHPFusion.Errors.md#property_new_errors)
---
### Methods
* [public __construct()](../classes/PHPFusion.Errors.md#method___construct)
* [public getInstance()](../classes/PHPFusion.Errors.md#method_getInstance)
* [public setError()](../classes/PHPFusion.Errors.md#method_setError)
* [public displayAdministration()](../classes/PHPFusion.Errors.md#method_displayAdministration)
* [public showFooterErrors()](../classes/PHPFusion.Errors.md#method_showFooterErrors)
* [private showErrorRows()](../classes/PHPFusion.Errors.md#method_showErrorRows)
* [private getErrorLogs()](../classes/PHPFusion.Errors.md#method_getErrorLogs)
* [private getErrorLogTypes()](../classes/PHPFusion.Errors.md#method_getErrorLogTypes)
* [private getMaxFolders()](../classes/PHPFusion.Errors.md#method_getMaxFolders)
* [private getErrorTypes()](../classes/PHPFusion.Errors.md#method_getErrorTypes)
* [private errorJs()](../classes/PHPFusion.Errors.md#method_errorJs)
* [private printCode()](../classes/PHPFusion.Errors.md#method_printCode)
* [private codeWrap()](../classes/PHPFusion.Errors.md#method_codeWrap)
---
### Details
* File: [classes\PHPFusion\Errors.php](../files/classes.PHPFusion.Errors.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Errors
---
## Constants
<a name="constant_E_ERROR" class="anchor"></a>
###### E_ERROR
```
E_ERROR = 1
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_WARNING" class="anchor"></a>
###### E_WARNING
```
E_WARNING = 2
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_PARSE" class="anchor"></a>
###### E_PARSE
```
E_PARSE = 4
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_NOTICE" class="anchor"></a>
###### E_NOTICE
```
E_NOTICE = 8
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_CORE_ERROR" class="anchor"></a>
###### E_CORE_ERROR
```
E_CORE_ERROR = 16
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_CORE_WARNING" class="anchor"></a>
###### E_CORE_WARNING
```
E_CORE_WARNING = 32
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_COMPILE_ERROR" class="anchor"></a>
###### E_COMPILE_ERROR
```
E_COMPILE_ERROR = 64
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_COMPILE_WARNING" class="anchor"></a>
###### E_COMPILE_WARNING
```
E_COMPILE_WARNING = 128
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_USER_ERROR" class="anchor"></a>
###### E_USER_ERROR
```
E_USER_ERROR = 256
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_USER_WARNING" class="anchor"></a>
###### E_USER_WARNING
```
E_USER_WARNING = 512
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_USER_NOTICE" class="anchor"></a>
###### E_USER_NOTICE
```
E_USER_NOTICE = 1024
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_ALL" class="anchor"></a>
###### E_ALL
```
E_ALL = 2047
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_E_STRICT" class="anchor"></a>
###### E_STRICT
```
E_STRICT = 2048
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_no_notice"></a>
#### public $no_notice : 
---
**Type:** 

**Details:**


<a name="property_compressed"></a>
#### public $compressed : 
---
**Type:** 

**Details:**


<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_error_status"></a>
#### private $error_status : 
---
**Type:** 

**Details:**


<a name="property_posted_error_id"></a>
#### private $posted_error_id : 
---
**Type:** 

**Details:**


<a name="property_delete_status"></a>
#### private $delete_status : 
---
**Type:** 

**Details:**


<a name="property_rows"></a>
#### private $rows : 
---
**Type:** 

**Details:**


<a name="property_rowstart"></a>
#### private $rowstart : 
---
**Type:** 

**Details:**


<a name="property_error_id"></a>
#### private $error_id : 
---
**Type:** 

**Details:**


<a name="property_errors"></a>
#### private $errors : 
---
**Type:** 

**Details:**


<a name="property_new_errors"></a>
#### private $new_errors : 
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
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $key = &#039;default&#039;) : static
```

**Summary**

Get an instance by key

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_setError" class="anchor"></a>
#### public setError() 

```
public setError(integer  $error_level, string  $error_message, string  $error_file, integer  $error_line) 
```

**Summary**

Custom error handler for PHP processor

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $error_level  | Severity |
| <code>string</code> | $error_message  | $e->message |
| <code>string</code> | $error_file  | The file in question, run a debug_backtrace()[2] in the file |
| <code>integer</code> | $error_line  | The line in question, run a debug_backtrace()[2] in the file |




<a name="method_displayAdministration" class="anchor"></a>
#### public displayAdministration() 

```
public displayAdministration() 
```

**Summary**

Administration Console

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)




<a name="method_showFooterErrors" class="anchor"></a>
#### public showFooterErrors() 

```
public showFooterErrors() 
```

**Summary**

Use this function to show error logs

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)




<a name="method_showErrorRows" class="anchor"></a>
#### private showErrorRows() : string

```
private showErrorRows(array  $data) : string
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  |  |

**Returns:** string


<a name="method_getErrorLogs" class="anchor"></a>
#### private getErrorLogs() : string

```
private getErrorLogs() : string
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)

**Returns:** string


<a name="method_getErrorLogTypes" class="anchor"></a>
#### private getErrorLogTypes() : array

```
private getErrorLogTypes() : array
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)

**Returns:** array


<a name="method_getMaxFolders" class="anchor"></a>
#### private getMaxFolders() : string

```
private getMaxFolders(string  $url, integer  $level = 2) : string
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  |  |
| <code>integer</code> | $level  |  |

**Returns:** string


<a name="method_getErrorTypes" class="anchor"></a>
#### private getErrorTypes() : false&amp;#124;mixed

```
private getErrorTypes(integer  $type) : false&amp;#124;mixed
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $type  |  |

**Returns:** false&#124;mixed


<a name="method_errorJs" class="anchor"></a>
#### private errorJs() 

```
private errorJs() 
```

**Summary**

JS code

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)




<a name="method_printCode" class="anchor"></a>
#### private printCode() : false&amp;#124;string

```
private printCode(string  $source_code, integer  $starting_line, string  $error_line = &quot;&quot;, array  $error_message = array(), null  $title = NULL) : false&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source_code  |  |
| <code>integer</code> | $starting_line  |  |
| <code>string</code> | $error_line  |  |
| <code>array</code> | $error_message  |  |
| <code>null</code> | $title  |  |

**Returns:** false&#124;string


<a name="method_codeWrap" class="anchor"></a>
#### private codeWrap() : string

```
private codeWrap(string  $code, integer  $maxLength = 150) : string
```

**Details:**
* Inherited From: [\PHPFusion\Errors](../classes/PHPFusion.Errors.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $code  |  |
| <code>integer</code> | $maxLength  |  |

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
