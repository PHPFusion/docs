# [PHPFusion Docs](../home.md)

# Class: \Authenticate
### Namespace: [\](../namespaces/default.md)
---
**Summary:**

Authenticate class for compatibility reason

---
### Constants
* No constants found
---
### Properties
* [private $authenticate_url](../classes/PHPFusion.Authenticate.md#property_authenticate_url)
* [private $user_data](../classes/PHPFusion.Authenticate.md#property_user_data)
---
### Methods
* [public __construct()](../classes/PHPFusion.Authenticate.md#method___construct)
* [public setUserCookie()](../classes/PHPFusion.Authenticate.md#method_setUserCookie)
* [public getRedirectUrl()](../classes/PHPFusion.Authenticate.md#method_getRedirectUrl)
* [public _setUserTheme()](../classes/PHPFusion.Authenticate.md#method__setUserTheme)
* [public setAdminLogin()](../classes/PHPFusion.Authenticate.md#method_setAdminLogin)
* [public expireAdminCookie()](../classes/PHPFusion.Authenticate.md#method_expireAdminCookie)
* [public validateAuthAdmin()](../classes/PHPFusion.Authenticate.md#method_validateAuthAdmin)
* [public setAdminCookie()](../classes/PHPFusion.Authenticate.md#method_setAdminCookie)
* [public validateAuthUser()](../classes/PHPFusion.Authenticate.md#method_validateAuthUser)
* [public logOut()](../classes/PHPFusion.Authenticate.md#method_logOut)
* [public getEmptyUserData()](../classes/PHPFusion.Authenticate.md#method_getEmptyUserData)
* [public setLastVisitCookie()](../classes/PHPFusion.Authenticate.md#method_setLastVisitCookie)
* [public setVisitorCounter()](../classes/PHPFusion.Authenticate.md#method_setVisitorCounter)
* [public getUserData()](../classes/PHPFusion.Authenticate.md#method_getUserData)
* [private _authenticate()](../classes/PHPFusion.Authenticate.md#method__authenticate)
* [private storeUserSession()](../classes/PHPFusion.Authenticate.md#method_storeUserSession)
---
### Details
* File: [classes\Authenticate.class.php](../files/classes.Authenticate.class.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
  * \Authenticate
---
## Properties
<a name="property_authenticate_url"></a>
#### private $authenticate_url : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)


<a name="property_user_data"></a>
#### private $user_data : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct(string  $inputUserName, string  $inputPassword, boolean  $remember, string  $authentication_url = NULL) 
```

**Summary**

Authenticate constructor.

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $inputUserName  |  |
| <code>string</code> | $inputPassword  |  |
| <code>boolean</code> | $remember  |  |
| <code>string</code> | $authentication_url  |  |




<a name="method_setUserCookie" class="anchor"></a>
#### public setUserCookie() 

```
Static public setUserCookie(integer  $userID, string  $salt, string  $algo, boolean  $remember = FALSE, boolean  $userCookie = TRUE) 
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $userID  |  |
| <code>string</code> | $salt  |  |
| <code>string</code> | $algo  |  |
| <code>boolean</code> | $remember  |  |
| <code>boolean</code> | $userCookie  |  |




<a name="method_getRedirectUrl" class="anchor"></a>
#### public getRedirectUrl() : string

```
Static public getRedirectUrl(integer  $errorId, string  $userStatus = &quot;&quot;, string  $userId = &quot;&quot;) : string
```

**Summary**

Get the redirection url
If there is a new authentication url, error request will not valid

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $errorId  |  |
| <code>string</code> | $userStatus  |  |
| <code>string</code> | $userId  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| todo |  | : use addNotice('') instead of going for errorId |

<a name="method__setUserTheme" class="anchor"></a>
#### public _setUserTheme() : mixed&amp;#124;null

```
Static public _setUserTheme(array  $user) : mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $user  |  |

**Returns:** mixed&#124;null


<a name="method_setAdminLogin" class="anchor"></a>
#### public setAdminLogin() 

```
Static public setAdminLogin() 
```

**Summary**

Set admin login

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)




<a name="method_expireAdminCookie" class="anchor"></a>
#### public expireAdminCookie() 

```
Static public expireAdminCookie() 
```

**Summary**

Expire admin cookie

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)




<a name="method_validateAuthAdmin" class="anchor"></a>
#### public validateAuthAdmin() : boolean

```
Static public validateAuthAdmin(string  $pass = &quot;&quot;) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $pass  |  |

**Returns:** boolean


<a name="method_setAdminCookie" class="anchor"></a>
#### public setAdminCookie() : boolean

```
Static public setAdminCookie(string  $inputPassword) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $inputPassword  |  |

**Returns:** boolean


<a name="method_validateAuthUser" class="anchor"></a>
#### public validateAuthUser() : array&amp;#124;string&amp;#124;null

```
Static public validateAuthUser() : array&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)

**Returns:** array&#124;string&#124;null


<a name="method_logOut" class="anchor"></a>
#### public logOut() : array

```
Static public logOut() : array
```

**Summary**

Log out

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)

**Returns:** array


<a name="method_getEmptyUserData" class="anchor"></a>
#### public getEmptyUserData() : array

```
Static public getEmptyUserData() : array
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)

**Returns:** array


<a name="method_setLastVisitCookie" class="anchor"></a>
#### public setLastVisitCookie() : array&amp;#124;integer&amp;#124;mixed&amp;#124;string&amp;#124;null

```
Static public setLastVisitCookie() : array&amp;#124;integer&amp;#124;mixed&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)

**Returns:** array&#124;integer&#124;mixed&#124;string&#124;null


<a name="method_setVisitorCounter" class="anchor"></a>
#### public setVisitorCounter() 

```
Static public setVisitorCounter() 
```

**Summary**

Set visitor counter

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)




<a name="method_getUserData" class="anchor"></a>
#### public getUserData() : array

```
public getUserData() : array
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)

**Returns:** array


<a name="method__authenticate" class="anchor"></a>
#### private _authenticate() 

```
private _authenticate(string  $inputUserName, string  $inputPassword, boolean  $remember) 
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $inputUserName  |  |
| <code>string</code> | $inputPassword  |  |
| <code>boolean</code> | $remember  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPMailer\PHPMailer\Exception |  |




<a name="method_storeUserSession" class="anchor"></a>
#### private storeUserSession() 

```
Static private storeUserSession(\PHPFusion\PasswordAuth  $passAuth, integer  $user_id) 
```

**Details:**
* Inherited From: [\PHPFusion\Authenticate](../classes/PHPFusion.Authenticate.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code><a href="../classes/PHPFusion.PasswordAuth.html">\PHPFusion\PasswordAuth</a></code> | $passAuth  |  |
| <code>integer</code> | $user_id  |  |





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
