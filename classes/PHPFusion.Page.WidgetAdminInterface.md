# [PHPFusion Docs](../home.md)

# Interface: WidgetAdminInterface
### Namespace: [\PHPFusion\Page](../namespaces/PHPFusion.Page.md)
---
**Summary:**

Interface WidgetInterface
This is the standard for the Widget Object

---
### Constants
* No constants found
---
### Methods
* [public widgetInstance()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_widgetInstance)
* [public excludeReturn()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_excludeReturn)
* [public validateInput()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_validateInput)
* [public validateSettings()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_validateSettings)
* [public validateDelete()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_validateDelete)
* [public displayFormInput()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_displayFormInput)
* [public displayFormButton()](../classes/PHPFusion.Page.WidgetAdminInterface.md#method_displayFormButton)

---
### Details
* File: [classes\PHPFusion\Page\WidgetAdminInterface.php](../files/classes.PHPFusion.Page.WidgetAdminInterface.md)
* Package: \Default
---
## Methods
<a name="method_widgetInstance" class="anchor"></a>
#### public widgetInstance() 

```
Static public widgetInstance() 
```

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)




<a name="method_excludeReturn" class="anchor"></a>
#### public excludeReturn() : array

```
public excludeReturn() : array
```

**Summary**

Returns the exclude key of a clean_request of your widget when save or update redirects

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)

**Returns:** array


<a name="method_validateInput" class="anchor"></a>
#### public validateInput() : string

```
public validateInput() : string
```

**Summary**

Validate all $_POST of your form and returns a page content serialized string from your form inputs
The post button value that reads this function is 'widget'
Return is saved into 'page_content' column of DB_PAGES_CONTENT table (i.e. $self::$colData)

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)

**Returns:** string - - serialized array


<a name="method_validateSettings" class="anchor"></a>
#### public validateSettings() : string

```
public validateSettings() : string
```

**Summary**

Validate all $_POST of your form and returns a page settings serialized string from your form inputs
The post button value that reads this function is 'settings'
Return is saved into 'page_options' column of DB_PAGES_CONTENT table (i.e. $self::$colData)

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)

**Returns:** string - - serialized array


<a name="method_validateDelete" class="anchor"></a>
#### public validateDelete() : mixed

```
public validateDelete() : mixed
```

**Summary**

The execution of codes extra when delete column button is pressed
Use this to delete and prune tables if needed, if not leave body blank

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)

**Returns:** mixed


<a name="method_displayFormInput" class="anchor"></a>
#### public displayFormInput() 

```
public displayFormInput() 
```

**Summary**

This function displays your widget admin interface
Echo your designed HTML of the administration here.

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)




<a name="method_displayFormButton" class="anchor"></a>
#### public displayFormButton() : mixed

```
public displayFormButton() : mixed
```

**Summary**

This function displays your widget save buttons
There are 2 acceptable button name - save_widget and save_and_close_widget
'save_widget' will retains the same window after save/update execution
'save_and_close_widget' will close the window after save/update execution
We strongly recommend that you make both available to your user

**Description**

There are 2 acceptable button values - widget and settings
'widget' will pair with validateInput() function to return against 'page_content' column
'settings' will pair with validateSettings() function to return against 'page_options' column

**Details:**
* Inherited From: [\PHPFusion\Page\WidgetAdminInterface](../classes/PHPFusion.Page.WidgetAdminInterface.md)

**Returns:** mixed




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
