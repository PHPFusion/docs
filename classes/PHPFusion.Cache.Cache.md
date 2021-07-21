# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Cache\Cache
### Namespace: [\PHPFusion\Cache](../namespaces/PHPFusion.Cache.md)
---
**Summary:**

Class Cache

---
### Constants
* No constants found
---
### Properties
* [protected $instance](../classes/PHPFusion.Cache.Cache.md#property_instance)
* [private $cache](../classes/PHPFusion.Cache.Cache.md#property_cache)
* [private $cache_storage](../classes/PHPFusion.Cache.Cache.md#property_cache_storage)
---
### Methods
* [public __construct()](../classes/PHPFusion.Cache.Cache.md#method___construct)
* [public init()](../classes/PHPFusion.Cache.Cache.md#method_init)
* [public getInstance()](../classes/PHPFusion.Cache.Cache.md#method_getInstance)
* [public getStorageType()](../classes/PHPFusion.Cache.Cache.md#method_getStorageType)
* [public isConnected()](../classes/PHPFusion.Cache.Cache.md#method_isConnected)
* [public set()](../classes/PHPFusion.Cache.Cache.md#method_set)
* [public get()](../classes/PHPFusion.Cache.Cache.md#method_get)
* [public delete()](../classes/PHPFusion.Cache.Cache.md#method_delete)
* [public flush()](../classes/PHPFusion.Cache.Cache.md#method_flush)
* [private getCacheConfig()](../classes/PHPFusion.Cache.Cache.md#method_getCacheConfig)
---
### Details
* File: [classes\PHPFusion\Cache\Cache.php](../files/classes.PHPFusion.Cache.Cache.md)
* Package: PHPFusion\Cache
* Class Hierarchy:
  * \PHPFusion\Cache\Cache
---
## Properties
<a name="property_instance"></a>
#### protected $instance : mixed
---
**Type:** mixed

**Details:**


<a name="property_cache"></a>
#### private $cache : object
---
**Summary**

Class name

**Type:** object

**Details:**


<a name="property_cache_storage"></a>
#### private $cache_storage : string
---
**Summary**

Current storage

**Type:** string

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct(string  $cache_storage = NULL) 
```

**Summary**

Cache constructor.

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)
* Uses:
 * [\PHPFusion\Cache\Storage\FileCache]()
 * [\PHPFusion\Cache\Storage\RedisCache]()
 * [\PHPFusion\Cache\Storage\MemcacheCache]()
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $cache_storage  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Cache\CacheException |  |




<a name="method_init" class="anchor"></a>
#### public init() 

```
public init() 
```

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Cache\CacheException |  |




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : mixed&amp;#124;\PHPFusion\Cache\Cache

```
Static public getInstance() : mixed&amp;#124;\PHPFusion\Cache\Cache
```

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)

**Returns:** mixed&#124;<a href="../classes/PHPFusion.Cache.Cache.html">\PHPFusion\Cache\Cache</a>


<a name="method_getStorageType" class="anchor"></a>
#### public getStorageType() : string

```
public getStorageType() : string
```

**Summary**

Get current storage type

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)

**Returns:** string


<a name="method_isConnected" class="anchor"></a>
#### public isConnected() : mixed

```
public isConnected() : mixed
```

**Summary**

Check connection

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)

**Returns:** mixed


<a name="method_set" class="anchor"></a>
#### public set() 

```
public set(string  $key, mixed  $data, integer  $seconds = NULL) 
```

**Summary**

Save data in cache

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | cache key |
| <code>mixed</code> | $data  |  |
| <code>integer</code> | $seconds  |  |




<a name="method_get" class="anchor"></a>
#### public get() : mixed

```
public get(string  $key) : mixed
```

**Summary**

Return data by key

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** mixed


<a name="method_delete" class="anchor"></a>
#### public delete() 

```
public delete(string  $key) 
```

**Summary**

Delete data from cache

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)
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
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)




<a name="method_getCacheConfig" class="anchor"></a>
#### private getCacheConfig() : array

```
private getCacheConfig() : array
```

**Summary**

Get cache config

**Details:**
* Inherited From: [\PHPFusion\Cache\Cache](../classes/PHPFusion.Cache.Cache.md)

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
