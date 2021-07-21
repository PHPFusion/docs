# [PHPFusion Docs](../home.md)

# Class: \Uri
### Namespace: [\](../namespaces/default.md)
---
**Summary:**

Class Uri
Validates URL Input

---
### Constants
* No constants found
---
### Properties
* [protected $inputName](../classes/Defender.Validation.md#property_inputName)
* [protected $inputValue](../classes/Defender.Validation.md#property_inputValue)
* [protected $inputDefault](../classes/Defender.Validation.md#property_inputDefault)
* [protected $isMultiLang](../classes/Defender.Validation.md#property_isMultiLang)
* [protected $inputConfig](../classes/Defender.Validation.md#property_inputConfig)
* [protected $validate_instance](../classes/Defender.Validation.md#property_validate_instance)
* [protected $validate_method](../classes/Defender.Validation.md#property_validate_method)
* [protected $validation_rules_assigned](../classes/Defender.Validation.md#property_validation_rules_assigned)
---
### Methods
* [public inputName()](../classes/Defender.Validation.md#method_inputName)
* [public inputConfig()](../classes/Defender.Validation.md#method_inputConfig)
* [public inputValue()](../classes/Defender.Validation.md#method_inputValue)
* [public inputDefault()](../classes/Defender.Validation.md#method_inputDefault)
* [public isMultilang()](../classes/Defender.Validation.md#method_isMultilang)
* [public getValidated()](../classes/Defender.Validation.md#method_getValidated)
* [public verify_path()](../classes/Uri.md#method_verify_path)
* [protected verify_URL()](../classes/Uri.md#method_verify_URL)
* [protected validateURL()](../classes/Uri.md#method_validateURL)
---
### Details
* File: [defender\validation\uri.php](../files/defender.validation.uri.md)
* Package: Default
* Class Hierarchy: 
  * [\Defender\Validation](../classes/Defender.Validation.md)
  * \Uri
---
## Properties
<a name="property_inputName"></a>
#### protected $inputName : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_inputValue"></a>
#### protected $inputValue : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_inputDefault"></a>
#### protected $inputDefault : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_isMultiLang"></a>
#### protected $isMultiLang : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_inputConfig"></a>
#### protected $inputConfig : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_validate_instance"></a>
#### protected $validate_instance : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_validate_method"></a>
#### protected $validate_method : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)


<a name="property_validation_rules_assigned"></a>
#### protected $validation_rules_assigned : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)



---
## Methods
<a name="method_inputName" class="anchor"></a>
#### public inputName() 

```
Static public inputName(  $value = NULL) 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_inputConfig" class="anchor"></a>
#### public inputConfig() 

```
Static public inputConfig(  $value = NULL) 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_inputValue" class="anchor"></a>
#### public inputValue() 

```
Static public inputValue(  $value = NULL) 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_inputDefault" class="anchor"></a>
#### public inputDefault() 

```
Static public inputDefault(  $value = NULL) 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_isMultilang" class="anchor"></a>
#### public isMultilang() 

```
Static public isMultilang(  $value = NULL) 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_getValidated" class="anchor"></a>
#### public getValidated() 

```
Static public getValidated() 
```

**Details:**
* Inherited From: [\Defender\Validation](../classes/Defender.Validation.md)




<a name="method_verify_path" class="anchor"></a>
#### public verify_path() : boolean&amp;#124;string

```
public verify_path() : boolean&amp;#124;string
```

**Summary**

Verify Paths within CMS

**Details:**
* Inherited From: [\Uri](../classes/Uri.md)

**Returns:** boolean&#124;string


<a name="method_verify_URL" class="anchor"></a>
#### protected verify_URL() 

```
protected verify_URL() 
```

**Summary**

Checks if is a valid URL
require path.

**Description**

returns str the input or bool FALSE if check fails

**Details:**
* Inherited From: [\Uri](../classes/Uri.md)




<a name="method_validateURL" class="anchor"></a>
#### protected validateURL() : boolean

```
Static protected validateURL(  $url) : boolean
```

**Summary**

Validate URL

**Details:**
* Inherited From: [\Uri](../classes/Uri.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $url  |  |

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
