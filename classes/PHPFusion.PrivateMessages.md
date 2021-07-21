# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\PrivateMessages
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class PrivateMessages

---
### Constants
* No constants found
---
### Properties
* [public $locale](../classes/PHPFusion.PrivateMessages.md#property_locale)
* [private $info](../classes/PHPFusion.PrivateMessages.md#property_info)
* [private $data](../classes/PHPFusion.PrivateMessages.md#property_data)
* [private $instances](../classes/PHPFusion.PrivateMessages.md#property_instances)
* [private $is_sent](../classes/PHPFusion.PrivateMessages.md#property_is_sent)
---
### Methods
* [public getInfo()](../classes/PHPFusion.PrivateMessages.md#method_getInfo)
* [public getPmSettings()](../classes/PHPFusion.PrivateMessages.md#method_getPmSettings)
* [public sendPm()](../classes/PHPFusion.PrivateMessages.md#method_sendPm)
* [public getInstance()](../classes/PHPFusion.PrivateMessages.md#method_getInstance)
* [public server()](../classes/PHPFusion.PrivateMessages.md#method_server)
* [public view()](../classes/PHPFusion.PrivateMessages.md#method_view)
* [protected validatePmUser()](../classes/PHPFusion.PrivateMessages.md#method_validatePmUser)
* [private setListMessages()](../classes/PHPFusion.PrivateMessages.md#method_setListMessages)
* [private setReadMessages()](../classes/PHPFusion.PrivateMessages.md#method_setReadMessages)
* [private setMessageOptions()](../classes/PHPFusion.PrivateMessages.md#method_setMessageOptions)
* [private setActionMenu()](../classes/PHPFusion.PrivateMessages.md#method_setActionMenu)
* [private doArchive()](../classes/PHPFusion.PrivateMessages.md#method_doArchive)
* [private doUnarchive()](../classes/PHPFusion.PrivateMessages.md#method_doUnarchive)
* [private doDelete()](../classes/PHPFusion.PrivateMessages.md#method_doDelete)
* [private doMark()](../classes/PHPFusion.PrivateMessages.md#method_doMark)
* [private doSend()](../classes/PHPFusion.PrivateMessages.md#method_doSend)
* [private setReplyForm()](../classes/PHPFusion.PrivateMessages.md#method_setReplyForm)
* [private setSendForm()](../classes/PHPFusion.PrivateMessages.md#method_setSendForm)
* [private __construct()](../classes/PHPFusion.PrivateMessages.md#method___construct)
---
### Details
* File: [classes\PHPFusion\PrivateMessages.php](../files/classes.PHPFusion.PrivateMessages.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\PrivateMessages
---
## Properties
<a name="property_locale"></a>
#### public $locale : 
---
**Type:** 

**Details:**


<a name="property_info"></a>
#### private $info : 
---
**Type:** 

**Details:**


<a name="property_data"></a>
#### private $data : 
---
**Summary**

Reply and send
SQL send pm

**Type:** 

**Details:**


<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**


<a name="property_is_sent"></a>
#### private $is_sent : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInfo" class="anchor"></a>
#### public getInfo() : array

```
public getInfo() : array
```

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)

**Returns:** array


<a name="method_getPmSettings" class="anchor"></a>
#### public getPmSettings() : array&amp;#124;mixed&amp;#124;null

```
Static public getPmSettings(integer  $user_id, null  $key = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Summary**

Get the pm settings for users

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |
| <code>null</code> | $key  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_sendPm" class="anchor"></a>
#### public sendPm() 

```
Static public sendPm(string  $to, string  $from, string  $subject, string  $message, string  $smileys = &#039;y&#039;, boolean  $to_group = FALSE, boolean  $save_sent = TRUE) 
```

**Summary**

Public API to send message using the message system

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $to  |  |
| <code>string</code> | $from  |  |
| <code>string</code> | $subject  |  |
| <code>string</code> | $message  |  |
| <code>string</code> | $smileys  |  |
| <code>boolean</code> | $to_group  |  |
| <code>boolean</code> | $save_sent  |  |




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $key = &#039;default&#039;) : static
```

**Summary**

Get PM Instances

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_server" class="anchor"></a>
#### public server() : $this

```
public server() : $this
```

**Summary**

Private message server

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)

**Returns:** $this


<a name="method_view" class="anchor"></a>
#### public view() 

```
public view() 
```

**Summary**

Private message main viewer

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_validatePmUser" class="anchor"></a>
#### protected validatePmUser() : boolean

```
Static protected validatePmUser(integer  $user_id) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |

**Returns:** boolean


<a name="method_setListMessages" class="anchor"></a>
#### private setListMessages() 

```
private setListMessages() 
```

**Summary**

Set Message Listing for inbox, outbox and archive*

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_setReadMessages" class="anchor"></a>
#### private setReadMessages() 

```
private setReadMessages() 
```

**Summary**

Set message reader

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_setMessageOptions" class="anchor"></a>
#### private setMessageOptions() 

```
private setMessageOptions() 
```

**Summary**

Set Message Options Viewer

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_setActionMenu" class="anchor"></a>
#### private setActionMenu() 

```
private setActionMenu() 
```

**Summary**

Actions buttons - archive, delete, mark all read, mark all unread, mark as read, mark as unread

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_doArchive" class="anchor"></a>
#### private doArchive() 

```
private doArchive() 
```

**Summary**

Actions: archive messages

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_doUnarchive" class="anchor"></a>
#### private doUnarchive() 

```
private doUnarchive() 
```

**Summary**

Actions: unarchive messages

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_doDelete" class="anchor"></a>
#### private doDelete() 

```
private doDelete() 
```

**Summary**

Actions: delete messages

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_doMark" class="anchor"></a>
#### private doMark() 

```
private doMark() 
```

**Summary**

Actions: marking messages

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_doSend" class="anchor"></a>
#### private doSend() 

```
private doSend() 
```

**Summary**

Actions: send messages

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method_setReplyForm" class="anchor"></a>
#### private setReplyForm() 

```
private setReplyForm(boolean  $show_form = TRUE) 
```

**Summary**

Private message forms
pm_form (Short form)
pm_mainForm (Full composing environment)

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $show_form  |  |




<a name="method_setSendForm" class="anchor"></a>
#### private setSendForm() 

```
private setSendForm() 
```

**Summary**

New message form

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)




<a name="method___construct" class="anchor"></a>
#### private __construct() 

```
private __construct() 
```

**Summary**

PrivateMessages constructor.

**Details:**
* Inherited From: [\PHPFusion\PrivateMessages](../classes/PHPFusion.PrivateMessages.md)





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
