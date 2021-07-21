# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Locale
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Locale

**Description:**

Locale Handling
We set a new global.php when the class initialize automatically so this will only be loaded once
Implemented at core_functions_include.php

---
### Constants
* No constants found
---
### Properties
* [private $locale_file](../classes/PHPFusion.Locale.md#property_locale_file)
* [private $locale](../classes/PHPFusion.Locale.md#property_locale)
* [private $instances](../classes/PHPFusion.Locale.md#property_instances)
---
### Methods
* [public getInstance()](../classes/PHPFusion.Locale.md#method_getInstance)
* [public loadLocaleFile()](../classes/PHPFusion.Locale.md#method_loadLocaleFile)
* [public getLoadedFiles()](../classes/PHPFusion.Locale.md#method_getLoadedFiles)
* [public setLocale()](../classes/PHPFusion.Locale.md#method_setLocale)
* [public getLocale()](../classes/PHPFusion.Locale.md#method_getLocale)
* [public formatWord()](../classes/PHPFusion.Locale.md#method_formatWord)
* [public translateCountryNames()](../classes/PHPFusion.Locale.md#method_translateCountryNames)
* [public translateLangNames()](../classes/PHPFusion.Locale.md#method_translateLangNames)
* [public getIso()](../classes/PHPFusion.Locale.md#method_getIso)
* [public format_word()](../classes/PHPFusion.Locale.md#method_format_word) - (deprecated)
---
### Details
* File: [classes\PHPFusion\Locale.php](../files/classes.PHPFusion.Locale.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Locale
---
## Properties
<a name="property_locale_file"></a>
#### private $locale_file : 
---
**Type:** 

**Details:**


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**


<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $key = &#039;default&#039;) : static
```

**Summary**

Get locale instance by key

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_loadLocaleFile" class="anchor"></a>
#### public loadLocaleFile() 

```
Static public loadLocaleFile(string  $filename) 
```

**Summary**

Includes a locale file and logs a trace

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filename  |  |




<a name="method_getLoadedFiles" class="anchor"></a>
#### public getLoadedFiles() 

```
Static public getLoadedFiles() 
```

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)




<a name="method_setLocale" class="anchor"></a>
#### public setLocale() 

```
Static public setLocale(string&amp;#124;array  $include_file) 
```

**Summary**

Iinclude a new locale file

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $include_file  | Can be an array or a string |




<a name="method_getLocale" class="anchor"></a>
#### public getLocale() : array&amp;#124;mixed&amp;#124;string

```
public getLocale(string  $key = NULL) : array&amp;#124;mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array&#124;mixed&#124;string


<a name="method_formatWord" class="anchor"></a>
#### public formatWord() : string

```
Static public formatWord(integer  $count, string  $words, array  $options = array()) : string
```

**Summary**

Returns a grammatical number word.

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $count  | Number of items. |
| <code>string</code> | $words  | A string consisting of singular and plural delimited by a | symbol. |
| <code>array</code> | $options  |  |

**Returns:** string


<a name="method_translateCountryNames" class="anchor"></a>
#### public translateCountryNames() : string

```
Static public translateCountryNames(string  $country) : string
```

**Summary**

Given English as base, find out the localized version

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $country  |  |

**Returns:** string


<a name="method_translateLangNames" class="anchor"></a>
#### public translateLangNames() : array&amp;#124;string

```
Static public translateLangNames(string  $key = NULL) : array&amp;#124;string
```

**Summary**

Attempt to translate Locale Folder Name into Localized language
or return the locale folder name by default.

**Description**

If key is not set, return a full array

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array&#124;string


<a name="method_getIso" class="anchor"></a>
#### public getIso() : array&amp;#124;integer&amp;#124;string&amp;#124;null

```
Static public getIso(null  $key = NULL, boolean  $iso_to_lang = TRUE) : array&amp;#124;integer&amp;#124;string&amp;#124;null
```

**Summary**

ISO-639 translator

**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>null</code> | $key  |  |
| <code>boolean</code> | $iso_to_lang  | set false to translate iso-folder, default folder-iso |

**Returns:** array&#124;integer&#124;string&#124;null


<a name="method_format_word" class="anchor"></a>
#### (deprecated) - public format_word() : string

```
Static public format_word(integer  $count, string  $words, array  $options = array()) : string
```

**Deprecated**
Deprecateduse format_word()
**Details:**
* Inherited From: [\PHPFusion\Locale](../classes/PHPFusion.Locale.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $count  |  |
| <code>string</code> | $words  | 'member|members'; |
| <code>array</code> | $options  |  |

**Returns:** string



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
