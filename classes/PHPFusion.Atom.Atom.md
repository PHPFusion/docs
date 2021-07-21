# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Atom\Atom
### Namespace: [\PHPFusion\Atom](../namespaces/PHPFusion.Atom.md)
---
---
### Constants
* No constants found
---
### Properties
* [public $target_folder](../classes/PHPFusion.Atom.Atom.md#property_target_folder)
* [public $theme_name](../classes/PHPFusion.Atom.Atom.md#property_theme_name)
* [public $compress](../classes/PHPFusion.Atom.Atom.md#property_compress)
* [public $debug](../classes/PHPFusion.Atom.Atom.md#property_debug)
* [public $compiler](../classes/PHPFusion.Atom.Atom.md#property_compiler)
* [private $font_decoration_options](../classes/PHPFusion.Atom.Atom.md#property_font_decoration_options)
* [private $fills](../classes/PHPFusion.Atom.Atom.md#property_fills)
* [private $text_weight](../classes/PHPFusion.Atom.Atom.md#property_text_weight)
* [private $text_decoration](../classes/PHPFusion.Atom.Atom.md#property_text_decoration)
* [private $text_style](../classes/PHPFusion.Atom.Atom.md#property_text_style)
* [private $data](../classes/PHPFusion.Atom.Atom.md#property_data)
* [private $less_var](../classes/PHPFusion.Atom.Atom.md#property_less_var)
---
### Methods
* [public displayThemeOverview()](../classes/PHPFusion.Atom.Atom.md#method_displayThemeOverview)
* [public displayThemeWidgets()](../classes/PHPFusion.Atom.Atom.md#method_displayThemeWidgets)
* [public themeEditor()](../classes/PHPFusion.Atom.Atom.md#method_themeEditor)
* [public saveTheme()](../classes/PHPFusion.Atom.Atom.md#method_saveTheme)
* [public parseFonts()](../classes/PHPFusion.Atom.Atom.md#method_parseFonts)
* [public parseFontSet()](../classes/PHPFusion.Atom.Atom.md#method_parseFontSet)
* [public parseSize()](../classes/PHPFusion.Atom.Atom.md#method_parseSize)
* [public baseFonts()](../classes/PHPFusion.Atom.Atom.md#method_baseFonts)
* [public googleFonts()](../classes/PHPFusion.Atom.Atom.md#method_googleFonts)
* [protected buildCss()](../classes/PHPFusion.Atom.Atom.md#method_buildCss)
* [private setLessVariables()](../classes/PHPFusion.Atom.Atom.md#method_setLessVariables)
* [private parseFontWeight()](../classes/PHPFusion.Atom.Atom.md#method_parseFontWeight)
* [private parseFontStyle()](../classes/PHPFusion.Atom.Atom.md#method_parseFontStyle)
* [private parseFontDecoration()](../classes/PHPFusion.Atom.Atom.md#method_parseFontDecoration)
* [private fontAdmin()](../classes/PHPFusion.Atom.Atom.md#method_fontAdmin)
* [private layoutAdmin()](../classes/PHPFusion.Atom.Atom.md#method_layoutAdmin)
* [private navAdmin()](../classes/PHPFusion.Atom.Atom.md#method_navAdmin)
---
### Details
* File: [classes\PHPFusion\Atom\Atom.php](../files/classes.PHPFusion.Atom.Atom.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\Atom\Atom
---
## Properties
<a name="property_target_folder"></a>
#### public $target_folder : 
---
**Type:** 

**Details:**


<a name="property_theme_name"></a>
#### public $theme_name : 
---
**Type:** 

**Details:**


<a name="property_compress"></a>
#### public $compress : 
---
**Type:** 

**Details:**


<a name="property_debug"></a>
#### public $debug : 
---
**Type:** 

**Details:**


<a name="property_compiler"></a>
#### public $compiler : 
---
**Type:** 

**Details:**


<a name="property_font_decoration_options"></a>
#### private $font_decoration_options : 
---
**Type:** 

**Details:**


<a name="property_fills"></a>
#### private $fills : 
---
**Type:** 

**Details:**


<a name="property_text_weight"></a>
#### private $text_weight : 
---
**Summary**

For internals CSS compilers - These are actual css properties. Do not translate.

**Type:** 

**Details:**


<a name="property_text_decoration"></a>
#### private $text_decoration : 
---
**Type:** 

**Details:**


<a name="property_text_style"></a>
#### private $text_style : 
---
**Type:** 

**Details:**


<a name="property_data"></a>
#### private $data : array
---
**Summary**

Initialize Data

**Type:** array

**Details:**


<a name="property_less_var"></a>
#### private $less_var : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method_displayThemeOverview" class="anchor"></a>
#### public displayThemeOverview() 

```
public displayThemeOverview() 
```

**Summary**

Theme Overview Page

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_displayThemeWidgets" class="anchor"></a>
#### public displayThemeWidgets() 

```
public displayThemeWidgets() 
```

**Summary**

Theme Widget Page

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_themeEditor" class="anchor"></a>
#### public themeEditor() 

```
public themeEditor() 
```

**Summary**

Theme Styler Page
Edit done, save done. Now load.

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_saveTheme" class="anchor"></a>
#### public saveTheme() 

```
public saveTheme() 
```

**Summary**

Save theme

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_parseFonts" class="anchor"></a>
#### public parseFonts() : string&amp;#124;null

```
Static public parseFonts(string  $font) : string&amp;#124;null
```

**Summary**

Parse fonts

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** string&#124;null


<a name="method_parseFontSet" class="anchor"></a>
#### public parseFontSet() : string

```
Static public parseFontSet(string  $font) : string
```

**Summary**

Parse font set

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** string


<a name="method_parseSize" class="anchor"></a>
#### public parseSize() : integer&amp;#124;string

```
Static public parseSize(string  $font) : integer&amp;#124;string
```

**Summary**

Parse font size

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** integer&#124;string


<a name="method_baseFonts" class="anchor"></a>
#### public baseFonts() : array&lt;mixed,string&gt;

```
Static public baseFonts() : array&lt;mixed,string&gt;
```

**Summary**

Return base fonts

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)

**Returns:** array&lt;mixed,string&gt;


<a name="method_googleFonts" class="anchor"></a>
#### public googleFonts() : array&lt;mixed,string&gt;

```
Static public googleFonts() : array&lt;mixed,string&gt;
```

**Summary**

Return Google Fonts

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)

**Returns:** array&lt;mixed,string&gt;


<a name="method_buildCss" class="anchor"></a>
#### protected buildCss() : string&amp;#124;null

```
protected buildCss() : string&amp;#124;null
```

**Summary**

Build CSS

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)

**Returns:** string&#124;null


<a name="method_setLessVariables" class="anchor"></a>
#### private setLessVariables() 

```
private setLessVariables() 
```

**Summary**

Set LESS vars

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_parseFontWeight" class="anchor"></a>
#### private parseFontWeight() : string

```
private parseFontWeight(string  $font) : string
```

**Summary**

Parse font weight

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** string


<a name="method_parseFontStyle" class="anchor"></a>
#### private parseFontStyle() : string

```
private parseFontStyle(string  $font) : string
```

**Summary**

Parse font style

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** string


<a name="method_parseFontDecoration" class="anchor"></a>
#### private parseFontDecoration() : string

```
private parseFontDecoration(string  $font) : string
```

**Summary**

Parse text decoration

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $font  |  |

**Returns:** string


<a name="method_fontAdmin" class="anchor"></a>
#### private fontAdmin() 

```
private fontAdmin() 
```

**Summary**

Fonts admin

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_layoutAdmin" class="anchor"></a>
#### private layoutAdmin() 

```
private layoutAdmin() 
```

**Summary**

Administration

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)




<a name="method_navAdmin" class="anchor"></a>
#### private navAdmin() 

```
private navAdmin() 
```

**Summary**

Admin navigation

**Details:**
* Inherited From: [\PHPFusion\Atom\Atom](../classes/PHPFusion.Atom.Atom.md)





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
