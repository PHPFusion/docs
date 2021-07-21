# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\UserFieldsInput
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class UserFieldsInput

---
### Constants
* No constants found
---
### Properties
* [public $adminActivation](../classes/PHPFusion.UserFieldsInput.md#property_adminActivation)
* [public $emailVerification](../classes/PHPFusion.UserFieldsInput.md#property_emailVerification)
* [public $verifyNewEmail](../classes/PHPFusion.UserFieldsInput.md#property_verifyNewEmail)
* [public $userData](../classes/PHPFusion.UserFieldsInput.md#property_userData)
* [public $validation](../classes/PHPFusion.UserFieldsInput.md#property_validation)
* [public $registration](../classes/PHPFusion.UserFieldsInput.md#property_registration)
* [public $skipCurrentPass](../classes/PHPFusion.UserFieldsInput.md#property_skipCurrentPass)
* [public $isAdminPanel](../classes/PHPFusion.UserFieldsInput.md#property_isAdminPanel)
* [private $_completeMessage](../classes/PHPFusion.UserFieldsInput.md#property__completeMessage)
* [private $_method](../classes/PHPFusion.UserFieldsInput.md#property__method)
* [private $_userEmail](../classes/PHPFusion.UserFieldsInput.md#property__userEmail)
* [private $_userName](../classes/PHPFusion.UserFieldsInput.md#property__userName)
* [private $data](../classes/PHPFusion.UserFieldsInput.md#property_data)
* [private $_isValidCurrentPassword](../classes/PHPFusion.UserFieldsInput.md#property__isValidCurrentPassword)
* [private $_newUserPassword](../classes/PHPFusion.UserFieldsInput.md#property__newUserPassword)
* [private $_newUserPassword2](../classes/PHPFusion.UserFieldsInput.md#property__newUserPassword2)
* [private $username_change](../classes/PHPFusion.UserFieldsInput.md#property_username_change)
* [private $_themeChanged](../classes/PHPFusion.UserFieldsInput.md#property__themeChanged)
---
### Methods
* [public saveInsert()](../classes/PHPFusion.UserFieldsInput.md#method_saveInsert)
* [public saveUpdate()](../classes/PHPFusion.UserFieldsInput.md#method_saveUpdate)
* [public getData()](../classes/PHPFusion.UserFieldsInput.md#method_getData)
* [public setUserNameChange()](../classes/PHPFusion.UserFieldsInput.md#method_setUserNameChange)
* [public verifyCode()](../classes/PHPFusion.UserFieldsInput.md#method_verifyCode)
* [public themeChanged()](../classes/PHPFusion.UserFieldsInput.md#method_themeChanged)
* [private setEmptyFields()](../classes/PHPFusion.UserFieldsInput.md#method_setEmptyFields)
* [private setUserName()](../classes/PHPFusion.UserFieldsInput.md#method_setUserName)
* [private setPassword()](../classes/PHPFusion.UserFieldsInput.md#method_setPassword)
* [private getPasswordInput()](../classes/PHPFusion.UserFieldsInput.md#method_getPasswordInput)
* [private setUserEmail()](../classes/PHPFusion.UserFieldsInput.md#method_setUserEmail)
* [private verifyNewEmail()](../classes/PHPFusion.UserFieldsInput.md#method_verifyNewEmail)
* [private setValidationError()](../classes/PHPFusion.UserFieldsInput.md#method_setValidationError)
* [private setEmailVerification()](../classes/PHPFusion.UserFieldsInput.md#method_setEmailVerification)
* [private setAdminPassword()](../classes/PHPFusion.UserFieldsInput.md#method_setAdminPassword)
* [private setUserAvatar()](../classes/PHPFusion.UserFieldsInput.md#method_setUserAvatar)
* [private verifyEmailPass()](../classes/PHPFusion.UserFieldsInput.md#method_verifyEmailPass)
---
### Details
* File: [classes\PHPFusion\UserFieldsInput.php](../files/classes.PHPFusion.UserFieldsInput.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\UserFieldsInput
---
## Properties
<a name="property_adminActivation"></a>
#### public $adminActivation : 
---
**Type:** 

**Details:**


<a name="property_emailVerification"></a>
#### public $emailVerification : 
---
**Type:** 

**Details:**


<a name="property_verifyNewEmail"></a>
#### public $verifyNewEmail : 
---
**Type:** 

**Details:**


<a name="property_userData"></a>
#### public $userData : 
---
**Type:** 

**Details:**


<a name="property_validation"></a>
#### public $validation : 
---
**Type:** 

**Details:**


<a name="property_registration"></a>
#### public $registration : 
---
**Type:** 

**Details:**


<a name="property_skipCurrentPass"></a>
#### public $skipCurrentPass : 
---
**Type:** 

**Details:**


<a name="property_isAdminPanel"></a>
#### public $isAdminPanel : 
---
**Type:** 

**Details:**


<a name="property__completeMessage"></a>
#### private $_completeMessage : 
---
**Type:** 

**Details:**


<a name="property__method"></a>
#### private $_method : 
---
**Type:** 

**Details:**


<a name="property__userEmail"></a>
#### private $_userEmail : 
---
**Type:** 

**Details:**


<a name="property__userName"></a>
#### private $_userName : 
---
**Type:** 

**Details:**


<a name="property_data"></a>
#### private $data : 
---
**Type:** 

**Details:**


<a name="property__isValidCurrentPassword"></a>
#### private $_isValidCurrentPassword : 
---
**Type:** 

**Details:**


<a name="property__newUserPassword"></a>
#### private $_newUserPassword : 
---
**Type:** 

**Details:**


<a name="property__newUserPassword2"></a>
#### private $_newUserPassword2 : 
---
**Type:** 

**Details:**


<a name="property_username_change"></a>
#### private $username_change : 
---
**Type:** 

**Details:**


<a name="property__themeChanged"></a>
#### private $_themeChanged : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_saveInsert" class="anchor"></a>
#### public saveInsert() : boolean

```
public saveInsert() : boolean
```

**Summary**

Save User Fields

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)

**Returns:** boolean


<a name="method_saveUpdate" class="anchor"></a>
#### public saveUpdate() : boolean

```
public saveUpdate() : boolean
```

**Summary**

Update User Fields

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)

**Returns:** boolean


<a name="method_getData" class="anchor"></a>
#### public getData() : array

```
public getData() : array
```

**Summary**

Returns userhash added userdata array

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)

**Returns:** array


<a name="method_setUserNameChange" class="anchor"></a>
#### public setUserNameChange() 

```
public setUserNameChange(string  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |




<a name="method_verifyCode" class="anchor"></a>
#### public verifyCode() 

```
public verifyCode(string  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |




<a name="method_themeChanged" class="anchor"></a>
#### public themeChanged() : boolean

```
public themeChanged() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)

**Returns:** boolean


<a name="method_setEmptyFields" class="anchor"></a>
#### private setEmptyFields() : array

```
private setEmptyFields() : array
```

**Summary**

Initialise empty fields

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)

**Returns:** array


<a name="method_setUserName" class="anchor"></a>
#### private setUserName() 

```
private setUserName() 
```

**Summary**

Handle User Name Input and Validation

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_setPassword" class="anchor"></a>
#### private setPassword() 

```
private setPassword() 
```

**Summary**

Handle User Password Input and Validation

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_getPasswordInput" class="anchor"></a>
#### private getPasswordInput() : false&amp;#124;mixed

```
private getPasswordInput(string  $field) : false&amp;#124;mixed
```

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  |  |

**Returns:** false&#124;mixed


<a name="method_setUserEmail" class="anchor"></a>
#### private setUserEmail() 

```
private setUserEmail() 
```

**Summary**

Handle User Email Input and Validation

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_verifyNewEmail" class="anchor"></a>
#### private verifyNewEmail() 

```
private verifyNewEmail() 
```

**Summary**

Handle new email verification procedures

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_setValidationError" class="anchor"></a>
#### private setValidationError() 

```
private setValidationError() 
```

**Summary**

Set validation error

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_setEmailVerification" class="anchor"></a>
#### private setEmailVerification() 

```
private setEmailVerification() 
```

**Summary**

Handle request for email verification
Sends Verification code when you change email
Sends Verification code when you register

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_setAdminPassword" class="anchor"></a>
#### private setAdminPassword() 

```
private setAdminPassword() 
```

**Summary**

Set admin password

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_setUserAvatar" class="anchor"></a>
#### private setUserAvatar() 

```
private setUserAvatar() 
```

**Summary**

Set user avatar

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)




<a name="method_verifyEmailPass" class="anchor"></a>
#### private verifyEmailPass() 

```
private verifyEmailPass() 
```

**Summary**

To validate only when _setUserEmail is true
Changing Email address

**Details:**
* Inherited From: [\PHPFusion\UserFieldsInput](../classes/PHPFusion.UserFieldsInput.md)





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
