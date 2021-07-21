# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Geomap
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Geomap

---
### Constants
* No constants found
---
### Properties
* [public $country_list](../classes/PHPFusion.Geomap.md#property_country_list)
* [public $currency_list](../classes/PHPFusion.Geomap.md#property_currency_list)
---
### Methods
* [public callingCodes()](../classes/PHPFusion.Geomap.md#method_callingCodes)
* [public currency()](../classes/PHPFusion.Geomap.md#method_currency)
* [public countryCodeLoLocale()](../classes/PHPFusion.Geomap.md#method_countryCodeLoLocale)
* [private getCountryResource()](../classes/PHPFusion.Geomap.md#method_getCountryResource)
---
### Details
* File: [classes\PHPFusion\Geomap.php](../files/classes.PHPFusion.Geomap.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Geomap
---
## Properties
<a name="property_country_list"></a>
#### public $country_list : 
---
**Type:** 

**Details:**


<a name="property_currency_list"></a>
#### public $currency_list : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_callingCodes" class="anchor"></a>
#### public callingCodes() : array&amp;#124;mixed&amp;#124;null

```
public callingCodes(string  $country = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Geomap](../classes/PHPFusion.Geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $country  |  |

**Returns:** array&#124;mixed&#124;null


<a name="method_currency" class="anchor"></a>
#### public currency() : array&amp;#124;null

```
public currency(string  $country_code = NULL) : array&amp;#124;null
```

**Summary**

Returns countries

**Details:**
* Inherited From: [\PHPFusion\Geomap](../classes/PHPFusion.Geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $country_code  | ISO cca2 code / returns array if NULL |

**Returns:** array&#124;null


<a name="method_countryCodeLoLocale" class="anchor"></a>
#### public countryCodeLoLocale() 

```
Static public countryCodeLoLocale(string  $country_code, string  $language_code = &#039;&#039;) 
```

**Summary**

Returns a locale from a country code that is provided.

**Description**

I have not think of an implementation benefits out of this yet.

**Details:**
* Inherited From: [\PHPFusion\Geomap](../classes/PHPFusion.Geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $country_code  | ISO 3166-2-alpha 2 country code |
| <code>string</code> | $language_code  | ISO 639-1-alpha 2 language code |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| returns |  | string a locale, formatted like en_US, or null if not found |

<a name="method_getCountryResource" class="anchor"></a>
#### private getCountryResource() : mixed&amp;#124;string

```
private getCountryResource() : mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Geomap](../classes/PHPFusion.Geomap.md)

**Returns:** mixed&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| todo |  | : countries.json information to geo.countries.php |


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
