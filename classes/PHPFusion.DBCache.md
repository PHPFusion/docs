# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\DBCache
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class DBCache
This class utilizes memory caching for database results.

---
### Constants
* No constants found
---
### Properties
* [private $connect_id](../classes/PHPFusion.DBCache.md#property_connect_id)
* [private $connections](../classes/PHPFusion.DBCache.md#property_connections)
* [private $array_counter](../classes/PHPFusion.DBCache.md#property_array_counter)
* [private $seconds](../classes/PHPFusion.DBCache.md#property_seconds)
---
### Methods
* [public getInstance()](../classes/PHPFusion.DBCache.md#method_getInstance)
* [public flush()](../classes/PHPFusion.DBCache.md#method_flush)
* [public delete()](../classes/PHPFusion.DBCache.md#method_delete)
* [public setSeconds()](../classes/PHPFusion.DBCache.md#method_setSeconds)
* [public dbquery()](../classes/PHPFusion.DBCache.md#method_dbquery)
* [public dbrows()](../classes/PHPFusion.DBCache.md#method_dbrows)
* [public dbarray()](../classes/PHPFusion.DBCache.md#method_dbarray)
* [public dbarraynum()](../classes/PHPFusion.DBCache.md#method_dbarraynum)
* [public dbresult()](../classes/PHPFusion.DBCache.md#method_dbresult)
---
### Details
* File: [classes\PHPFusion\DBCache.php](../files/classes.PHPFusion.DBCache.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\DBCache
---
## Properties
<a name="property_connect_id"></a>
#### private $connect_id : 
---
**Summary**

Instance ID

**Type:** 

**Details:**


<a name="property_connections"></a>
#### private $connections : 
---
**Summary**

Instances

**Type:** 

**Details:**


<a name="property_array_counter"></a>
#### private $array_counter : integer
---
**Summary**

Associative array return counter

**Type:** integer

**Details:**


<a name="property_seconds"></a>
#### private $seconds : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : mixed&amp;#124;static

```
Static public getInstance(string  $connection = &#039;default&#039;) : mixed&amp;#124;static
```

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $connection  |  |

**Returns:** mixed&#124;static


<a name="method_flush" class="anchor"></a>
#### public flush() 

```
public flush() 
```

**Summary**

Runs the flush command
Clears out all cached results

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)




<a name="method_delete" class="anchor"></a>
#### public delete() 

```
public delete(string  $key) 
```

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |




<a name="method_setSeconds" class="anchor"></a>
#### public setSeconds() 

```
public setSeconds(integer  $seconds = 120) 
```

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $seconds  |  |




<a name="method_dbquery" class="anchor"></a>
#### public dbquery() : false&amp;#124;integer&amp;#124;mixed

```
public dbquery(string  $key, string  $query, array  $parameters) : false&amp;#124;integer&amp;#124;mixed
```

**Summary**

Cached query

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $query  |  |
| <code>array</code> | $parameters  |  |

**Returns:** false&#124;integer&#124;mixed


<a name="method_dbrows" class="anchor"></a>
#### public dbrows() : integer

```
public dbrows(mixed  $result) : integer
```

**Summary**

Return number of rows

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** integer


<a name="method_dbarray" class="anchor"></a>
#### public dbarray() : array&amp;#124;null

```
public dbarray(mixed  $result) : array&amp;#124;null
```

**Summary**

Returns associative object array

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array&#124;null


<a name="method_dbarraynum" class="anchor"></a>
#### public dbarraynum() : array&amp;#124;mixed

```
public dbarraynum(mixed  $result) : array&amp;#124;mixed
```

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array&#124;mixed


<a name="method_dbresult" class="anchor"></a>
#### public dbresult() : mixed

```
public dbresult(mixed  $result, string  $column) : mixed
```

**Details:**
* Inherited From: [\PHPFusion\DBCache](../classes/PHPFusion.DBCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |
| <code>string</code> | $column  |  |

**Returns:** mixed



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
