# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Comments
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Comments

---
### Constants
* No constants found
---
### Properties
* [private $instances](../classes/PHPFusion.Comments.md#property_instances)
* [private $key](../classes/PHPFusion.Comments.md#property_key)
* [private $params](../classes/PHPFusion.Comments.md#property_params)
* [private $locale](../classes/PHPFusion.Comments.md#property_locale)
* [private $userdata](../classes/PHPFusion.Comments.md#property_userdata)
* [private $settings](../classes/PHPFusion.Comments.md#property_settings)
* [private $post_link](../classes/PHPFusion.Comments.md#property_post_link)
* [private $c_arr](../classes/PHPFusion.Comments.md#property_c_arr)
* [private $comment_params](../classes/PHPFusion.Comments.md#property_comment_params)
* [private $comment_data](../classes/PHPFusion.Comments.md#property_comment_data)
* [private $cpp](../classes/PHPFusion.Comments.md#property_cpp)
* [private $clink](../classes/PHPFusion.Comments.md#property_clink)
* [private $c_start](../classes/PHPFusion.Comments.md#property_c_start)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Comments.md#method_getInstance)
* [public showComments()](../classes/PHPFusion.Comments.md#method_showComments)
* [public getParams()](../classes/PHPFusion.Comments.md#method_getParams)
* [public replaceParam()](../classes/PHPFusion.Comments.md#method_replaceParam)
* [private __construct()](../classes/PHPFusion.Comments.md#method___construct)
* [private setInstance()](../classes/PHPFusion.Comments.md#method_setInstance)
* [private displayAllComments()](../classes/PHPFusion.Comments.md#method_displayAllComments)
* [private checkPermissions()](../classes/PHPFusion.Comments.md#method_checkPermissions)
* [private setParams()](../classes/PHPFusion.Comments.md#method_setParams)
* [private setEmptyCommentData()](../classes/PHPFusion.Comments.md#method_setEmptyCommentData)
* [private executeCommentUpdate()](../classes/PHPFusion.Comments.md#method_executeCommentUpdate)
* [private formatClink()](../classes/PHPFusion.Comments.md#method_formatClink)
* [private getComments()](../classes/PHPFusion.Comments.md#method_getComments)
* [private parseCommentsData()](../classes/PHPFusion.Comments.md#method_parseCommentsData)
---
### Details
* File: [classes\PHPFusion\Comments.php](../files/classes.PHPFusion.Comments.md)
* Package: PHPFusion
         Rating is not working
         Edit is not working
* Class Hierarchy:
  * \PHPFusion\Comments
---
## Properties
<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**


<a name="property_key"></a>
#### private $key : 
---
**Type:** 

**Details:**


<a name="property_params"></a>
#### private $params : array
---
**Type:** array
comment_item_type -
comment_db -
comment_item_id -
clink -
comment_allow_reply - enable or disable reply of others comments
comment_allow_post - enable or disable posting of comments
comment_allow_ratings - enable or disable ratings
comment_allow_vote - enable or disable voting
comment_once - each user can only comment once (replying a comment is unaffected)
comment_echo - to echo the output if true
comment_title - display the comment block title
comment_count - display the current comment count
**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_userdata"></a>
#### private $userdata : 
---
**Type:** 

**Details:**


<a name="property_settings"></a>
#### private $settings : 
---
**Type:** 

**Details:**


<a name="property_post_link"></a>
#### private $post_link : 
---
**Type:** 

**Details:**


<a name="property_c_arr"></a>
#### private $c_arr : 
---
**Type:** 

**Details:**


<a name="property_comment_params"></a>
#### private $comment_params : 
---
**Type:** 

**Details:**


<a name="property_comment_data"></a>
#### private $comment_data : 
---
**Type:** 

**Details:**


<a name="property_cpp"></a>
#### private $cpp : 
---
**Type:** 

**Details:**


<a name="property_clink"></a>
#### private $clink : 
---
**Summary**

Removes comment reply

**Type:** 

**Details:**

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| param |  |  |
| return |  |  |

<a name="property_c_start"></a>
#### private $c_start : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(array  $params = array(), string  $key = &#039;Default&#039;) : static
```

**Summary**

Get an instance by key

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $params  |  |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_showComments" class="anchor"></a>
#### public showComments() 

```
public showComments() 
```

**Summary**

Displays Comments

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_getParams" class="anchor"></a>
#### public getParams() : null

```
public getParams(null  $key = NULL) : null
```

**Summary**

Get Comment Object Parameter

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>null</code> | $key  | null for all array |

**Returns:** null


<a name="method_replaceParam" class="anchor"></a>
#### public replaceParam() 

```
public replaceParam(  $param,   $value) 
```

**Summary**

Replace Comment Object Parameter

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $param  |  |
| <code></code> | $value  |  |




<a name="method___construct" class="anchor"></a>
#### private __construct() 

```
private __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_setInstance" class="anchor"></a>
#### private setInstance() 

```
Static private setInstance(string  $key) 
```

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |




<a name="method_displayAllComments" class="anchor"></a>
#### private displayAllComments() : string

```
private displayAllComments(array  $c_data, integer  $index, string&amp;#124;array  $options) : string
```

**Summary**

Comments Listing

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $c_data  |  |
| <code>integer</code> | $index  |  |
| <code>string&#124;array</code> | $options  |  |

**Returns:** string


<a name="method_checkPermissions" class="anchor"></a>
#### private checkPermissions() 

```
private checkPermissions() 
```

**Summary**

Check permissions

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_setParams" class="anchor"></a>
#### private setParams() 

```
private setParams(array  $params = array()) 
```

**Summary**

Set Comment Object Parameters

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $params  |  |




<a name="method_setEmptyCommentData" class="anchor"></a>
#### private setEmptyCommentData() 

```
private setEmptyCommentData() 
```

**Summary**

Set empty comment data

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_executeCommentUpdate" class="anchor"></a>
#### private executeCommentUpdate() 

```
private executeCommentUpdate() 
```

**Summary**

Execute comment update

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_formatClink" class="anchor"></a>
#### private formatClink() : string

```
Static private formatClink(string  $clink) : string
```

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $clink  |  |

**Returns:** string


<a name="method_getComments" class="anchor"></a>
#### private getComments() 

```
private getComments() 
```

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)




<a name="method_parseCommentsData" class="anchor"></a>
#### private parseCommentsData() 

```
private parseCommentsData(  $row,   $i) 
```

**Details:**
* Inherited From: [\PHPFusion\Comments](../classes/PHPFusion.Comments.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $row  |  |
| <code></code> | $i  |  |





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
