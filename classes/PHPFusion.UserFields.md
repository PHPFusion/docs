# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\UserFields
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class QuantumFields

---
### Constants
* No constants found
---
### Properties
* [public $system_title](../classes/PHPFusion.UserFields.md#property_system_title)
* [public $admin_rights](../classes/PHPFusion.UserFields.md#property_admin_rights)
* [public $category_db](../classes/PHPFusion.UserFields.md#property_category_db)
* [public $field_db](../classes/PHPFusion.UserFields.md#property_field_db)
* [public $plugin_folder](../classes/PHPFusion.UserFields.md#property_plugin_folder)
* [public $plugin_locale_folder](../classes/PHPFusion.UserFields.md#property_plugin_locale_folder)
* [public $method](../classes/PHPFusion.UserFields.md#property_method)
* [public $debug](../classes/PHPFusion.UserFields.md#property_debug)
* [public $displayTerms](../classes/PHPFusion.UserFields.md#property_displayTerms)
* [public $displayValidation](../classes/PHPFusion.UserFields.md#property_displayValidation)
* [public $formaction](../classes/PHPFusion.UserFields.md#property_formaction)
* [public $formname](../classes/PHPFusion.UserFields.md#property_formname)
* [public $postName](../classes/PHPFusion.UserFields.md#property_postName)
* [public $postValue](../classes/PHPFusion.UserFields.md#property_postValue)
* [public $showAdminOptions](../classes/PHPFusion.UserFields.md#property_showAdminOptions)
* [public $showAdminPass](../classes/PHPFusion.UserFields.md#property_showAdminPass)
* [public $showAvatarInput](../classes/PHPFusion.UserFields.md#property_showAvatarInput)
* [public $baseRequest](../classes/PHPFusion.UserFields.md#property_baseRequest)
* [public $skipCurrentPass](../classes/PHPFusion.UserFields.md#property_skipCurrentPass)
* [public $registration](../classes/PHPFusion.UserFields.md#property_registration)
* [public $userData](../classes/PHPFusion.UserFields.md#property_userData)
* [public $locale_file](../classes/PHPFusion.UserFields.md#property_locale_file)
* [public $paginate](../classes/PHPFusion.UserFields.md#property_paginate)
* [public $admin_mode](../classes/PHPFusion.UserFields.md#property_admin_mode)
* [public $options](../classes/PHPFusion.UserFields.md#property_options)
* [protected $callback_data](../classes/PHPFusion.QuantumFields.md#property_callback_data)
* [protected $fields](../classes/PHPFusion.QuantumFields.md#property_fields)
* [protected $cat_list](../classes/PHPFusion.QuantumFields.md#property_cat_list)
* [protected $module_debug](../classes/PHPFusion.QuantumFields.md#property_module_debug)
* [private $input_page](../classes/PHPFusion.QuantumFields.md#property_input_page)
* [private $locale](../classes/PHPFusion.QuantumFields.md#property_locale)
* [private $page_list](../classes/PHPFusion.QuantumFields.md#property_page_list)
* [private $page](../classes/PHPFusion.QuantumFields.md#property_page)
* [private $enabled_fields](../classes/PHPFusion.QuantumFields.md#property_enabled_fields)
* [private $get_available_modules](../classes/PHPFusion.QuantumFields.md#property_get_available_modules)
* [private $available_field_info](../classes/PHPFusion.QuantumFields.md#property_available_field_info)
* [private $user_field_dbinfo](../classes/PHPFusion.QuantumFields.md#property_user_field_dbinfo)
* [private $field_data](../classes/PHPFusion.QuantumFields.md#property_field_data)
* [private $field_cat_data](../classes/PHPFusion.QuantumFields.md#property_field_cat_data)
* [private $output_fields](../classes/PHPFusion.QuantumFields.md#property_output_fields)
* [private $field_cat_index](../classes/PHPFusion.QuantumFields.md#property_field_cat_index)
* [private $username_change](../classes/PHPFusion.UserFields.md#property_username_change)
* [private $info](../classes/PHPFusion.UserFields.md#property_info)
* [private $default_options](../classes/PHPFusion.UserFields.md#property_default_options)
---
### Methods
* [public __construct()](../classes/PHPFusion.QuantumFields.md#method___construct)
* [public fusionGetLocale()](../classes/PHPFusion.QuantumFields.md#method_fusionGetLocale)
* [public serializeFields()](../classes/PHPFusion.QuantumFields.md#method_serializeFields)
* [public isSerialized()](../classes/PHPFusion.QuantumFields.md#method_isSerialized)
* [public setMethod()](../classes/PHPFusion.QuantumFields.md#method_setMethod)
* [public setLocale()](../classes/PHPFusion.QuantumFields.md#method_setLocale)
* [public setPluginFolder()](../classes/PHPFusion.QuantumFields.md#method_setPluginFolder)
* [public setPluginLocaleFolder()](../classes/PHPFusion.QuantumFields.md#method_setPluginLocaleFolder)
* [public setSystemTitle()](../classes/PHPFusion.QuantumFields.md#method_setSystemTitle)
* [public setCategoryDb()](../classes/PHPFusion.QuantumFields.md#method_setCategoryDb)
* [public setFieldDb()](../classes/PHPFusion.QuantumFields.md#method_setFieldDb)
* [public setCallbackData()](../classes/PHPFusion.QuantumFields.md#method_setCallbackData)
* [public setAdminRights()](../classes/PHPFusion.QuantumFields.md#method_setAdminRights)
* [public getCatList()](../classes/PHPFusion.QuantumFields.md#method_getCatList)
* [public getFields()](../classes/PHPFusion.QuantumFields.md#method_getFields)
* [public displayQuantumAdmin()](../classes/PHPFusion.QuantumFields.md#method_displayQuantumAdmin)
* [public loadFields()](../classes/PHPFusion.QuantumFields.md#method_loadFields)
* [public loadFieldCats()](../classes/PHPFusion.QuantumFields.md#method_loadFieldCats)
* [public parseLabel()](../classes/PHPFusion.QuantumFields.md#method_parseLabel)
* [public view()](../classes/PHPFusion.QuantumFields.md#method_view)
* [public displayFields()](../classes/PHPFusion.QuantumFields.md#method_displayFields)
* [public quantumAdminButtons()](../classes/PHPFusion.QuantumFields.md#method_quantumAdminButtons)
* [public getDynamicsType()](../classes/PHPFusion.QuantumFields.md#method_getDynamicsType)
* [public quantumCategoryForm()](../classes/PHPFusion.QuantumFields.md#method_quantumCategoryForm)
* [public quantumMultilocaleFields()](../classes/PHPFusion.QuantumFields.md#method_quantumMultilocaleFields)
* [public quantumInsert()](../classes/PHPFusion.QuantumFields.md#method_quantumInsert)
* [public returnFieldsInput()](../classes/PHPFusion.QuantumFields.md#method_returnFieldsInput)
* [public logUserAction()](../classes/PHPFusion.QuantumFields.md#method_logUserAction)
* [public parse_label()](../classes/PHPFusion.QuantumFields.md#method_parse_label) - (deprecated)
* [public quantum_multilocale_fields()](../classes/PHPFusion.QuantumFields.md#method_quantum_multilocale_fields) - (deprecated)
* [public add_column()](../classes/SqlHandler.md#method_add_column)
* [public drop_column()](../classes/SqlHandler.md#method_drop_column)
* [public build_table()](../classes/SqlHandler.md#method_build_table)
* [public transfer_table()](../classes/SqlHandler.md#method_transfer_table)
* [public drop_table()](../classes/SqlHandler.md#method_drop_table)
* [public rename_column()](../classes/SqlHandler.md#method_rename_column)
* [public move_column()](../classes/SqlHandler.md#method_move_column)
* [public checkUserField()](../classes/PHPFusion.UserFields.md#method_checkUserField)
* [public setUserNameChange()](../classes/PHPFusion.UserFields.md#method_setUserNameChange)
* [public displayProfileInput()](../classes/PHPFusion.UserFields.md#method_displayProfileInput)
* [public getInputValue()](../classes/PHPFusion.UserFields.md#method_getInputValue)
* [public displayProfileOutput()](../classes/PHPFusion.UserFields.md#method_displayProfileOutput)
* [public getUserData()](../classes/PHPFusion.UserFields.md#method_getUserData)
* [private moveFields()](../classes/PHPFusion.QuantumFields.md#method_moveFields)
* [private deleteCategory()](../classes/PHPFusion.QuantumFields.md#method_deleteCategory)
* [private validateFieldCat()](../classes/PHPFusion.QuantumFields.md#method_validateFieldCat)
* [private validateField()](../classes/PHPFusion.QuantumFields.md#method_validateField)
* [private deleteFields()](../classes/PHPFusion.QuantumFields.md#method_deleteFields)
* [private getAvailableModules()](../classes/PHPFusion.QuantumFields.md#method_getAvailableModules)
* [private filenameToTitle()](../classes/PHPFusion.QuantumFields.md#method_filenameToTitle)
* [private quantumDynamicsForm()](../classes/PHPFusion.QuantumFields.md#method_quantumDynamicsForm)
* [private createFields()](../classes/PHPFusion.QuantumFields.md#method_createFields)
* [private dynamicsFieldInfo()](../classes/PHPFusion.QuantumFields.md#method_dynamicsFieldInfo)
* [private displayModuleForm()](../classes/PHPFusion.QuantumFields.md#method_displayModuleForm)
* [private getProfileSections()](../classes/PHPFusion.UserFields.md#method_getProfileSections)
* [private renderValidation()](../classes/PHPFusion.UserFields.md#method_renderValidation)
* [private renderTerms()](../classes/PHPFusion.UserFields.md#method_renderTerms)
* [private renderButton()](../classes/PHPFusion.UserFields.md#method_renderButton)
* [private getUserFields()](../classes/PHPFusion.UserFields.md#method_getUserFields)
---
### Details
* File: [classes\PHPFusion\UserFields.php](../files/classes.PHPFusion.UserFields.md)
* Package: Default
* Class Hierarchy:  
  * [\SqlHandler](../classes/SqlHandler.md)
  * [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
  * \PHPFusion\UserFields
---
## Properties
<a name="property_system_title"></a>
#### public $system_title : 
---
**Summary**

Set the Quantum System Fields Page Title

**Type:** 

**Details:**


<a name="property_admin_rights"></a>
#### public $admin_rights : string
---
**Summary**

Set the admin rights to Quantum Fields Admin

**Type:** string

**Details:**


<a name="property_category_db"></a>
#### public $category_db : string
---
**Summary**

Set the Database to install field structure records
Refer to v7.x User Fields Structrue

**Type:** string
- category_db = DB_USER_FIELDS_CAT
**Details:**


<a name="property_field_db"></a>
#### public $field_db : 
---
**Type:** 

**Details:**


<a name="property_plugin_folder"></a>
#### public $plugin_folder : string
---
**Summary**

Set system API folder paths
Refer to v7.x User Fields API

**Type:** string
- plugin_locale_folder (LOCALE.LOCALESET.&quot;user_fields/&quot;)
**Details:**


<a name="property_plugin_locale_folder"></a>
#### public $plugin_locale_folder : 
---
**Type:** 

**Details:**


<a name="property_method"></a>
#### public $method : string
---
**Summary**

Set as `display` to show array values output
Two methods - input or display

**Type:** string

**Details:**


<a name="property_debug"></a>
#### public $debug : 
---
**Type:** 

**Details:**


<a name="property_displayTerms"></a>
#### public $displayTerms : 
---
**Type:** 

**Details:**


<a name="property_displayValidation"></a>
#### public $displayValidation : 
---
**Type:** 

**Details:**


<a name="property_formaction"></a>
#### public $formaction : 
---
**Type:** 

**Details:**


<a name="property_formname"></a>
#### public $formname : 
---
**Type:** 

**Details:**


<a name="property_postName"></a>
#### public $postName : 
---
**Type:** 

**Details:**


<a name="property_postValue"></a>
#### public $postValue : 
---
**Type:** 

**Details:**


<a name="property_showAdminOptions"></a>
#### public $showAdminOptions : 
---
**Type:** 

**Details:**


<a name="property_showAdminPass"></a>
#### public $showAdminPass : 
---
**Type:** 

**Details:**


<a name="property_showAvatarInput"></a>
#### public $showAvatarInput : 
---
**Type:** 

**Details:**


<a name="property_baseRequest"></a>
#### public $baseRequest : 
---
**Type:** 

**Details:**


<a name="property_skipCurrentPass"></a>
#### public $skipCurrentPass : 
---
**Type:** 

**Details:**


<a name="property_registration"></a>
#### public $registration : 
---
**Type:** 

**Details:**


<a name="property_userData"></a>
#### public $userData : 
---
**Type:** 

**Details:**


<a name="property_locale_file"></a>
#### public $locale_file : 
---
**Type:** 

**Details:**


<a name="property_paginate"></a>
#### public $paginate : 
---
**Type:** 

**Details:**


<a name="property_admin_mode"></a>
#### public $admin_mode : 
---
**Type:** 

**Details:**


<a name="property_options"></a>
#### public $options : 
---
**Type:** 

**Details:**


<a name="property_callback_data"></a>
#### protected $callback_data : array
---
**Summary**

feed $userData or $data here to append display_fields() values
use the setter function setCallbackData()

**Type:** array

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_fields"></a>
#### protected $fields : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_cat_list"></a>
#### protected $cat_list : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_module_debug"></a>
#### protected $module_debug : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_input_page"></a>
#### private $input_page : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_page_list"></a>
#### private $page_list : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_page"></a>
#### private $page : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_enabled_fields"></a>
#### private $enabled_fields : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_get_available_modules"></a>
#### private $get_available_modules : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_available_field_info"></a>
#### private $available_field_info : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_user_field_dbinfo"></a>
#### private $user_field_dbinfo : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_field_data"></a>
#### private $field_data : 
---
**Summary**

Setters

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_field_cat_data"></a>
#### private $field_cat_data : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_output_fields"></a>
#### private $output_fields : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_field_cat_index"></a>
#### private $field_cat_index : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)


<a name="property_username_change"></a>
#### private $username_change : 
---
**Type:** 

**Details:**


<a name="property_info"></a>
#### private $info : 
---
**Type:** 

**Details:**


<a name="property_default_options"></a>
#### private $default_options : 
---
**Type:** 

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_fusionGetLocale" class="anchor"></a>
#### public fusionGetLocale() : array&amp;#124;boolean&amp;#124;mixed&amp;#124;string&amp;#124;null

```
Static public fusionGetLocale(array  $data, string  $input_name) : array&amp;#124;boolean&amp;#124;mixed&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  |  |
| <code>string</code> | $input_name  |  |

**Returns:** array&#124;boolean&#124;mixed&#124;string&#124;null


<a name="method_serializeFields" class="anchor"></a>
#### public serializeFields() : boolean&amp;#124;string

```
Static public serializeFields(string  $input_name) : boolean&amp;#124;string
```

**Summary**

Short serialization function.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |

**Returns:** boolean&#124;string


<a name="method_isSerialized" class="anchor"></a>
#### public isSerialized() : boolean

```
Static public isSerialized(string  $value, boolean&amp;#124;null  $result = NULL) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |
| <code>boolean&#124;null</code> | $result  |  |

**Returns:** boolean


<a name="method_setMethod" class="anchor"></a>
#### public setMethod() 

```
public setMethod(string  $method) 
```

**Summary**

`input` renders field.

**Description**

`display` renders data

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $method  | ('input' or 'display') |




<a name="method_setLocale" class="anchor"></a>
#### public setLocale() 

```
public setLocale(mixed  $locale) 
```

**Summary**

Set Quantum system locale

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $locale  |  |




<a name="method_setPluginFolder" class="anchor"></a>
#### public setPluginFolder() 

```
public setPluginFolder(mixed  $plugin_folder_path) 
```

**Summary**

If modules are used, specify fields module path
API follows Version 7.00's User Fields module.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $plugin_folder_path  |  |




<a name="method_setPluginLocaleFolder" class="anchor"></a>
#### public setPluginLocaleFolder() 

```
public setPluginLocaleFolder(string  $locale_folder_path) 
```

**Summary**

If modules are used, specify fields module locale libs folder path
API follows Version 7.00's User Fields Module.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $locale_folder_path  |  |




<a name="method_setSystemTitle" class="anchor"></a>
#### public setSystemTitle() 

```
public setSystemTitle(string  $system_title) 
```

**Summary**

Give your Quantum based system a name. Will add to breadcrumbs if available.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $system_title  |  |




<a name="method_setCategoryDb" class="anchor"></a>
#### public setCategoryDb() 

```
public setCategoryDb(string  $category_db) 
```

**Summary**

Database Handler for Category Structuring
If it does not exist, quantum will automatically build a template onload.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $category_db  |  |




<a name="method_setFieldDb" class="anchor"></a>
#### public setFieldDb() 

```
public setFieldDb(string  $field_db) 
```

**Summary**

Database Handler for Field Structuring
If it does not exist, quantum will automatically build a template onload.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field_db  |  |




<a name="method_setCallbackData" class="anchor"></a>
#### public setCallbackData() 

```
public setCallbackData(array  $callback_data) 
```

**Summary**

Additional data-id referencing.

**Description**

$userdata for instance.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $callback_data  |  |




<a name="method_setAdminRights" class="anchor"></a>
#### public setAdminRights() 

```
public setAdminRights(string  $admin_rights) 
```

**Summary**

The internal admin rights by a user to use this system.

**Description**

if specified, to lock down to certain user rights.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $admin_rights  |  |




<a name="method_getCatList" class="anchor"></a>
#### public getCatList() : array

```
public getCatList() : array
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)

**Returns:** array


<a name="method_getFields" class="anchor"></a>
#### public getFields() : array

```
public getFields(string  $key = NULL) : array
```

**Summary**

Get results from running load_structure

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array


<a name="method_displayQuantumAdmin" class="anchor"></a>
#### public displayQuantumAdmin() 

```
public displayQuantumAdmin() 
```

**Summary**

UF Admin

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_loadFields" class="anchor"></a>
#### public loadFields() 

```
public loadFields() 
```

**Summary**

Load fields

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_loadFieldCats" class="anchor"></a>
#### public loadFieldCats() 

```
public loadFieldCats() 
```

**Summary**

Returns $this->page_list and $this->cat_list

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_parseLabel" class="anchor"></a>
#### public parseLabel() : string

```
Static public parseLabel(string  $value) : string
```

**Summary**

Parse the correct label language. Requires serialized $value.

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  | Serialized |

**Returns:** string - NOTE: If your field does not parse properly, check your column length. Set it to TEXT NOT NULL.


<a name="method_view" class="anchor"></a>
#### public view() 

```
public view() 
```

**Summary**

UF admin UI

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_displayFields" class="anchor"></a>
#### public displayFields() : array&amp;#124;boolean&amp;#124;string

```
public displayFields(array  $data, mixed  $callback_data, string  $method = &#039;input&#039;, array  $options = array()) : array&amp;#124;boolean&amp;#124;string
```

**Summary**

Display fields for each fieldDB record entry

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | The array of the user field. |
| <code>mixed</code> | $callback_data  |  |
| <code>string</code> | $method  | Possible valie: input, display. In case of any other value the method return false. |
| <code>array</code> | $options  |  |

**Returns:** array&#124;boolean&#124;string - False on failure, string if $method 'display' or array if $method is 'input'


<a name="method_quantumAdminButtons" class="anchor"></a>
#### public quantumAdminButtons() 

```
public quantumAdminButtons() 
```

**Summary**

Outputs Quantum Admin Button Sets

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_getDynamicsType" class="anchor"></a>
#### public getDynamicsType() : array

```
public getDynamicsType() : array
```

**Summary**

Array of available field types

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)

**Returns:** array


<a name="method_quantumCategoryForm" class="anchor"></a>
#### public quantumCategoryForm() : string

```
public quantumCategoryForm() : string
```

**Summary**

Category Form

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)

**Returns:** string


<a name="method_quantumMultilocaleFields" class="anchor"></a>
#### public quantumMultilocaleFields() : string

```
Static public quantumMultilocaleFields(string  $input_name, string  $title, mixed  $input_value, array  $options = array()) : string
```

**Summary**

Multiple locale fields input

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |
| <code>string</code> | $title  |  |
| <code>mixed</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string


<a name="method_quantumInsert" class="anchor"></a>
#### public quantumInsert() 

```
public quantumInsert(array  $data = array()) 
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  |  |




<a name="method_returnFieldsInput" class="anchor"></a>
#### public returnFieldsInput() : array

```
public returnFieldsInput(string  $db, string  $primary_key, boolean  $callback_data = FALSE) : array
```

**Summary**

Return sanitized post values of input fields

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  |  |
| <code>string</code> | $primary_key  |  |
| <code>boolean</code> | $callback_data  |  |

**Returns:** array


<a name="method_logUserAction" class="anchor"></a>
#### public logUserAction() 

```
public logUserAction(string  $db, string  $primary_key) 
```

**Summary**

Logs the user actions

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  |  |
| <code>string</code> | $primary_key  |  |




<a name="method_parse_label" class="anchor"></a>
#### (deprecated) - public parse_label() : string

```
Static public parse_label(string  $value) : string
```

**Summary**

Parse the correct label language. Requires serialized $value.

**Deprecated**
Deprecateduse parseLabel()
**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  | Serialized |

**Returns:** string


<a name="method_quantum_multilocale_fields" class="anchor"></a>
#### (deprecated) - public quantum_multilocale_fields() : string

```
Static public quantum_multilocale_fields(string  $input_name, string  $title, mixed  $input_value, array  $options = array()) : string
```

**Summary**

Multiple locale fields input

**Deprecated**
Deprecateduse quantumMultilocaleFields()
**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  |  |
| <code>string</code> | $title  |  |
| <code>mixed</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string


<a name="method_add_column" class="anchor"></a>
#### public add_column() 

```
Static public add_column(string  $table_name, string  $new_column_name, string  $field_attributes) 
```

**Summary**

Add column to a specific table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $new_column_name  |  |
| <code>string</code> | $field_attributes  |  |




<a name="method_drop_column" class="anchor"></a>
#### public drop_column() 

```
Static public drop_column(string  $table_name, string  $old_column_name) 
```

**Summary**

Drop column of a table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $old_column_name  |  |




<a name="method_build_table" class="anchor"></a>
#### public build_table() : mixed

```
Static public build_table(string  $new_table, string  $primary_column) : mixed
```

**Summary**

Build a new table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $new_table  |  |
| <code>string</code> | $primary_column  |  |

**Returns:** mixed


<a name="method_transfer_table" class="anchor"></a>
#### public transfer_table() 

```
Static public transfer_table(string  $old_table, string  $new_table) 
```

**Summary**

Move old table to new table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |
| <code>string</code> | $new_table  |  |




<a name="method_drop_table" class="anchor"></a>
#### public drop_table() 

```
Static public drop_table(string  $old_table) 
```

**Summary**

Drop table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |




<a name="method_rename_column" class="anchor"></a>
#### public rename_column() 

```
Static public rename_column(string  $table_name, string  $old_column_name, string  $new_column_name, string  $field_attributes) 
```

**Summary**

Rename column name.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $old_column_name  |  |
| <code>string</code> | $new_column_name  |  |
| <code>string</code> | $field_attributes  |  |




<a name="method_move_column" class="anchor"></a>
#### public move_column() 

```
Static public move_column(string  $old_table, string  $new_table, string  $column_name) 
```

**Summary**

Move a single column from one table to another.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |
| <code>string</code> | $new_table  |  |
| <code>string</code> | $column_name  |  |




<a name="method_checkUserField" class="anchor"></a>
#### public checkUserField() : boolean

```
Static public checkUserField(string  $field_name) : boolean
```

**Summary**

Check whether a user field is available/installed

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field_name  |  |

**Returns:** boolean


<a name="method_setUserNameChange" class="anchor"></a>
#### public setUserNameChange() 

```
public setUserNameChange(  $value) 
```

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |




<a name="method_displayProfileInput" class="anchor"></a>
#### public displayProfileInput() 

```
public displayProfileInput() 
```

**Summary**

Display Input Fields

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)




<a name="method_getInputValue" class="anchor"></a>
#### public getInputValue() : integer&amp;#124;mixed&amp;#124;string&amp;#124;null

```
public getInputValue(string  $key) : integer&amp;#124;mixed&amp;#124;string&amp;#124;null
```

**Summary**

Check for input value of profile form

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** integer&#124;mixed&#124;string&#124;null


<a name="method_displayProfileOutput" class="anchor"></a>
#### public displayProfileOutput() 

```
public displayProfileOutput() 
```

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)




<a name="method_getUserData" class="anchor"></a>
#### public getUserData() : array&amp;#124;null

```
public getUserData(string  $key = NULL) : array&amp;#124;null
```

**Summary**

Get User Data of the current page.

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array&#124;null


<a name="method_moveFields" class="anchor"></a>
#### private moveFields() 

```
private moveFields() 
```

**Summary**

Move fields order - up and down

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_deleteCategory" class="anchor"></a>
#### private deleteCategory() 

```
private deleteCategory() 
```

**Summary**

Delete category

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_validateFieldCat" class="anchor"></a>
#### private validateFieldCat() : false&amp;#124;integer

```
private validateFieldCat(integer  $field_cat_id) : false&amp;#124;integer
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $field_cat_id  |  |

**Returns:** false&#124;integer


<a name="method_validateField" class="anchor"></a>
#### private validateField() : false&amp;#124;integer

```
private validateField(integer  $field_id) : false&amp;#124;integer
```

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $field_id  |  |

**Returns:** false&#124;integer


<a name="method_deleteFields" class="anchor"></a>
#### private deleteFields() 

```
private deleteFields() 
```

**Summary**

Delete fields

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_getAvailableModules" class="anchor"></a>
#### private getAvailableModules() 

```
private getAvailableModules() 
```

**Summary**

Get available modules

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_filenameToTitle" class="anchor"></a>
#### private filenameToTitle() : string

```
private filenameToTitle(string  $filename) : string
```

**Summary**

Get the field title from filename

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filename  |  |

**Returns:** string


<a name="method_quantumDynamicsForm" class="anchor"></a>
#### private quantumDynamicsForm() 

```
private quantumDynamicsForm() 
```

**Summary**

The master form for Adding or Editing Dynamic Fields

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_createFields" class="anchor"></a>
#### private createFields() 

```
private createFields(array  $data, string  $type = &#039;dynamics&#039;) 
```

**Summary**

Field creation

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  |  |
| <code>string</code> | $type  |  |




<a name="method_dynamicsFieldInfo" class="anchor"></a>
#### private dynamicsFieldInfo() 

```
private dynamicsFieldInfo(  $type,   $default_value) 
```

**Summary**

Single array output match against $db - use get_structureData before to populate $fields

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $type  |  |
| <code></code> | $default_value  |  |




<a name="method_displayModuleForm" class="anchor"></a>
#### private displayModuleForm() 

```
private displayModuleForm() 
```

**Summary**

Modules Form

**Details:**
* Inherited From: [\PHPFusion\QuantumFields](../classes/PHPFusion.QuantumFields.md)




<a name="method_getProfileSections" class="anchor"></a>
#### private getProfileSections() : array

```
private getProfileSections() : array
```

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)

**Returns:** array


<a name="method_renderValidation" class="anchor"></a>
#### private renderValidation() : string

```
private renderValidation() : string
```

**Summary**

Display Captcha

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)

**Returns:** string


<a name="method_renderTerms" class="anchor"></a>
#### private renderTerms() : string

```
private renderTerms() : string
```

**Summary**

Display Terms of Agreement Field

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)

**Returns:** string


<a name="method_renderButton" class="anchor"></a>
#### private renderButton() : string

```
private renderButton() : string
```

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)

**Returns:** string


<a name="method_getUserFields" class="anchor"></a>
#### private getUserFields() 

```
private getUserFields() 
```

**Summary**

Fetch User Fields Array to templates
Toggle with class string method - input or display
output to array

**Details:**
* Inherited From: [\PHPFusion\UserFields](../classes/PHPFusion.UserFields.md)





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
