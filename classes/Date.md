# [PHPFusion Docs](../home.md)

# Class: \Date
### Namespace: [\](../namespaces/default.md)
---
**Summary:**

Class Date
Validates Date Input

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
* [public verify_date()](../classes/Date.md#method_verify_date)
---
### Details
* File: [defender\validation\date.php](../files/defender.validation.date.md)
* Package: Default
* Class Hierarchy: 
  * [\Defender\Validation](../classes/Defender.Validation.md)
  * \Date
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




<a name="method_verify_date" class="anchor"></a>
#### public verify_date() : integer&amp;#124;string

```
public verify_date() : integer&amp;#124;string
```

**Summary**

Check and verify submitted date
If type is timestamp, it will return a Unix timestamp
If type is date, it will return a date

**Details:**
* Inherited From: [\Date](../classes/Date.md)

**Returns:** integer&#124;string



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
