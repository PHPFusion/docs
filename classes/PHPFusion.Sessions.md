# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Sessions
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Sessions

**Description:**

You must call session_set_save_handler() prior to calling session_start(), but you can define the functions themselves anywhere.
The real beauty of this approach is that you don't have to modify your code or the way you use sessions in any way.
$_SESSION still exists and behaves the same way, PHP still takes care of generating and propagating the session identifier,
and changes made to session configuration directives still apply. All you have to do is call this one function.

---
### Constants
* No constants found
---
### Properties
* [private $_sess](../classes/PHPFusion.Sessions.md#property__sess)
* [private $db_info](../classes/PHPFusion.Sessions.md#property_db_info)
* [private $_sess_key](../classes/PHPFusion.Sessions.md#property__sess_key)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Sessions.md#method_getInstance)
* [public getId()](../classes/PHPFusion.Sessions.md#method_getId)
* [public setConfig()](../classes/PHPFusion.Sessions.md#method_setConfig)
* [public _open()](../classes/PHPFusion.Sessions.md#method__open)
* [public _close()](../classes/PHPFusion.Sessions.md#method__close)
* [public _read()](../classes/PHPFusion.Sessions.md#method__read)
* [public _write()](../classes/PHPFusion.Sessions.md#method__write)
* [public _destroy()](../classes/PHPFusion.Sessions.md#method__destroy)
* [public _purge()](../classes/PHPFusion.Sessions.md#method__purge)
* [public _clean()](../classes/PHPFusion.Sessions.md#method__clean)
* [public remote_cache()](../classes/PHPFusion.Sessions.md#method_remote_cache)
* [private __construct()](../classes/PHPFusion.Sessions.md#method___construct)
* [private connection()](../classes/PHPFusion.Sessions.md#method_connection)
* [private __clone()](../classes/PHPFusion.Sessions.md#method___clone)
---
### Details
* File: [classes\PHPFusion\Sessions.php](../files/classes.PHPFusion.Sessions.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Sessions
---
## Properties
<a name="property__sess"></a>
#### private $_sess : 
---
**Type:** 

**Details:**


<a name="property_db_info"></a>
#### private $db_info : 
---
**Type:** 

**Details:**


<a name="property__sess_key"></a>
#### private $_sess_key : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $handler) : static
```

**Summary**

Get an instance by key

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $handler  |  |

**Returns:** static


<a name="method_getId" class="anchor"></a>
#### public getId() 

```
public getId() 
```

**Summary**

Methods to fetch the ID from the session.

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)




<a name="method_setConfig" class="anchor"></a>
#### public setConfig() : $this

```
public setConfig(  $db_host,   $db_user,   $db_pass,   $db_name,   $db_port = 3306) : $this
```

**Summary**

Set db configuration values

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $db_host  |  |
| <code></code> | $db_user  |  |
| <code></code> | $db_pass  |  |
| <code></code> | $db_name  |  |
| <code></code> | $db_port  |  |

**Returns:** $this


<a name="method__open" class="anchor"></a>
#### public _open() : boolean

```
public _open() : boolean
```

**Summary**

The _open() and _close() functions are closely related. These are used to open the session data store and close it, respectively.

**Description**

If you are storing sessions in the filesystem, these functions open and close files
(and you likely need to use a global variable for the file handler, so that the other session functions can use it).

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)

**Returns:** boolean


<a name="method__close" class="anchor"></a>
#### public _close() 

```
public _close() 
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)




<a name="method__read" class="anchor"></a>
#### public _read() : string

```
public _read(string  $name) : string
```

**Summary**

Read and fetches the data from a session
The _read() function is called whenever PHP needs to read the session data.

**Description**

This takes place immediately after _open(), and both are a direct result of your use of session_start().

PHP expects the session data in return, and you don't have to worry about the format, because
PHP provides the data to the _write() function (covered in the next section) in the same format that it expects it.
Thus, this function returns exactly what is in the data column for the matching record.

Note: The handler PHP uses to handle data serialization is defined by the session.serialize_handler configuration directive. It is set to php by default.

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |

**Returns:** string


<a name="method__write" class="anchor"></a>
#### public _write() : boolean

```
public _write(string  $name, mixed  $data) : boolean
```

**Summary**

Write a session

**Description**

The _write() function is called whenever PHP needs to write the session data. This takes place at the very end of the script.
PHP passes this function the session identifier and the session data.

You don't need to worry with the format of the data - PHP serializes it, so that you can treat it like a string.
However, PHP does not modify it beyond this, so you want to properly escape it before using it in a query.

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>mixed</code> | $data  |  |

**Returns:** boolean


<a name="method__destroy" class="anchor"></a>
#### public _destroy() : boolean

```
public _destroy(string  $name) : boolean
```

**Summary**

Destroys a session

**Description**

The _destroy() function is called whenever PHP needs to destroy all session data associated with a specific session identifier.
An obvious example is when you call session__destroy().

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |

**Returns:** boolean


<a name="method__purge" class="anchor"></a>
#### public _purge() : boolean

```
public _purge() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)

**Returns:** boolean


<a name="method__clean" class="anchor"></a>
#### public _clean() : boolean

```
public _clean(integer  $max) : boolean
```

**Summary**

Clear the session gc

**Description**

The _clean() function is called every once in a while in order to clean out (delete) old records in the session data store.
More specifically, the frequency in which this function is called is determined by two configuration directives,
session.gc_probability and session.gc_divisor.

The default values for these are 1 and 1000, respectively, which means there is a 1 in 1000 (0.1%) chance for this function to be called per session initialization.
Because the _write() function keeps the timestamp of the last access in the access column for each record,
this can be used to determine which records to delete. PHP passes the maximum number of seconds allowed before a session is to be considered expired.

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $max  | The value that PHP passes to this function comes directly from the session.gc_maxlifetime configuration directive.
You can actually ignore this and determine your own maximum lifetime allowed, but it is much better to adhere to the value PHP passes.
Doing so better adheres to the idea of transparently changing the storage mechanism.
From a developer's perspective, the behavior of sessions should not change. |

**Returns:** boolean


<a name="method_remote_cache" class="anchor"></a>
#### public remote_cache() 

```
public remote_cache(string  $path) 
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $path  |  |




<a name="method___construct" class="anchor"></a>
#### private __construct() 

```
private __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)




<a name="method_connection" class="anchor"></a>
#### private connection() : array

```
private connection() : array
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)

**Returns:** array


<a name="method___clone" class="anchor"></a>
#### private __clone() 

```
private __clone() 
```

**Details:**
* Inherited From: [\PHPFusion\Sessions](../classes/PHPFusion.Sessions.md)





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
