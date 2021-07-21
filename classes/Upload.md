# [PHPFusion Docs](../home.md)

# Class: \Upload
### Namespace: [\](../namespaces/default.md)
---
**Summary:**

Class Upload
Handles file or image uploads validation

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
* [protected verify_file_upload()](../classes/Upload.md#method_verify_file_upload)
* [protected verify_image_upload()](../classes/Upload.md#method_verify_image_upload)
* [private in_array_insensitive()](../classes/Upload.md#method_in_array_insensitive)
* [private setError()](../classes/Upload.md#method_setError)
---
### Details
* File: [defender\validation\upload.php](../files/defender.validation.upload.md)
* Package: Default
* Class Hierarchy: 
  * [\Defender\Validation](../classes/Defender.Validation.md)
  * \Upload
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




<a name="method_verify_file_upload" class="anchor"></a>
#### protected verify_file_upload() 

```
protected verify_file_upload() 
```

**Details:**
* Inherited From: [\Upload](../classes/Upload.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| noinspection |  | PhpInconsistentReturnPointsInspection |

<a name="method_verify_image_upload" class="anchor"></a>
#### protected verify_image_upload() : array

```
protected verify_image_upload() : array
```

**Summary**

Verify Image Upload

**Details:**
* Inherited From: [\Upload](../classes/Upload.md)

**Returns:** array


<a name="method_in_array_insensitive" class="anchor"></a>
#### private in_array_insensitive() 

```
private in_array_insensitive(  $needle,   $haystack) 
```

**Details:**
* Inherited From: [\Upload](../classes/Upload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $needle  |  |
| <code></code> | $haystack  |  |




<a name="method_setError" class="anchor"></a>
#### private setError() : string

```
private setError(  $error_code) : string
```

**Details:**
* Inherited From: [\Upload](../classes/Upload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $error_code  |  |

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
