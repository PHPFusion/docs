# [PHPFusion Docs](../home.md)

# Interface: ICache
### Namespace: [\PHPFusion\Cache](../namespaces/PHPFusion.Cache.md)
---
---
### Constants
* No constants found
---
### Methods
* [public isConnected()](../classes/PHPFusion.Cache.ICache.md#method_isConnected)
* [public set()](../classes/PHPFusion.Cache.ICache.md#method_set)
* [public get()](../classes/PHPFusion.Cache.ICache.md#method_get)
* [public delete()](../classes/PHPFusion.Cache.ICache.md#method_delete)
* [public flush()](../classes/PHPFusion.Cache.ICache.md#method_flush)

---
### Details
* File: [classes\PHPFusion\Cache\ICache.php](../files/classes.PHPFusion.Cache.ICache.md)
* Package: \Default
---
## Methods
<a name="method_isConnected" class="anchor"></a>
#### public isConnected() : mixed&amp;#124;boolean

```
public isConnected() : mixed&amp;#124;boolean
```

**Summary**

Check connection

**Details:**
* Inherited From: [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)

**Returns:** mixed&#124;boolean


<a name="method_set" class="anchor"></a>
#### public set() 

```
public set(string  $key, mixed  $data, integer  $seconds) 
```

**Summary**

Save data in cache

**Details:**
* Inherited From: [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)
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
* Inherited From: [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)
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
* Inherited From: [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)
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
* Inherited From: [\PHPFusion\Cache\ICache](../classes/PHPFusion.Cache.ICache.md)






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
