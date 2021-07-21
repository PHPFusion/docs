# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\httpdownload
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
---
### Constants
* No constants found
---
### Properties
* [public $data](../classes/PHPFusion.httpdownload.md#property_data)
* [public $data_len](../classes/PHPFusion.httpdownload.md#property_data_len)
* [public $data_mod](../classes/PHPFusion.httpdownload.md#property_data_mod)
* [public $data_type](../classes/PHPFusion.httpdownload.md#property_data_type)
* [public $data_section](../classes/PHPFusion.httpdownload.md#property_data_section)
* [public $handler](../classes/PHPFusion.httpdownload.md#property_handler)
* [public $use_resume](../classes/PHPFusion.httpdownload.md#property_use_resume)
* [public $use_autoexit](../classes/PHPFusion.httpdownload.md#property_use_autoexit)
* [public $use_auth](../classes/PHPFusion.httpdownload.md#property_use_auth)
* [public $filename](../classes/PHPFusion.httpdownload.md#property_filename)
* [public $mime](../classes/PHPFusion.httpdownload.md#property_mime)
* [public $bufsize](../classes/PHPFusion.httpdownload.md#property_bufsize)
* [public $seek_start](../classes/PHPFusion.httpdownload.md#property_seek_start)
* [public $seek_end](../classes/PHPFusion.httpdownload.md#property_seek_end)
* [public $bandwidth](../classes/PHPFusion.httpdownload.md#property_bandwidth)
* [public $speed](../classes/PHPFusion.httpdownload.md#property_speed)
---
### Methods
* [public download_ex()](../classes/PHPFusion.httpdownload.md#method_download_ex)
* [public initialize()](../classes/PHPFusion.httpdownload.md#method_initialize)
* [public _auth()](../classes/PHPFusion.httpdownload.md#method__auth)
* [public header()](../classes/PHPFusion.httpdownload.md#method_header)
* [public download()](../classes/PHPFusion.httpdownload.md#method_download)
* [public set_byfile()](../classes/PHPFusion.httpdownload.md#method_set_byfile)
* [public set_bydata()](../classes/PHPFusion.httpdownload.md#method_set_bydata)
* [public set_byurl()](../classes/PHPFusion.httpdownload.md#method_set_byurl)
* [public set_filename()](../classes/PHPFusion.httpdownload.md#method_set_filename)
* [public set_mime()](../classes/PHPFusion.httpdownload.md#method_set_mime)
* [public set_lastmodtime()](../classes/PHPFusion.httpdownload.md#method_set_lastmodtime)
---
### Details
* File: [class.httpdownload.php](../files/class.httpdownload.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\httpdownload
---
## Properties
<a name="property_data"></a>
#### public $data : 
---
**Type:** 

**Details:**


<a name="property_data_len"></a>
#### public $data_len : 
---
**Type:** 

**Details:**


<a name="property_data_mod"></a>
#### public $data_mod : 
---
**Type:** 

**Details:**


<a name="property_data_type"></a>
#### public $data_type : 
---
**Type:** 

**Details:**


<a name="property_data_section"></a>
#### public $data_section : 
---
**Type:** 

**Details:**


<a name="property_handler"></a>
#### public $handler : array
---
**Type:** array
ObjectHandler
**Details:**


<a name="property_use_resume"></a>
#### public $use_resume : 
---
**Type:** 

**Details:**


<a name="property_use_autoexit"></a>
#### public $use_autoexit : 
---
**Type:** 

**Details:**


<a name="property_use_auth"></a>
#### public $use_auth : 
---
**Type:** 

**Details:**


<a name="property_filename"></a>
#### public $filename : 
---
**Type:** 

**Details:**


<a name="property_mime"></a>
#### public $mime : 
---
**Type:** 

**Details:**


<a name="property_bufsize"></a>
#### public $bufsize : 
---
**Type:** 

**Details:**


<a name="property_seek_start"></a>
#### public $seek_start : 
---
**Type:** 

**Details:**


<a name="property_seek_end"></a>
#### public $seek_end : 
---
**Type:** 

**Details:**


<a name="property_bandwidth"></a>
#### public $bandwidth : integer
---
**Summary**

Total bandwidth has been used for this download

**Type:** integer

**Details:**


<a name="property_speed"></a>
#### public $speed : float
---
**Summary**

Speed limit

**Type:** float

**Details:**



---
## Methods
<a name="method_download_ex" class="anchor"></a>
#### public download_ex() 

```
public download_ex(  $size) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $size  |  |




<a name="method_initialize" class="anchor"></a>
#### public initialize() : boolean

```
public initialize() : boolean
```

**Summary**

Check authentication and get seek position

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)

**Returns:** boolean


<a name="method__auth" class="anchor"></a>
#### public _auth() : boolean

```
public _auth() : boolean
```

**Summary**

Check authentication

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)

**Returns:** boolean


<a name="method_header" class="anchor"></a>
#### public header() 

```
public header(  $size, null  $seek_start = NULL, null  $seek_end = NULL) 
```

**Summary**

Send download information header

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $size  |  |
| <code>null</code> | $seek_start  |  |
| <code>null</code> | $seek_end  |  |




<a name="method_download" class="anchor"></a>
#### public download() : boolean

```
public download() : boolean
```

**Summary**

Start download

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)

**Returns:** boolean


<a name="method_set_byfile" class="anchor"></a>
#### public set_byfile() 

```
public set_byfile(  $dir) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $dir  |  |




<a name="method_set_bydata" class="anchor"></a>
#### public set_bydata() 

```
public set_bydata(  $data) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $data  |  |




<a name="method_set_byurl" class="anchor"></a>
#### public set_byurl() 

```
public set_byurl(  $data) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $data  |  |




<a name="method_set_filename" class="anchor"></a>
#### public set_filename() 

```
public set_filename(  $filename) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $filename  |  |




<a name="method_set_mime" class="anchor"></a>
#### public set_mime() 

```
public set_mime(  $mime) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $mime  |  |




<a name="method_set_lastmodtime" class="anchor"></a>
#### public set_lastmodtime() 

```
public set_lastmodtime(  $time) 
```

**Details:**
* Inherited From: [\PHPFusion\httpdownload](../classes/PHPFusion.httpdownload.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $time  |  |





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
