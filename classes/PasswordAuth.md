# [PHPFusion Docs](../home.md)

# Class: \PasswordAuth
### Namespace: [\](../namespaces/default.md)
---
**Summary:**

PasswordAuth class for compatibility reason

---
### Constants
* No constants found
---
### Properties
* [public $currentAlgo](../classes/PHPFusion.PasswordAuth.md#property_currentAlgo)
* [public $currentSalt](../classes/PHPFusion.PasswordAuth.md#property_currentSalt)
* [public $currentPasswordHash](../classes/PHPFusion.PasswordAuth.md#property_currentPasswordHash)
* [public $inputPassword](../classes/PHPFusion.PasswordAuth.md#property_inputPassword)
* [public $inputNewPassword](../classes/PHPFusion.PasswordAuth.md#property_inputNewPassword)
* [public $inputNewPassword2](../classes/PHPFusion.PasswordAuth.md#property_inputNewPassword2)
* [public $currentPassCheckLength](../classes/PHPFusion.PasswordAuth.md#property_currentPassCheckLength)
* [public $currentPassCheckCase](../classes/PHPFusion.PasswordAuth.md#property_currentPassCheckCase)
* [public $currentPassCheckNum](../classes/PHPFusion.PasswordAuth.md#property_currentPassCheckNum)
* [public $currentPassCheckSpecialchar](../classes/PHPFusion.PasswordAuth.md#property_currentPassCheckSpecialchar)
* [private $newAlgo](../classes/PHPFusion.PasswordAuth.md#property_newAlgo)
* [private $newSalt](../classes/PHPFusion.PasswordAuth.md#property_newSalt)
* [private $newPasswordHash](../classes/PHPFusion.PasswordAuth.md#property_newPasswordHash)
* [private $error](../classes/PHPFusion.PasswordAuth.md#property_error)
---
### Methods
* [public __construct()](../classes/PHPFusion.PasswordAuth.md#method___construct)
* [public isValidCurrentPassword()](../classes/PHPFusion.PasswordAuth.md#method_isValidCurrentPassword)
* [public checkInputPassword()](../classes/PHPFusion.PasswordAuth.md#method_checkInputPassword)
* [public passwordStrengthOpts()](../classes/PHPFusion.PasswordAuth.md#method_passwordStrengthOpts)
* [public getNewRandomSalt()](../classes/PHPFusion.PasswordAuth.md#method_getNewRandomSalt)
* [public getNewPassword()](../classes/PHPFusion.PasswordAuth.md#method_getNewPassword)
* [public getError()](../classes/PHPFusion.PasswordAuth.md#method_getError)
* [public setNewPassword()](../classes/PHPFusion.PasswordAuth.md#method_setNewPassword)
* [public isValidNewPassword()](../classes/PHPFusion.PasswordAuth.md#method_isValidNewPassword)
* [public getNewAlgo()](../classes/PHPFusion.PasswordAuth.md#method_getNewAlgo)
* [public getNewSalt()](../classes/PHPFusion.PasswordAuth.md#method_getNewSalt)
* [public getNewHash()](../classes/PHPFusion.PasswordAuth.md#method_getNewHash)
* [protected setNewHash()](../classes/PHPFusion.PasswordAuth.md#method_setNewHash)
* [private hashPassword()](../classes/PHPFusion.PasswordAuth.md#method_hashPassword)
* [private isValidPasswordInput()](../classes/PHPFusion.PasswordAuth.md#method_isValidPasswordInput)
---
### Details
* File: [classes\PasswordAuth.class.php](../files/classes.PasswordAuth.class.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
  * \PasswordAuth
---
## Properties
<a name="property_currentAlgo"></a>
#### public $currentAlgo : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentSalt"></a>
#### public $currentSalt : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentPasswordHash"></a>
#### public $currentPasswordHash : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_inputPassword"></a>
#### public $inputPassword : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_inputNewPassword"></a>
#### public $inputNewPassword : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_inputNewPassword2"></a>
#### public $inputNewPassword2 : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentPassCheckLength"></a>
#### public $currentPassCheckLength : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentPassCheckCase"></a>
#### public $currentPassCheckCase : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentPassCheckNum"></a>
#### public $currentPassCheckNum : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_currentPassCheckSpecialchar"></a>
#### public $currentPassCheckSpecialchar : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_newAlgo"></a>
#### private $newAlgo : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_newSalt"></a>
#### private $newSalt : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_newPasswordHash"></a>
#### private $newPasswordHash : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)


<a name="property_error"></a>
#### private $error : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct(string  $passwordAlgorithm = &#039;sha256&#039;) 
```

**Summary**

PasswordAuth constructor.

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $passwordAlgorithm  |  |




<a name="method_isValidCurrentPassword" class="anchor"></a>
#### public isValidCurrentPassword() : boolean

```
public isValidCurrentPassword(boolean  $createNewHash = FALSE) : boolean
```

**Summary**

Checks if new password is valid

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $createNewHash  |  |

**Returns:** boolean


<a name="method_checkInputPassword" class="anchor"></a>
#### public checkInputPassword() : boolean

```
public checkInputPassword(string  $value) : boolean
```

**Summary**

Strengh settings check

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |

**Returns:** boolean


<a name="method_passwordStrengthOpts" class="anchor"></a>
#### public passwordStrengthOpts() : string

```
Static public passwordStrengthOpts(integer  $minimum_length = 8, boolean  $number = TRUE, false  $camelcase = FALSE, false  $special_char = FALSE) : string
```

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $minimum_length  |  |
| <code>boolean</code> | $number  |  |
| <code>false</code> | $camelcase  |  |
| <code>false</code> | $special_char  |  |

**Returns:** string


<a name="method_getNewRandomSalt" class="anchor"></a>
#### public getNewRandomSalt() : string

```
Static public getNewRandomSalt(integer  $length = 12) : string
```

**Summary**

Generate a random password salt

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $length  |  |

**Returns:** string


<a name="method_getNewPassword" class="anchor"></a>
#### public getNewPassword() : string

```
Static public getNewPassword(integer  $length = 12) : string
```

**Summary**

Generates a random password with given length

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $length  |  |

**Returns:** string


<a name="method_getError" class="anchor"></a>
#### public getError() 

```
public getError() 
```

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)




<a name="method_setNewPassword" class="anchor"></a>
#### public setNewPassword() : array

```
public setNewPassword(  $user_password) : array
```

**Summary**

Get hash, salt, and algo

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $user_password  |  |

**Returns:** array


<a name="method_isValidNewPassword" class="anchor"></a>
#### public isValidNewPassword() : integer

```
public isValidNewPassword() : integer
```

**Summary**

Checks whether new input password is valid

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)

**Returns:** integer


<a name="method_getNewAlgo" class="anchor"></a>
#### public getNewAlgo() : string

```
public getNewAlgo() : string
```

**Summary**

Get new password algorithem

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)

**Returns:** string


<a name="method_getNewSalt" class="anchor"></a>
#### public getNewSalt() : mixed

```
public getNewSalt() : mixed
```

**Summary**

Get new password salt

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)

**Returns:** mixed


<a name="method_getNewHash" class="anchor"></a>
#### public getNewHash() : mixed

```
public getNewHash() : mixed
```

**Summary**

Get new password hash

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)

**Returns:** mixed


<a name="method_setNewHash" class="anchor"></a>
#### protected setNewHash() 

```
protected setNewHash(  $password) 
```

**Summary**

Generate new password hash and password salt

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $password  |  |




<a name="method_hashPassword" class="anchor"></a>
#### private hashPassword() : string

```
private hashPassword(string  $password, string  $algorithm, string  $salt) : string
```

**Summary**

Encrypts the password with given algorithm and salt

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $password  |  |
| <code>string</code> | $algorithm  |  |
| <code>string</code> | $salt  |  |

**Returns:** string


<a name="method_isValidPasswordInput" class="anchor"></a>
#### private isValidPasswordInput() : boolean

```
private isValidPasswordInput() : boolean
```

**Summary**

Checks if new password input is valid

**Details:**
* Inherited From: [\PHPFusion\PasswordAuth](../classes/PHPFusion.PasswordAuth.md)

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
