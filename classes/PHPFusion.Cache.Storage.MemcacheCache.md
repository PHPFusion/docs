# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Cache\Storage\MemcacheCache
### Namespace: [\PHPFusion\Cache\Storage](../namespaces/PHPFusion.Cache.Storage.md)
---
**Summary:**

Class MemcacheCache

---
### Constants
* No constants found
---
### Properties
* [private $memcache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#property_memcache)
* [private $connection](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#property_connection)
* [private $is_memcached](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#property_is_memcached)
---
### Methods
* [public __construct()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method___construct)
* [public isConnected()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method_isConnected)
* [public set()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method_set)
* [public get()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method_get)
* [public delete()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method_delete)
* [public flush()](../classes/PHPFusion.Cache.Storage.MemcacheCache.md#method_flush)
---
### Details
* File: [classes\PHPFusion\Cache\Storage\MemcacheCache.php](../files/classes.PHPFusion.Cache.Storage.MemcacheCache.md)
* Package: Cache\Storage
* Class Hierarchy:
  * \PHPFusion\Cache\Storage\MemcacheCache
* Implements:
  * [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)
---
## Properties
<a name="property_memcache"></a>
#### private $memcache : \Memcache
---
**Type:** \Memcache

**Details:**


<a name="property_connection"></a>
#### private $connection : boolean
---
**Type:** boolean

**Details:**


<a name="property_is_memcached"></a>
#### private $is_memcached : boolean
---
**Type:** boolean

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct(array  $config) 
```

**Summary**

MemcacheCache constructor.

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $config  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Cache\CacheException |  |




<a name="method_isConnected" class="anchor"></a>
#### public isConnected() : boolean

```
public isConnected() : boolean
```

**Summary**

Check connection

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)

**Returns:** boolean


<a name="method_set" class="anchor"></a>
#### public set() 

```
public set(string  $key, mixed  $data, integer  $seconds = NULL) 
```

**Summary**

Save data in cache

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | cache key |
| <code>mixed</code> | $data  |  |
| <code>integer</code> | $seconds  |  |




<a name="method_get" class="anchor"></a>
#### public get() : array&amp;#124;false&amp;#124;string

```
public get(string  $key) : array&amp;#124;false&amp;#124;string
```

**Summary**

Return data by key

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array&#124;false&#124;string


<a name="method_delete" class="anchor"></a>
#### public delete() 

```
public delete(string  $key) 
```

**Summary**

Delete data from cache

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |




<a name="method_flush" class="anchor"></a>
#### public flush() 

```
public flush() 
```

**Summary**

Delete all data from cache

**Details:**
* Inherited From: [\PHPFusion\Cache\Storage\MemcacheCache](../classes/PHPFusion.Cache.Storage.MemcacheCache.md)





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
