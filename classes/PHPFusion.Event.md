# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Event
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class DomainEvent
The purpose of this class is to enable domain level event management
such as notifications and user level cron to run.

---
### Constants
* No constants found
---
### Properties
* [protected $event_time](../classes/PHPFusion.Event.md#property_event_time)
* [private $event_instance](../classes/PHPFusion.Event.md#property_event_instance)
* [private $handler](../classes/PHPFusion.Event.md#property_handler)
* [private $event_name](../classes/PHPFusion.Event.md#property_event_name)
* [private $notices](../classes/PHPFusion.Event.md#property_notices)
* [private $event_required](../classes/PHPFusion.Event.md#property_event_required)
* [private $user_id](../classes/PHPFusion.Event.md#property_user_id)
* [private $threshold_minute](../classes/PHPFusion.Event.md#property_threshold_minute)
---
### Methods
* [public getEventClass()](../classes/PHPFusion.Event.md#method_getEventClass)
* [public setEventName()](../classes/PHPFusion.Event.md#method_setEventName)
* [public getEventTime()](../classes/PHPFusion.Event.md#method_getEventTime)
* [public getInstance()](../classes/PHPFusion.Event.md#method_getInstance)
* [public setUserId()](../classes/PHPFusion.Event.md#method_setUserId)
* [public isEventRequired()](../classes/PHPFusion.Event.md#method_isEventRequired)
* [public addNotice()](../classes/PHPFusion.Event.md#method_addNotice)
* [public renderNotice()](../classes/PHPFusion.Event.md#method_renderNotice)
* [public parentNoticeTemplate()](../classes/PHPFusion.Event.md#method_parentNoticeTemplate)
* [public childNoticeTemplate()](../classes/PHPFusion.Event.md#method_childNoticeTemplate)
* [public noNoticeTemplate()](../classes/PHPFusion.Event.md#method_noNoticeTemplate)
* [protected getUserId()](../classes/PHPFusion.Event.md#method_getUserId)
* [protected handleGlobalEvent()](../classes/PHPFusion.Event.md#method_handleGlobalEvent)
* [private cacheNotices()](../classes/PHPFusion.Event.md#method_cacheNotices)
---
### Details
* File: [classes\PHPFusion\Event.php](../files/classes.PHPFusion.Event.md)
* Package: PHPFusion\Event
* Class Hierarchy:
  * \PHPFusion\Event
---
## Properties
<a name="property_event_time"></a>
#### protected $event_time : 
---
**Type:** 

**Details:**


<a name="property_event_instance"></a>
#### private $event_instance : 
---
**Type:** 

**Details:**


<a name="property_handler"></a>
#### private $handler : 
---
**Type:** 

**Details:**


<a name="property_event_name"></a>
#### private $event_name : 
---
**Type:** 

**Details:**


<a name="property_notices"></a>
#### private $notices : 
---
**Type:** 

**Details:**


<a name="property_event_required"></a>
#### private $event_required : 
---
**Type:** 

**Details:**


<a name="property_user_id"></a>
#### private $user_id : 
---
**Type:** 

**Details:**


<a name="property_threshold_minute"></a>
#### private $threshold_minute : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getEventClass" class="anchor"></a>
#### public getEventClass() 

```
public getEventClass(  $event_name) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $event_name  |  |




<a name="method_setEventName" class="anchor"></a>
#### public setEventName() 

```
public setEventName(  $event_name) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $event_name  |  |




<a name="method_getEventTime" class="anchor"></a>
#### public getEventTime() : integer

```
Static public getEventTime(  $event_name) : integer
```

**Summary**

Returns latest time you ever cached into your event records of a specific event handler type.

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $event_name  |  |

**Returns:** integer - - unix timestamp


<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Singleton runtime instance

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)

**Returns:** null&#124;static


<a name="method_setUserId" class="anchor"></a>
#### public setUserId() 

```
Static public setUserId(  $user_id) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $user_id  |  |




<a name="method_isEventRequired" class="anchor"></a>
#### public isEventRequired() : boolean

```
public isEventRequired() : boolean
```

**Summary**

Validates if a trigger is needed**

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)

**Returns:** boolean - - true will trigger the event.


<a name="method_addNotice" class="anchor"></a>
#### public addNotice() 

```
public addNotice(  $to,   $from,   $message,   $event_type,   $time) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $to  |  |
| <code></code> | $from  |  |
| <code></code> | $message  |  |
| <code></code> | $event_type  |  |
| <code></code> | $time  |  |




<a name="method_renderNotice" class="anchor"></a>
#### public renderNotice() 

```
public renderNotice() 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)




<a name="method_parentNoticeTemplate" class="anchor"></a>
#### public parentNoticeTemplate() 

```
Static public parentNoticeTemplate(  $info) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |




<a name="method_childNoticeTemplate" class="anchor"></a>
#### public childNoticeTemplate() 

```
Static public childNoticeTemplate(  $info) 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |




<a name="method_noNoticeTemplate" class="anchor"></a>
#### public noNoticeTemplate() 

```
public noNoticeTemplate() 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)




<a name="method_getUserId" class="anchor"></a>
#### protected getUserId() 

```
Static protected getUserId() 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)




<a name="method_handleGlobalEvent" class="anchor"></a>
#### protected handleGlobalEvent() 

```
protected handleGlobalEvent() 
```

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)




<a name="method_cacheNotices" class="anchor"></a>
#### private cacheNotices() : array

```
private cacheNotices() : array
```

**Summary**

Cache the last 15 notices of all types of event.

**Details:**
* Inherited From: [\PHPFusion\Event](../classes/PHPFusion.Event.md)

**Returns:** array



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
