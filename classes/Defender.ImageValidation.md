# [PHPFusion Docs](../home.md)

# Class: \Defender\ImageValidation
### Namespace: [\Defender](../namespaces/Defender.md)
---
**Summary:**

Class Mimecheck
Check file types of the uploaded file with known mime types list to
prevent uploading unwanted files if enabled. This feature is to detect payload
in image extensions that has been partly encoded.

---
### Constants
* No constants found
---
### Properties
---
### Methods
* [public ValidateExtensions()](../classes/Defender.ImageValidation.md#method_ValidateExtensions)
* [public mime_check()](../classes/Defender.ImageValidation.md#method_mime_check)
* [private in_array_r()](../classes/Defender.ImageValidation.md#method_in_array_r)
---
### Details
* File: [defender\mimecheck.php](../files/defender.mimecheck.md)
* Package: Default
* Class Hierarchy:
  * \Defender\ImageValidation

---
## Methods
<a name="method_ValidateExtensions" class="anchor"></a>
#### public ValidateExtensions() 

```
Static public ValidateExtensions() 
```

**Summary**

Check extensions only. This will not check against mimetype header

**Details:**
* Inherited From: [\Defender\ImageValidation](../classes/Defender.ImageValidation.md)




<a name="method_mime_check" class="anchor"></a>
#### public mime_check() : boolean

```
Static public mime_check(  $file_src,   $file_ext,   $valid_ext) : boolean
```

**Summary**

Check for alteration of file extensions to prevent unwanted payload executions
https://securelist.com/blog/virus-watch/74297/png-embedded-malicious-payload-hidden-in-a-png-file/

**Details:**
* Inherited From: [\Defender\ImageValidation](../classes/Defender.ImageValidation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $file_src  | - the tmp src file |
| <code></code> | $file_ext  | - the current tmp src file extensions |
| <code></code> | $valid_ext  | - all accepted file extensions |

**Returns:** boolean


<a name="method_in_array_r" class="anchor"></a>
#### private in_array_r() 

```
Static private in_array_r(  $needle,   $haystack,   $strict = FALSE) 
```

**Details:**
* Inherited From: [\Defender\ImageValidation](../classes/Defender.ImageValidation.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $needle  |  |
| <code></code> | $haystack  |  |
| <code></code> | $strict  |  |





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
