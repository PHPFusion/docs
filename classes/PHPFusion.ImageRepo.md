# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\ImageRepo
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

A class to handle imagepaths

---
### Constants
* No constants found
---
### Properties
* [private $image_paths](../classes/PHPFusion.ImageRepo.md#property_image_paths)
* [private $cached](../classes/PHPFusion.ImageRepo.md#property_cached)
* [private $smiley_cache](../classes/PHPFusion.ImageRepo.md#property_smiley_cache)
---
### Methods
* [public getImagePaths()](../classes/PHPFusion.ImageRepo.md#method_getImagePaths)
* [public getImage()](../classes/PHPFusion.ImageRepo.md#method_getImage)
* [public setImage()](../classes/PHPFusion.ImageRepo.md#method_setImage)
* [public replaceInAllPath()](../classes/PHPFusion.ImageRepo.md#method_replaceInAllPath)
* [public getFileList()](../classes/PHPFusion.ImageRepo.md#method_getFileList)
* [public cacheSmileys()](../classes/PHPFusion.ImageRepo.md#method_cacheSmileys)
* [private cache()](../classes/PHPFusion.ImageRepo.md#method_cache)
---
### Details
* File: [classes\PHPFusion\ImageRepo.php](../files/classes.PHPFusion.ImageRepo.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\ImageRepo
---
## Properties
<a name="property_image_paths"></a>
#### private $image_paths : array&lt;mixed,string&gt;
---
**Summary**

All cached paths

**Type:** array&lt;mixed,string&gt;

**Details:**


<a name="property_cached"></a>
#### private $cached : boolean
---
**Summary**

The state of the cache

**Type:** boolean

**Details:**


<a name="property_smiley_cache"></a>
#### private $smiley_cache : 
---
**Summary**

Cache installed smiley images from database

**Type:** 

**Details:**

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| return |  |  |


---
## Methods
<a name="method_getImagePaths" class="anchor"></a>
#### public getImagePaths() : array&lt;mixed,string&gt;

```
Static public getImagePaths() : array&lt;mixed,string&gt;
```

**Summary**

Get all imagepaths

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)

**Returns:** array&lt;mixed,string&gt;


<a name="method_getImage" class="anchor"></a>
#### public getImage() : string

```
Static public getImage(string  $image, string  $alt = &quot;&quot;, string  $style = &quot;&quot;, string  $title = &quot;&quot;, string  $atts = &quot;&quot;) : string
```

**Summary**

Get the imagepath or the html "img" tag

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $image  | The name of the image. |
| <code>string</code> | $alt  | "alt" attribute of the image |
| <code>string</code> | $style  | "style" attribute of the image |
| <code>string</code> | $title  | "title" attribute of the image |
| <code>string</code> | $atts  | Custom attributes of the image |

**Returns:** string - The path of the image if the first argument is given,
but others not. Otherwise the html "img" tag


<a name="method_setImage" class="anchor"></a>
#### public setImage() 

```
Static public setImage(string  $name, string  $path) 
```

**Summary**

Set a path of an image

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>string</code> | $path  |  |




<a name="method_replaceInAllPath" class="anchor"></a>
#### public replaceInAllPath() 

```
Static public replaceInAllPath(string  $source, string  $target) 
```

**Summary**

Replace a part in each path

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source  |  |
| <code>string</code> | $target  |  |




<a name="method_getFileList" class="anchor"></a>
#### public getFileList() : array

```
Static public getFileList(string  $path) : array
```

**Summary**

Given a path, returns an array of all files

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $path  |  |

**Returns:** array


<a name="method_cacheSmileys" class="anchor"></a>
#### public cacheSmileys() 

```
Static public cacheSmileys() 
```

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)




<a name="method_cache" class="anchor"></a>
#### private cache() 

```
Static private cache() 
```

**Summary**

Fetch and cache all off the imagepaths

**Details:**
* Inherited From: [\PHPFusion\ImageRepo](../classes/PHPFusion.ImageRepo.md)





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
