# [PHPFusion Docs](../home.md)

# Class: \Defender\Token
### Namespace: [\Defender](../namespaces/Defender.md)
---
**Summary:**

Class Token
CSRF protection layer for PHPFusion CMS

---
### Constants
* No constants found
---
### Properties
* [public $input_errors](../classes/Defender.md#property_input_errors)
* [public $ref](../classes/Defender.md#property_ref)
* [public $field](../classes/Defender.md#property_field)
* [public $field_name](../classes/Defender.md#property_field_name)
* [public $field_value](../classes/Defender.md#property_field_value)
* [public $field_default](../classes/Defender.md#property_field_default)
* [public $field_config](../classes/Defender.md#property_field_config)
* [public $remote_file](../classes/Defender.Token.md#property_remote_file)
* [public $allow_repost](../classes/Defender.Token.md#property_allow_repost)
* [private $debug](../classes/Defender.Token.md#property_debug)
* [private $defender_instance](../classes/Defender.md#property_defender_instance)
* [private $input_name](../classes/Defender.md#property_input_name)
* [private $input_error_text](../classes/Defender.md#property_input_error_text)
* [private $page_hash](../classes/Defender.md#property_page_hash)
* [private $tokenIsValid](../classes/Defender.Token.md#property_tokenIsValid)
* [private $error](../classes/Defender.Token.md#property_error)
---
### Methods
* [public getInstance()](../classes/Defender.md#method_getInstance)
* [public serialize()](../classes/Defender.md#method_serialize)
* [public encode()](../classes/Defender.md#method_encode)
* [public decode()](../classes/Defender.md#method_decode)
* [public unserialize()](../classes/Defender.md#method_unserialize)
* [public add_field_session()](../classes/Defender.md#method_add_field_session)
* [public pageHash()](../classes/Defender.md#method_pageHash)
* [public unset_field_session()](../classes/Defender.md#method_unset_field_session)
* [public sanitize_array()](../classes/Defender.md#method_sanitize_array)
* [public set_sessionUserID()](../classes/Defender.md#method_set_sessionUserID)
* [public getInputErrors()](../classes/Defender.md#method_getInputErrors)
* [public setErrorText()](../classes/Defender.md#method_setErrorText)
* [public getErrorText()](../classes/Defender.md#method_getErrorText)
* [public inputHasError()](../classes/Defender.md#method_inputHasError)
* [public get_inputError()](../classes/Defender.md#method_get_inputError)
* [public get_encrypt_key()](../classes/Defender.md#method_get_encrypt_key)
* [public encrypt_string()](../classes/Defender.md#method_encrypt_string)
* [public decrypt_string()](../classes/Defender.md#method_decrypt_string)
* [public get_current_field_session()](../classes/Defender.md#method_get_current_field_session)
* [public safe()](../classes/Defender.md#method_safe)
* [public addHoneypot()](../classes/Defender.md#method_addHoneypot)
* [public getHoneypot()](../classes/Defender.md#method_getHoneypot)
* [public debug()](../classes/Defender.md#method_debug)
* [public sanitizer()](../classes/Defender.md#method_sanitizer)
* [public filterPostArray()](../classes/Defender.md#method_filterPostArray)
* [public formSanitizer()](../classes/Defender.md#method_formSanitizer)
* [public validate()](../classes/Defender.md#method_validate)
* [public stop()](../classes/Defender.md#method_stop)
* [public setInputError()](../classes/Defender.md#method_setInputError)
* [public fileSanitizer()](../classes/Defender.md#method_fileSanitizer)
* [public __construct()](../classes/Defender.Token.md#method___construct)
* [public generate_token()](../classes/Defender.Token.md#method_generate_token)
* [private pkcs7_pad()](../classes/Defender.md#method_pkcs7_pad)
* [private pkcs7_unpad()](../classes/Defender.md#method_pkcs7_unpad)
* [private verify_token()](../classes/Defender.Token.md#method_verify_token)
---
### Details
* File: [defender\token.php](../files/defender.token.md)
* Package: Defender
* Class Hierarchy: 
  * [\Defender](../classes/Defender.md)
  * \Defender\Token
---
## Properties
<a name="property_input_errors"></a>
#### public $input_errors : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_ref"></a>
#### public $ref : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_field"></a>
#### public $field : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_field_name"></a>
#### public $field_name : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_field_value"></a>
#### public $field_value : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_field_default"></a>
#### public $field_default : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_field_config"></a>
#### public $field_config : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_remote_file"></a>
#### public $remote_file : string
---
**Summary**

The remote file must begin with site_path

**Type:** string

**Details:**


<a name="property_allow_repost"></a>
#### public $allow_repost : boolean
---
**Summary**

Allow using back a valid token by not consuming any tokens at all

**Type:** boolean

**Details:**


<a name="property_debug"></a>
#### private $debug : boolean
---
**Summary**

Set debug mode

**Type:** boolean
- true to debug
**Details:**


<a name="property_defender_instance"></a>
#### private $defender_instance : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_input_name"></a>
#### private $input_name : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_input_error_text"></a>
#### private $input_error_text : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_page_hash"></a>
#### private $page_hash : 
---
**Type:** 

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)


<a name="property_tokenIsValid"></a>
#### private $tokenIsValid : boolean
---
**Summary**

System to check whether post token is valid

**Type:** boolean

**Details:**


<a name="property_error"></a>
#### private $error : string
---
**Summary**

Error string

**Type:** string

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Generates and return class instance
Eliminates global usage in functions
Instead of using - `global $defender`, try `\Defender->getInstance()`

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** null&#124;static


<a name="method_serialize" class="anchor"></a>
#### public serialize() : string

```
Static public serialize(array  $array = array()) : string
```

**Summary**

Serialize an array securely

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |

**Returns:** string


<a name="method_encode" class="anchor"></a>
#### public encode() : string

```
Static public encode(string&amp;#124;array  $value) : string
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $value  |  |

**Returns:** string


<a name="method_decode" class="anchor"></a>
#### public decode() : mixed

```
Static public decode(string  $value) : mixed
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |

**Returns:** mixed


<a name="method_unserialize" class="anchor"></a>
#### public unserialize() : array&amp;#124;mixed

```
Static public unserialize(  $string) : array&amp;#124;mixed
```

**Summary**

Read serialized array

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $string  | string serialized string |

**Returns:** array&#124;mixed


<a name="method_add_field_session" class="anchor"></a>
#### public add_field_session() 

```
Static public add_field_session(array  $array) 
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |




<a name="method_pageHash" class="anchor"></a>
#### public pageHash() : string

```
Static public pageHash() : string
```

**Summary**

Hash a token to prevent unauthorized access

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** string


<a name="method_unset_field_session" class="anchor"></a>
#### public unset_field_session() 

```
Static public unset_field_session() 
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)




<a name="method_sanitize_array" class="anchor"></a>
#### public sanitize_array() : array

```
Static public sanitize_array(array  $array) : array
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |

**Returns:** array


<a name="method_set_sessionUserID" class="anchor"></a>
#### public set_sessionUserID() : mixed

```
Static public set_sessionUserID() : mixed
```

**Summary**

ID for Session
No $userName because it can be changed and tampered via Edit Profile.

**Description**

Using IP address extends for guest

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** mixed


<a name="method_getInputErrors" class="anchor"></a>
#### public getInputErrors() : array

```
Static public getInputErrors() : array
```

**Summary**

Checks whether an input was marked as invalid

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** array


<a name="method_setErrorText" class="anchor"></a>
#### public setErrorText() 

```
Static public setErrorText(string  $input_name, string  $text) 
```

**Summary**

Set and override default field error text

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |
| <code>string</code> | $text  |  |




<a name="method_getErrorText" class="anchor"></a>
#### public getErrorText() : null

```
Static public getErrorText(string  $input_name) : null
```

**Summary**

Fetches the latest error text of this input
Important! Ensure your applications do not refresh screen for this error to show.

**Description**

Usage fusion_safe(); for conditional redirect.

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |

**Returns:** null


<a name="method_inputHasError" class="anchor"></a>
#### public inputHasError() : boolean

```
Static public inputHasError(string  $input_name) : boolean
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |

**Returns:** boolean


<a name="method_get_inputError" class="anchor"></a>
#### public get_inputError() : array

```
Static public get_inputError() : array
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** array


<a name="method_get_encrypt_key" class="anchor"></a>
#### public get_encrypt_key() : string

```
Static public get_encrypt_key(string  $private_key) : string
```

**Summary**

Generate a key

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $private_key  |  |

**Returns:** string


<a name="method_encrypt_string" class="anchor"></a>
#### public encrypt_string() : string

```
Static public encrypt_string(string  $string, string  $private_key = &#039;phpfusion&#039;) : string
```

**Summary**

Encrypts a string securely with a private key

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $string  | The text to encrypt |
| <code>string</code> | $private_key  | For better security use \Defender::get_encrypt_key to generate your private key

Does not support array encrypt. |

**Returns:** string


<a name="method_decrypt_string" class="anchor"></a>
#### public decrypt_string() : null&amp;#124;string

```
Static public decrypt_string(string  $string, string  $private_key = &#039;phpfusion&#039;) : null&amp;#124;string
```

**Summary**

Decrypts a string securely with a private key

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $string  | The string to decrypt |
| <code>string</code> | $private_key  | For better security use \Defender::get_encrypt_key to generate your private key |

**Returns:** null&#124;string


<a name="method_get_current_field_session" class="anchor"></a>
#### public get_current_field_session() : mixed

```
public get_current_field_session(string  $input_name = &#039;&#039;) : mixed
```

**Summary**

Return the current document field session or sessions
Use for debug purposes

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |

**Returns:** mixed


<a name="method_safe" class="anchor"></a>
#### public safe() : boolean

```
Static public safe() : boolean
```

**Summary**

Request whether safe to proceed at all times

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** boolean


<a name="method_addHoneypot" class="anchor"></a>
#### public addHoneypot() 

```
public addHoneypot(array  $array) 
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |




<a name="method_getHoneypot" class="anchor"></a>
#### public getHoneypot() : string

```
public getHoneypot(string  $honeypot = &#039;&#039;) : string
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $honeypot  |  |

**Returns:** string


<a name="method_debug" class="anchor"></a>
#### public debug() 

```
public debug(boolean&amp;#124;FALSE  $value = FALSE) 
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean&#124;FALSE</code> | $value  |  |




<a name="method_sanitizer" class="anchor"></a>
#### public sanitizer() : string

```
public sanitizer(string  $key, string  $default = &#039;&#039;, boolean  $input_name = FALSE, boolean  $is_multiLang = FALSE) : string
```

**Summary**

Sanitize with input name

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $default  |  |
| <code>boolean</code> | $input_name  |  |
| <code>boolean</code> | $is_multiLang  |  |

**Returns:** string


<a name="method_filterPostArray" class="anchor"></a>
#### public filterPostArray() : string

```
public filterPostArray(mixed  $key) : string
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  |  |

**Returns:** string


<a name="method_formSanitizer" class="anchor"></a>
#### public formSanitizer() : string

```
public formSanitizer(string&amp;#124;array  $value, string  $default = &#039;&#039;, boolean&amp;#124;FALSE  $input_name = FALSE, boolean&amp;#124;FALSE  $is_multiLang = FALSE) : string
```

**Summary**

Sanitize

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $value  |  |
| <code>string</code> | $default  |  |
| <code>boolean&#124;FALSE</code> | $input_name  |  |
| <code>boolean&#124;FALSE</code> | $is_multiLang  |  |

**Returns:** string


<a name="method_validate" class="anchor"></a>
#### public validate() : false&amp;#124;string&amp;#124;null

```
public validate() : false&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)

**Returns:** false&#124;string&#124;null


<a name="method_stop" class="anchor"></a>
#### public stop() : null

```
Static public stop(string  $notice = &#039;&#039;) : null
```

**Summary**

Sends a system error declaration.

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $notice  |  |

**Returns:** null


<a name="method_setInputError" class="anchor"></a>
#### public setInputError() 

```
Static public setInputError(string  $input_name) 
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |




<a name="method_fileSanitizer" class="anchor"></a>
#### public fileSanitizer() : array

```
public fileSanitizer(string  $key, string  $default = &#039;&#039;, false  $input_name = FALSE) : array
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $default  |  |
| <code>false</code> | $input_name  |  |

**Returns:** array


<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Details:**
* Inherited From: [\Defender\Token](../classes/Defender.Token.md)




<a name="method_generate_token" class="anchor"></a>
#### public generate_token() : string

```
Static public generate_token(string  $form_id = &#039;phpfusion&#039;, integer  $max_tokens = 5) : string
```

**Summary**

Generates a unique token

**Details:**
* Inherited From: [\Defender\Token](../classes/Defender.Token.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $form_id  |  |
| <code>integer</code> | $max_tokens  |  |

**Returns:** string


<a name="method_pkcs7_pad" class="anchor"></a>
#### private pkcs7_pad() : string

```
Static private pkcs7_pad(string  $data, integer  $size) : string
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $data  |  |
| <code>integer</code> | $size  |  |

**Returns:** string


<a name="method_pkcs7_unpad" class="anchor"></a>
#### private pkcs7_unpad() : false&amp;#124;string

```
Static private pkcs7_unpad(string  $data) : false&amp;#124;string
```

**Details:**
* Inherited From: [\Defender](../classes/Defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $data  |  |

**Returns:** false&#124;string


<a name="method_verify_token" class="anchor"></a>
#### private verify_token() : boolean

```
Static private verify_token() : boolean
```

**Summary**

Plain Token Validation - executed at maincore.php through sniff_token() only.

**Description**

Makes thorough checks of a posted token, and the token alone. It does not unset token.

**Details:**
* Inherited From: [\Defender\Token](../classes/Defender.Token.md)

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
