# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\BreadCrumbs
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class BreadCrumbs

**Description:**

Get instances by keys:
$bcDefault = BreadCrumbs::getInstance();
$bcCustom = BreadCrumbs::getInstance('custom');

Hide the home of $bcCustom
$bcCustom->hideHome();

Set the last breadcrumb clickable (it is rendered as a simple text by default)
$bcCustom->setLastClicklable();
You can override the default CSS classes of the wrapper HTML node
$bcCustom->setCssClasses('breadcrumb-custom');

Be careful! If you want to add a new class, use this method
$bcCustom->addCssClasses('additional-class1 additional-class2');

Get the items as associative arrays
$itemsDefault = $bcDefault->toArray();
$itemsCustom = $bcCustom->toArray();

---
### Constants
* No constants found
---
### Properties
* [private $instances](../classes/PHPFusion.BreadCrumbs.md#property_instances)
* [private $breadcrumbs](../classes/PHPFusion.BreadCrumbs.md#property_breadcrumbs)
* [private $showHome](../classes/PHPFusion.BreadCrumbs.md#property_showHome)
* [private $isLastClickable](../classes/PHPFusion.BreadCrumbs.md#property_isLastClickable)
* [private $cssClasses](../classes/PHPFusion.BreadCrumbs.md#property_cssClasses)
---
### Methods
* [public __construct()](../classes/PHPFusion.BreadCrumbs.md#method___construct)
* [public addBreadCrumb()](../classes/PHPFusion.BreadCrumbs.md#method_addBreadCrumb)
* [public getInstance()](../classes/PHPFusion.BreadCrumbs.md#method_getInstance)
* [public addCssClasses()](../classes/PHPFusion.BreadCrumbs.md#method_addCssClasses)
* [public getCssClasses()](../classes/PHPFusion.BreadCrumbs.md#method_getCssClasses)
* [public setCssClasses()](../classes/PHPFusion.BreadCrumbs.md#method_setCssClasses)
* [public hideHome()](../classes/PHPFusion.BreadCrumbs.md#method_hideHome)
* [public showHome()](../classes/PHPFusion.BreadCrumbs.md#method_showHome)
* [public setLastClickable()](../classes/PHPFusion.BreadCrumbs.md#method_setLastClickable)
* [public toArray()](../classes/PHPFusion.BreadCrumbs.md#method_toArray)
* [public isHomeShown()](../classes/PHPFusion.BreadCrumbs.md#method_isHomeShown)
* [public isLastClickable()](../classes/PHPFusion.BreadCrumbs.md#method_isLastClickable)
---
### Details
* File: [classes\PHPFusion\BreadCrumbs.php](../files/classes.PHPFusion.BreadCrumbs.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\BreadCrumbs
---
## Properties
<a name="property_instances"></a>
#### private $instances : array&lt;mixed,static&gt;
---
**Type:** array&lt;mixed,static&gt;

**Details:**


<a name="property_breadcrumbs"></a>
#### private $breadcrumbs : array
---
**Type:** array

**Details:**


<a name="property_showHome"></a>
#### private $showHome : boolean
---
**Summary**

Whether to add the 'Home' link

**Type:** boolean

**Details:**


<a name="property_isLastClickable"></a>
#### private $isLastClickable : boolean
---
**Summary**

Whether to make last breadcrumb a link

**Type:** boolean

**Details:**


<a name="property_cssClasses"></a>
#### private $cssClasses : string
---
**Summary**

The class wrapping the breacrumbs

**Type:** string

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)




<a name="method_addBreadCrumb" class="anchor"></a>
#### public addBreadCrumb() : static

```
public addBreadCrumb(array  $link) : static
```

**Summary**

Add a link to the breadcrumb

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $link  | Keys: link, title |

**Returns:** static


<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : static

```
Static public getInstance(string  $key = &#039;default&#039;) : static
```

**Summary**

Get an instance by key

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_addCssClasses" class="anchor"></a>
#### public addCssClasses() : static

```
public addCssClasses(string  $classes) : static
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $classes  |  |

**Returns:** static


<a name="method_getCssClasses" class="anchor"></a>
#### public getCssClasses() : string

```
public getCssClasses() : string
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)

**Returns:** string


<a name="method_setCssClasses" class="anchor"></a>
#### public setCssClasses() : static

```
public setCssClasses(string  $classes) : static
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $classes  |  |

**Returns:** static


<a name="method_hideHome" class="anchor"></a>
#### public hideHome() : static

```
public hideHome() : static
```

**Summary**

Hide the link to home page

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)

**Returns:** static


<a name="method_showHome" class="anchor"></a>
#### public showHome() : static

```
public showHome(boolean  $state = TRUE) : static
```

**Summary**

Show or hide the link to home page

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $state  |  |

**Returns:** static


<a name="method_setLastClickable" class="anchor"></a>
#### public setLastClickable() : static

```
public setLastClickable(boolean  $clickable = TRUE) : static
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $clickable  |  |

**Returns:** static


<a name="method_toArray" class="anchor"></a>
#### public toArray() : array

```
public toArray() : array
```

**Summary**

Get breadcrumbs

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)

**Returns:** array - Keys of elements: title, link


<a name="method_isHomeShown" class="anchor"></a>
#### public isHomeShown() : boolean

```
public isHomeShown() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)

**Returns:** boolean


<a name="method_isLastClickable" class="anchor"></a>
#### public isLastClickable() : boolean

```
public isLastClickable() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\BreadCrumbs](../classes/PHPFusion.BreadCrumbs.md)

**Returns:** boolean



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
